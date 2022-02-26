# TOGAF 101 

## Part 1 - Introduction

#### **The Open Group** 

   |      |      |  
   | ----------- | ----------- | 
   | Vision  | ***Boundaryless Information Flow*** Boundaries exists but permeable to enable business | 
   | Mission | Creation of ***Boundaryless Information Flow*** achieved by working with customers and suppliers |
   | Architecture Forum Mission | Advance the Open Group vision of ***Boundaryless Information Flow*** for and between enterprises |

#### Enterprise Architecture (EA)
A discipline - 
- That defines, organises, standardizes, and documents the whole architecture and all important elements of the respective organisation, covering relevant domains such as business, digital, physical, or organisational; and 
- The relations and interactions between elements that belong to those domains, such as processes, functions, applications, events, data, or technologies

   |      |      |  
   | ----------- | ----------- | 
   | Need | Preparation for business transformation or any radical infrastructure change initiates |
   | Purpose  | To optimize across the enterprise the often fragmented legacy of processes into an integrated environment that is responsive to change and supportive of the delivery of the business strategy | 
   | Benefits | More effective and efficient **_Business operations_**, Digital Transformation and **_IT operations_**, Better return on  **_Existing Investment_**, Reduced Risk for  **_Future Investment_**, Faster, simpler, and cheaper **_Procurement_** |

#### Architecture Framework
- A foundational structure, or set of structures, which can be used for developing different architectures 
- Should describe a method for designing a target state of the enterprise in terms of a set of building blocks
- Should contain a set of tools and provide a common vocabulary 
- Should also include a list of recommended standards and compliant products that can be used to implement the building blocks
- Value of Architecture Framework
   - Systematic ***Codified Common Sense***
   - Avoids the initial panic when the scale of the task becomes apparent and provides a starting point for an architecture project
 
 #### Architecture
 - ISO/IEC/IEEE 42010:2011 definition: 
   - _**The fundamental concepts or properties of a system in its environment embodied in its elements, relationships, and in the principles of its design and evolution**._
- TOGAF definition: 
   - _**The structure of components, their inter-relationships, and the principles and guidelines governing their design and evolution over time**._

#### TOGAF Standard
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

#### TOGAF Parts
1. ***Introduction*** is a step by step approach, which is at the core of the TOGAF framework
2. ***Architecture Development Method (ADM)*** is a step by step approach, which is at the core of the TOGAF framework
3. ***ADM Guidelines & Techniques*** contains a collection of guidelines and techniques used while applying the TOGAF ADM
4. ***Architecture Content Framework*** describes a structured metamodel for architectural artifacts, using re-usable Architecture Building Blocks (ABBs)
5. ***Enterprise Continuum & Tools*** discusses appropriate taxonomies and tools to categorize and store the outputs of architecture activity
6. ***Architecture Capability Framework*** discusses the organization, processes, skills, roles, and responsibilities required to establish and operate an architecture function within an enterprise

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/01_structure.png" width="700"></p>

## Part 2 - TOGAF Architecture Development Method (ADM)
- TOGAF ADM is a compresensive method of enterprise architecture (EA) development, based on the best practices 
- TOGAF includes multiple phases to develop various architectures using following iterations
  - ***Architecture Capability (AC) Iteration*** 
  - ***Architecture Development (AD) Iteration*** 
  - ***Transition Planning (TP) Iteration*** 
  - ***Architecture Governance (AG) Iteration*** 
  
<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/19_adm_iteration.png" width="400"></p>

### TOGAF ADM Stages Objectives, Input, Output and Steps ([Mind Maps](adm-stages-steps.md))
<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/adm-objective.png" width="2000"></p>
<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/adm-input.png" width="2000"></p>
<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/adm-output.png" width="2000"></p>
<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/adm-steps.png" width="2000"></p>

