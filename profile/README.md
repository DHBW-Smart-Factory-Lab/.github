# Project: IIoTProductBuilder

Nice that you found your way to the github Oranization Smart Factory Lab  👋

The github DHBW-Smart-Factory-Lab organization is the central point for the documentation, project organization and at the same time the management of software and system development of all projects in and around the Smart Factory Lab. The Smart Factory Lab focuses on the technological orientation of cyber-physical matrix production systems. The IIoTProductBuilder initiative was created to provide a framework for projects and theses. This "flagship" project also aims to offer a complete prototype solution for individualized manufacturing, from machine integration to the adaptability of production systems.

<!--

Table of contents
=================

<!--ts-->
   * [Conceptual Overview of the Development Goals](#conceptual-overview-of-the-development-goals)
      * [Layer 1 Process Modules](#layer-1-process-modules)
      * [Layer 2 Manufacuring Execution](#layer-2-manufacuring-execution)
      * [Layers 3 Product Interpreter and 4 Product Designer](#layers-3-product-interpreter-and-4-product-designer)
   * [Scientific Goals](#scientific-goals)
   * [References](references)
<!--te-->


Conceptual Overview of the Development Goals
============================================
<img  alt="overview product builder" src="/profile/Schichtenmodel_UmsetzungIIoTProductBuilder.drawio.png">

Layer 1 Process Modules
-----------------------
The resource modules and process modules are located at this level:<br>
A process module is the smallest production resource that can be freely approached and independently planned from a logistical point of view and that carries out several process steps. The process modules, however, can be made up of resource modules. Resource modules perform value-adding, handling or other supporting tasks. From a logistical point of view, they cannot be planned individually.<br>
In the IIoTProductBuilder project, a digital twin is to be added to the process modules. The digital twin should map the behavioral model of the real system and should have the same OPC UA interfaces in the network.

<img  alt="overview product builder" src="/profile/2024-05-14 165008.png">

As part of teaching at the DHBW, the final theses and project work from the fields of mechanical engineering, mechatronics, computer science and electrical engineering are integrated into this level of the process modules. Students are required to develop systems and models for various process modules and to create network-compatible systems. 


Layer 2 Manufacuring Execution
------------------------------
At this level, order management dominates as the main requirement. In cyber-physical matrix production systems, each order follows a specific path through the production structure. This enables cycle independence. Order control can establish the sequence of operations and order placement during operation.<br> 
<img  alt="overview product builder" src="/profile/2024-05-14 165008_2.png"><br> 
To realize the main requirement, a Plug&Work mechanism with the four basic properties as formulated by Fraunhofer IOSB is needed:<br> 
<img  alt="overview product builder" src="/profile/2024-05-14 165500.png"><br> 
AutomationML (Automation Markup Language) is being discussed here as a modeling language. It is a neutral, XML-based data format for the storage and exchange of plant design data that is available as an open standard. The aim is to exchange data in a heterogeneous tool landscape.<br> 
As part of the teaching at the DHBW, final and project work from the fields of mechanical engineering, mechatronics, computer science and electrical engineering is also offered at this level. The students are required to build real and simulated prototype cyber-physical matrix systems with existing process modules, to research the Plug&Work functionality and to develop solutions. 

Layers 3 Product Interpreter and 4 Product Designer
---------------------------
The Product Interpreter layer is located between the Product Content Management System layer. This layers are the link between the human-readable product code and the production order for the factory. <br> 
These two levels are given very low priority when it comes to implementation in the DHBW Smart Factory Lab Karlsruhe. Nevertheless, there is a great need for research here that goes beyond the scope of student project work. <br>
There is another overarching goal that the networking of smart factories aims to reach for order management. This is not dealt with as part of the DHBW Smart Factory Lab, but is included in the context of the work. For example, you can discover more here: [Smart Factory Web – ein Netzwerk intelligenter Fabriken](https://www.iosb.fraunhofer.de/de/projekte-produkte/smart-factory-web.html)

Scientific Goals
================
The main requirements for high productivity in production and resilience in the field of variance (supply chain, quantities, customer requirements) are defined by the boundary conditions of the market.  A high degree of standardization in system technology for machine integration and interoperability is also of great importance. Therefore, there is a need for application-oriented research in the design of tools for the planning and control (e.g. digital twin) of cyber-physical production matrix systems, their human/market integration and the standardization of hardware and software. 
Other barriers in practice are the high level of complexity, limited experience in suitable areas of application and cost-effectiveness. There is no overall provider in all control-relevant design fields (as of 2022). Particular challenges exist in the creation and establishment of workable business models and the networking of content, organization and application technology. 

Illustration of the conflicting goals between flexibility and productivity in production systems:
<img  alt="overview product builder" src="/profile/2024-05-02 140833.png">

References
==========
[Umsetzung von cyber-physischen Matrixproduktionssystemen (Expertise), 2022](https://www.acatech.de/publikation/umsetzung-von-cyber-physischen-matrixproduktionssystemen/) <br> 
[PLUG and WORK – Integration von Maschinen und Geräten in die digitale Fertigung, 2024](https://www.iosb.fraunhofer.de/de/geschaeftsfelder/automatisierung-digitalisierung/technologien/plug-and-work.html)<br> 
[Industrial Internet of Things (IIoT), 2024](https://www.iosb.fraunhofer.de/de/geschaeftsfelder/automatisierung-digitalisierung/anwendungsfelder/iiot.html)




