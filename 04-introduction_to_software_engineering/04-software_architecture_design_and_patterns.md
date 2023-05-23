<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Software Architecture and Design](#software-architecture-and-design)
  - [Introduction to Software Architecture](#introduction-to-software-architecture)
    - [Software architecture and design:](#software-architecture-and-design)
    - [Artifacts](#artifacts)
    - [Deployment considerations](#deployment-considerations)
  - [Software Design and Modeling](#software-design-and-modeling)
    - [Software Design:](#software-design)
    - [Behavioral models:](#behavioral-models)
  - [Object-Oriented Analysis and Design](#object-oriented-analysis-and-design)
- [Software Architecture Patterns and Deployment Topologies](#software-architecture-patterns-and-deployment-topologies)
  - [Approaches to Application Architecture](#approaches-to-application-architecture)
    - [What is component?](#what-is-component)
    - [Services](#services)
  - [Architectural Patterns in Software](#architectural-patterns-in-software)
    - [Types of architectural patterns:](#types-of-architectural-patterns)
  - [Application Deployment Environments](#application-deployment-environments)
    - [Production environment](#production-environment)
  - [Production Deployment Components](#production-deployment-components)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Software Architecture and Design

## Introduction to Software Architecture

### Software architecture and design:

- Design and documentation take place during the design phase of the SDLC
- Software architecture is the organization of the system
- Serves as a blueprint for developers
- Comprised of fundamentals structures and behaviors

**Early design decisions:**
- How components interact
- Operating environment
- Design principles
- Costly to change once implemented
- Addresses non-functional aspects

**Why software architecture is important:**

- Communication
- Earliest design decisions
- Flexibility
- Increases lifespan

**Software architecture and tech stacks:**

- Guides technology stack choice
- Tech stacks must address non-functional capabilities
- Tech stacks include:
	- Software
	- Programming languages
	- Libs
	- Frameworks
 - Architects must weigh advantages and disadvantages of tech stack choices

### Artifacts

- Software design document (SDD)
- Architectural diagrams
- Unified modeling language (UML) diagrams

1) **Software Design Document (SDD)**

- Collection of tech specs regarding design implementation
- Design considerations:
	- Assumptions
	- Dependencies
	- Constraints
	- Requirements
	- Objectives
	- Methodologies

2) **Architectural diagrams**

It displays:
- Components
- Interactions
- Constraints
- Confines
- Architectural patterns

2) **UML diagrams**

- Visually communicate structures and behaviors
- Not constrained by a programming language

### Deployment considerations

- Architecture drives production environment choices
- Production environment is the infrastructure that runs and delivers the software
	- Servers
	- Load balancers
	- Databases

## Software Design and Modeling

### Software Design:

Software design is a process to document:
- Structural components
- Behavioral attributes

Models express software design using:
- Diagrams and flowcharts
- Unified Modeling Language (UML)

**Characteristics of structured design:**

- Structural elements: modules & submodules
- Cohesive
- Loosely coupled

Structure diagram example:

![](assets/Pasted%20image%2020230523053741.png)

### Behavioral models:

- Describe what a system does but doesn’t explain how it does it
- Communicate the behavior of the system
- Many types of behavioral UML diagrams
	- State transition
	- Interaction

**Unified Modeling Language (UML):**

- Visual representations to communicate architecture, design, and implementation
- Two types: structural and behavioral
- Programming language agnostic

Advantages of Unified Modeling Language (UML):

![](assets/Pasted%20image%2020230523054125.png)

State transition diagram example:

![](assets/Pasted%20image%2020230523054212.png)

Interaction diagram:

![](assets/Pasted%20image%2020230523054301.png)

## Object-Oriented Analysis and Design

**Object-Oriented Languages:**

- A patient could be an object
- An object contains data, and an object can perform actions

![](assets/Pasted%20image%2020230523054553.png)

**Classes and objects:**

![](assets/Pasted%20image%2020230523054709.png)

**Object-Oriented analysis and design:**

- Used for a system that can be modeled by interacting objects
- OOAD allows developers to work on different aspects of the same application at the same time
- Visual UML diagrams can be made to show both static structure and dynamic behavior of a system

**Class diagram:**

![](assets/Pasted%20image%2020230523054954.png)

# Software Architecture Patterns and Deployment Topologies

## Approaches to Application Architecture

### What is component?

- An individual unit of encapsulated functionality
- Serves as a part of an application in conjunction with other components

**Component characteristics:**
1) **Reusable:** reused in different applications
2) **Replaceable:** easily replaced with another component
3) **Independent:** doesn’t have dependencies on other components
4) **Extensible:** add behavior without changing other components
5) **Encapsulated:** doesn’t expose its specific implementation
6) **Non-context specific:** operates in different environments

**Components examples:**

![](assets/Pasted%20image%2020230523060738.png)

**Component-based architecture:**

- Decomposes design into logical components
- Higher level abstraction than objects
- Defines, composes, and implements loosely coupled independent components, so they work together to create an application

### Services

- Designed to be deployed independently and reused by multiple systems
- Solution to a business need
- Has one unique, always running instance with whom multiple clients communicate

![](assets/Pasted%20image%2020230523061053.png)

**Examples of Services:**

- A service is a component that can be deployed independently
	- Checking a customer’s credit
	- Calculating a monthly loan payment
	- Processing a mortgage application

**Service-oriented architecture:**

- Loosely coupled services that communicate over a network
- Supports building distributed systems that deliver services to other applications through the communication protocol

**Distributed systems**

- Multiple services located on different machines
- Services coordinate interactions via a communication protocol such as HTTP
- Appears to the end-user as a single coherent system

**Distributed system characteristics:**

- Shares resources
- Fault-tolerant
- Multiple activities run concurrently
- Scalable
- Runs on a variety of computers
- Programmed in a variety of languages

**Nodes:**

- Any devices on a network that can recognize, process, and transmit data to other nodes on the network
- Distributed systems have multiple interconnected nodes running services

**Distributed system architectures:**

![](assets/Pasted%20image%2020230523062321.png)

## Architectural Patterns in Software

### Types of architectural patterns:

![](assets/Pasted%20image%2020230523062516.png)

**2-tier**

![](assets/Pasted%20image%2020230523062548.png)

**3-tier**

![](assets/Pasted%20image%2020230523062643.png)

**Peer-to-peer (P2P)**

![](assets/Pasted%20image%2020230523062733.png)

**Event-driven**

![](assets/Pasted%20image%2020230523062900.png)

**Microservices**

![](assets/Pasted%20image%2020230523062944.png)

**Examples:**

![](assets/Pasted%20image%2020230523063044.png)

**Combining patterns**

![](assets/Pasted%20image%2020230523063120.png)

## Application Deployment Environments

**Application environments:**

Include:
- Application code/executables
- Software stack (libs, apps, middleware, OS)
- Networking infrastructure
- Hardware (compute, memory and storage)

**Pre-production environments:**

![](assets/Pasted%20image%2020230523063423.png)

### Production environment

- Entire solution stack ++
- Intended for all users
- Take load into consideration
- Other non-functional requirements
	- Security
	- Reliability
	- Scalability
- More complex than pre-production environments

**On-premises deployment:**

- System and infrastructure reside in-house
- Offers greater control of the application
- Organization is responsible for everything
- Usually more expensive than compared to cloud deployment

**Cloud deployment types:**

![](assets/Pasted%20image%2020230523063846.png)

## Production Deployment Components

**Production deployment infrastructure:**

![](assets/Pasted%20image%2020230523064031.png)

**Web and application servers:**

![](assets/Pasted%20image%2020230523064155.png)

**Proxy server:**

- An intermediate server that handles requests between two tiers
- Can be used for load balancing, system optimization, caching, as a firewall, obscuring the source of a request, encrypting messages, scanning for malware, and more
- Can improve efficiency, privacy, and security

**Databases and database servers:**

- Databases are a collection of related data stored on a computer that can be accessed in various ways
- DBMS (Database Management System) controls a database by connecting it to users or other programs
- Database servers control the flow and storage of data