#### Adapting the ADM Process
- Reasons for Adapting the ADM Process
   - The order of the phases in the ADM is dependent on the maturity of the architecture discipline within the enterprise
   - Wanting to adapt the ADM is if the TOGAF framework is to be integrated with another enterprise framework
   - The ADM is one of the many corporate processes that make up the corporate governance model 
   - The ADM is being mandated for use by a prime or lead contractor in an outsourcing situation, and needs to be tailored
   - The enterprise is a small-to-medium enterprise, and wishes to use a "cut-down" method 
   - The enterprise is very large and complex, and the architecture method needs to be adapted to recognize this 


## Part 3 - ADM Guidelines and Techniquies

   |      |   |
   | ----------- |-----------  |
   | [Applying Iteration to the ADM](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap19.html) | ***Baseline First*** or ***Target First*** Architecture Definition |
   | [Architecture Principles](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap20.html) | Principle Qualities: ***URCCS- Understandable (U), Robust (R), Complete (C), Consistent (C), Stable (S)*** |
   | [Stakeholder Management](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap21.html) |  ***Used in Phase A***. It is important to pay particular attention to stakeholder interests by defining specific ***catalogs, matrices, and diagrams that are relevant*** for a particular Enterprise Architecture model. This enables the architecture to be communicated to, and understood by, all the stakeholders |
   | [Architecture Patterns](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap22.html) | ***Architecture*** Pattern, ***Design*** Pattern or  ***Idiom*** (programming language specific pattern)  |
   | [Gap Analysis](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap23.html) | ***Used in Phase E***. Highlight a shortfall between the Baseline Architecture and the Target Architecture; items that have been ***Deliberately Omitted, Accidentally Left Out, or Not Yet Defined***  |
   | [Migration Planning](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap24.html) |  ***Used in Phase E & F***. There are 5 techniques: ***Implementation Factor Assessment & Deduction Matrix***, ***Consolidated Gaps, Solutions, & Dependencies Matrix***, ***Architecture Definition Increments Table***, ***Transition Architecture State Evolution Table***, ***Business Value Assessment Technique*** |
   | [Business Transformation Readiness Assessment (BRTP)](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap25.html) | The BTRP results goes to ***Phases B-C-D Capability Assessment***   |
   | [Risk Management](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap26.html) |   ***Initial Risk*** (prior to mitigating actions) and ***Residual Risk*** (after mitigating actions) |
   | [Capability-Based Planning](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap27.html) |  Often the need for these capabilities are discovered and refined using business scenarios |

#### Principles
- Principles are general rules and guidelines, intended to be ***enduring and seldom amended***
- Recommended template for Principles
   
   |      |      |  
   | ----------- | ----------- | 
   | ***Name*** | Should both represent the essence of the rule as well as be easy to remember |
   | ***Statement*** | Should succinctly and unambiguously communicate the fundamental rule |
   | ***Rationale*** | Should highlight the business benefits of adhering to the principle, using business terminology |
   | ***Implications*** | Should highlight the requirements, both for the business and IT, for carrying out the principle |

#### Stakeholder Management
- Identify Stakeholders
- Classify Stakeholder Positions
- Determine Stakeholder Management Approach
- Tailor Engagement Deliverables 

#### Business Transformation Readiness Assessment (BTRP)
- Determine the readiness factors that will impact the organization
- Present the readiness factors using maturity models
- Assess the readiness factors, including determination of readiness factor ratings
- Assess the risks for each readiness factor and identify improvement actions to mitigate the risk
- Work these actions into Phase E and F Implementation and Migration Plan

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/30_btep_summary.png" width="700"></p>

#### Business Scenerios
- ***Business Scenerios used at Phase A- Vision***
- TOGAF Library contains the specification for Business Scenerios

<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/business-scenerios.png" width="2000"></p>

- A Business Scenario describes: 
   - A business process, application, or set of applications, that can be enabled by the architecture (***Process***)
   - The business and technology environment (***Platform***)
   - The people and computing components (called "actors") who execute the scenario (***People***)
   - The desired outcome of proper execution (***Results***)
