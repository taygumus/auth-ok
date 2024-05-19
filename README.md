# AuthOK

## Overview

The project documentation is structured into three main parts:

1. **Requirements Analysis**

2. **System Design**

3. **Java Implementation**

### Part I: Requirements Analysis

AuthOK is an authentication system based on a client-server architecture. The project involves building a Java library for remote communication between systems. The library exactly implements the JSON-RPC protocol specification. Leveraging this, a centralized authorization system is established for accessing specific resources. The central system maintains the list of accessible resources and tracks the permissions granted.

#### Utilized Tools:

1. **Data Dictionary**: describes the principal entities.

2. **Goal Diagrams**: i* modeling language with Strategic Dependency Model (SDM) and Strategic Rationale Model (SRM).

### Part II: System Design

The study of the UML design for the project takes on a connecting role between the analysis of requirements and the subsequent implementation phase. This is achieved through the specification and documentation of the entire software design. To perform this step several UML diagrams are utilized, including:

- **Use Case Diagram**
- **Class Diagram**
- **Two Sequence Diagrams**
- **Two Activity Diagrams**
- **Two State Diagrams**
- **One Component Diagram**
- **Deployment Diagram**
- **Object Diagram**
- **Collaboration Diagram**

The tool utilized for UML modeling is [StarUML](https://staruml.io/).

### Part III: Java Implementation

Implementing the AuthOK Java code is the final part of the software realization process. It has the objective to develop the real program which must respect all the models previously established, starting from the Goal Diagram up to the last of the UML diagrams. One at a time, all the methods were implemented and integrated with each other in order to realize the logic application of the program.