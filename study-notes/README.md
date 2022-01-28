# TOGAF 101 

## **The Open Group** 

|      |      |  
| ----------- | ----------- | 
| Vision  | ***Boundaryless Information Flow*** Boundaries exists but permeable to enable business | 
| Mission | Creation of ***Boundaryless Information Flow*** achieved by working with customers and suppliers |
| Architecture Forum Mission | Advance the Open Group vision of ***Boundaryless Information Flow*** for and between enterprises |

## Enterprise Architecture (EA)
A discipline - 
- That defines, organises, standardizes, and documents the whole architecture and all important elements of the respective organisation, covering relevant domains such as business, digital, physical, or organisational; and 
- The relations and interactions between elements that belong to those domains, such as processes, functions, applications, events, data, or technologies

|      |      |  
| ----------- | ----------- | 
| Need | Preparation for business transformation or any radical infrastructure change initiates |
| Purpose  | To optimize across the enterprise the often fragmented legacy of processes into an integrated environment that is responsive to change and supportive of the delivery of the business strategy | 
| Benefits | More effective and efficient business operations, Digital Transformation and IT operations, Better return on existing investment, Reduced Risk for future investment, Faster, simpler, and cheaper procurement |

## Architecture Framework
- A foundational structure, or set of structures, which can be used for developing different architectures 
- Should describe a method for designing a target state of the enterprise in terms of a set of building blocks
- Should contain a set of tools and provide a common vocabulary 
- Should also include a list of recommended standards and compliant products that can be used to implement the building blocks
- Value of Architecture Framework
   - Systematic ***Codified Common Sense***
   - Avoids the initial panic when the scale of the task becomes apparent and provides a starting point for an architecture project
 
 ## Architecture
 - ISO/IEC/IEEE 42010:2011 defines "architecture" as:
   - "The fundamental concepts or properties of a system in its environment embodied in its elements, relationships, and in the principles of its design and evolution."
- TOGAF standard defines a second meaning depending upon the context:
   - "The structure of components, their inter-relationships, and the principles and guidelines governing their design and evolution over time."

## TOGAF Standard
- A Customer Initiative based on the ***Technical Architecture Framework for Information Management*** (TAFIM from US DoD)
- A ***Framework*** not ***Architecture*** to develop architectures to meet different business needs
- TOGAF as Enterprise Architecture (EA) framework
  - TOGAF provides the ***methods and tools*** for assisting in the ***Acceptance***, ***Production***, ***Use***, and ***Maintenance*** (***APUM***) of an EA. 
  - It is based on an ***Iterative Process Model*** supported by best practices and a re-usable set of existing architecture assets.
- TOGAF uses ***Architecture Development Method (ADM)*** to develop an ***Enterprise Architecture (EA)***
- TOGAF Standard helps in creating following Architecture types (BDAT) using ADM
   - ***Business Architecture (B)***: defines the business strategy, governance, organization, and key business processes
   - ***Data Architecture (D)***: describes the structure of an organization's logical and physical data assets and data management resources
   - ***Application Architecture (A)***: provides a blueprint for the applications to be deployed, their interactions, and their relationships to the core business processes
   - ***Technical Architecture (T)***: describes the logical software & hardware capabilities, required to support the deployment of business, data, and application services

## TOGAF Components
- ***Architecture Development Method (ADM)*** is a step by step approach, which is at the core of the TOGAF framework
- ***ADM Guidelines & Techniques*** contains a collection of guidelines and techniques used while applying the TOGAF ADM
- ***Architecture Content Framework*** describes a structured metamodel for architectural artifacts, using re-usable Architecture Building Blocks (ABBs)
- ***Enterprise Continuum & Tools*** discusses appropriate taxonomies and tools to categorize and store the outputs of architecture activity
- ***Architecture Capability Framework*** discusses the organization, processes, skills, roles, and responsibilities required to establish and operate an architecture function within an enterprise

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/01_structure.png" width="700"></p>

## TOGAF Architecture Development Method (ADM)
- TOGAF ADM is a compresensive method of enterprise architecture (EA) development, based on the best practices 
- TOGAF includes multiple phases to develop various architectures using following iterations
  - ***Architecture Capability (AC) Iteration*** 
  - ***Architecture Development (AD) Iteration*** 
  - ***Transition Planning (TP) Iteration*** 
  - ***Architecture Governance (AG) Iteration*** 

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/19_adm_iteration.png" width="400"></p>

## Architecture Phases (A, B, C, D)
| Phase | Name | Deliverable | Content | Version | 
| ----------- | ----------- | ----------- | ----------- | ----------- |
| A | Architecture Vision | Architecture Vision | Business Architecture, Data Architecture, Application Architecture, Technology Architecture | 0.1
| B | Business Architecture | Architecture Definition Document | Business Architecture | 1.0
| C | Information System Architecture | Architecture Definition Document | Data Architecture, Application Architecture | 1.0
| D | Technology Architecture | Architecture Definition Document | Technology Architecture | 1.0

## TOGAF Architecture Content Framework (ACF)
- Architects executing the ADM will produce architectural content as a result of their efforts. Some examples
  - Process flows
  - Architectural requirements
  - Project plans 
  - Project compliance assessments etc. 
- ACF provides a ***Structural Model for Architectural Content*** that allows major work products to be ***consistently Defined, Structured, and Presented***.
- ACF uses the following three categories (***DAB***) to describe the type of architectural work product within the context of use:
  - ***Deliverables (D)***
  - ***Artifacts (A)***
  - ***Building Blocks (B)***
    - ***Architecture Building Blocks (ABBs)***
    - ***Solution Building Blocks (SBBs)***   

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/02_concepts1.png" width="700"></p>

### Architecture Definition Document (ADD)
- ADD is a deliverable that documents an Architecture Description
- An example of the relationships between deliverables, artifacts, and building blocks is illustrated

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/02_concepts2.png" width="700"></p>

## Enterprise Continuum
- The Enterprise Continuum is as a view of the repository of all the architecture assets. 
- It can contain architecture descriptions, models, building blocks, patterns, viewpoints, and other artifacts 
- It contains the architectures that exist both within the enterprise and in the IT industry at large
- The Enterprise Continuum enables the organization of re-usable architecture artifacts and solution assets to maximize the enterprise architecture investment opportunities

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_entcon_oview.png" width="700"></p>

### Architecture Continuum
- The Architecture Continuum illustrates how architectures are developed and evolved across a continuum ranging from Foundation Architectures

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_archcon.png" width="700"></p>

### Solutions Continuum
- The Solutions Continuum is a population of the architecture with reference building blocks
- The Solutions Continuum represents the detailed specification and construction of the architectures at the corresponding levels of the Architecture Continuum

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_solcon.png" width="700"></p>