- A good Business Scenario is also ***SMART***
   - ***Specific***, by defining what needs to be done in the business
   - ***Measurable***, through clear metrics for success
   - ***Actionable***, by
      - Clearly segmenting the problem, and
      - Providing the basis for determining elements and plans for the solution
    - ***Realistic***, in that the problem can be solved within the bounds of physical reality, time and cost constraints
    - ***Time-bound***, in that there is a clear statement of when the solution opportunity expires

#### Migration Planning
- TOGAF suggests a number of techniques used to support migration planning in Phases E and F

<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/migration-planning.png" width="2000"></p>

#### Key Definitions
- ***Organizational Model*** for EA provides information on the organization, roles, and responsibilities within the enterprise. It includes
   - Scope of organizations impacted
   - Maturity assessment, gaps, and resolution approach
   - Roles and responsibilities for architecture team(s)
   - Constraints on architecture work
   - Budget requirements
   - Governance and support strategy
- An ***Architecture Description*** is a work product used to express an architecture; a collection of architecture views and models that together document the architecture
- ***Stakeholders*** are individuals, teams, organizations, or classes thereof, having an interest in a system
- ***Concerns*** are interests in a system relevant to one or more of its stakeholders. Concerns may pertain to any aspect of the system's functioning, development, or operation, including considerations such as performance, reliability, security, distribution, and evolvability and may determine the acceptability of the system
- An ***Architecture View*** is a representation of a system from the perspective of a related set of concerns. It consists of one or more architecture models of the system.  TOGAF encourages these steps for ***Architecture View*** creation process
   1. Refer to an existing library of architecture viewpoints
   2. Select the appropriate architecture viewpoints (based on the stakeholders and concerns that need to be covered by views)
   3. Generate views of the system by using the selected architecture viewpoints as templates

- An ***Architecture Viewpoint*** is a specification of the conventions for a particular kind of architecture view. It establishes the conventions for constructing, interpreting, and using an architecture view to address a specific concern (or set of concerns) about a system-of-interest. 
   - An ***Architecture View*** is what you see; an ***Architecture Viewpoint*** is where you are looking from that determines what you see
   - ***Architecture Viewpoints*** are generic, and can be stored in libraries for re-use; an ***Architecture View*** is always specific to the architecture
   - Every ***Architecture View*** has an associated ***Architecture Viewpoint*** that describes it, at least implicitly  
   - ***Example***
      - Consider two stakeholders in a new small computing system: the ***Users*** and the ***Developer***
      - The ***Users*** have an ***Architecture Viewpoint*** that reflects their concerns when interacting with the system
      - The ***Developers*** have a different ***Architecture Viewpoint*** that reflects their concerns when interacting with the system
      - The ***User Architecture Viewpoint*** doesn't include any details such as applications or Database Management Systems (DBMS)
      - The ***Developer Architecture Viewpoint*** doesn't include things such as actual live data and connections with consumers
      - The ***Architecture Views*** that are developed to address either of the two ***Architecture Viewpoints*** are unlikely to exhaustively describe the whole system, because each perspective reduces how each sees the system
      - However, there are things that are shared, such as descriptions of the processes that are enabled by the system and/or communications protocols set up for users to communicate problems directly to development
      
## Part 4 - TOGAF Architecture Content Framework (ACF)
- Architects executing the ADM will produce architectural content as a result of their efforts
- Core content metamodel is how to structure your content within the repository, including the extentions

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/34_contentfwk1.png" width="700"></p>

- ACF provides a ***Structural Model for Architectural Content*** that allows major work products to be ***consistently Defined, Structured, and Presented***
- ACF uses the following three categories (***DAB***) to describe the type of architectural work product within the context of use:
  - ***Deliverables (D)***
  - ***Artifacts (A)***
  - ***Building Blocks (B)***

<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/deliverables.png" width="2000"></p>

#### Architecture Definition Document (ADD)
- ADD is a deliverable that documents an Architecture Description
- An example of the relationships between deliverables, artifacts, and building blocks is illustrated

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/02_concepts2.png" width="700"></p>

## Part 5 - Enterprise Continuum
- The Enterprise Continuum is a view of the repository of all the architecture assets. 
- It can contain architecture descriptions, models, building blocks, patterns, viewpoints, and other artifacts 
- It contains the architectures that exist both within the enterprise and in the IT industry at large
- The Enterprise Continuum enables the organization of re-usable architecture artifacts and solution assets to maximize the enterprise architecture investment opportunities

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_entcon_oview.png" width="700"></p>

#### Architecture Continuum
- The Architecture Continuum illustrates how architectures are developed and evolved across a continuum ranging from Foundation Architectures

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_archcon.png" width="700"></p>

#### Solutions Continuum
- The Solutions Continuum is a population of the architecture with reference building blocks
- The Solutions Continuum represents the detailed specification and construction of the architectures at the corresponding levels of the Architecture Continuum

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_solcon.png" width="700"></p>

#### Architecture Repository
- Operating a mature Architecture Capability within a large enterprise creates a huge volume of architectural output 
- Effective management and leverage of these architectural work products require a formal taxonomy
- At a high level, the following classes of architectural information are expected to be held within an Architecture Repository
   -  ***Architecture Metamodel*** describes the organizationally tailored application of an architecture framework
   -  ***Architecture Capability*** defines the parameters, structures, and processes
   -  ***Architecture Landscape*** presents an architectural representation of assets
   -  ***Standards Information*** Base captures the standards with which new architectures must comply
   -  ***Reference Library*** provides guidelines, templates, patterns, and other forms of reference material
   -  ***Governance Log*** provides a record of governance activity across the enterprise
   -  ***Architecture Requirements Repository*** provides a view of all authorized architecture requirements
   -  ***Solutions Landscape*** presents an architectural representation of the Solution Building Blocks (SBBs)  

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf9-doc/arch/Figures/41_archrepos.png" width="700"></p>

## Part 6 - Architecture Capability Framework
- Provides a set of reference materials for how to establish such an architecture function
- The structure of Architecture Capability Framework includes
   - Architecture Board
   - Architecture Compliance
   - Architecture Contracts
   - Architecture Governance
   - Architecture Maturity Models
   - Architecture Skills Framework

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf9-doc/arch/Figures/02_concepts4.png" width="700"></p>

#### Architecture Capability
- It is an evaludation of your ability to define Enterprise Architecture
- In order to successfully operate an architecture function within an enterprise, it is necessary to put in place appropriate organization structures, processes, roles, responsibilities, and skills to realize the Architecture Capability
- Ability to estabilish the **Architecture Contract** is also the part of the Architecture Capability

#### Architecture Governance
- The practice and orientation by which Enterprise Architectures and other architectures are managed and controlled
- Levels of Governance
   - Corporate Governance
   - Technology Governance (how an organization utilizes technology in its services)
   - IT Governance (TOGAF suggests COBIT framework - Control OBjectives for Information and related Technology)
   - Architecture Governance (how architectures are managed and controlled within enterprise)
- Characteristics of Governance (***DTIARF***)
   - Discipline (D), Transparency (T), Independence (I), Accountability (A), Responsibility (R), Fairness (F)

#### Architecture Governance Framework
- An approach, a series of processes, a cultural orientation, and set of owned responsibilities that ensure the integrity and effectiveness of the organization's architectures
 
<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/50_concepts.png" width="700"></p>

- An Architecture Governance structure for will typically include Global governance board, Local governance board, Design authorities and Working parties

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/50_org.png" width="700"></p>

#### Scoping the Architecture 
- Four dimensions (BDAT) are typically used in order to define and limit the scope of an architecture
   - ***Breadth (B)***: what is the full extent of the enterprise?   
   - ***Depth (D)***: to what level of detail should the architecting effort go?
   - ***Architecture Domains (A)***: a complete EA description should contain all four domains (business, data, application, technology)
   - ***Time Period (T)***: what is the time period that needs to be articulated for the Architecture Vision
