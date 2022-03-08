# TOGAF 101 

## Part 4 - TOGAF Architecture Content Framework (ACF)
- Architects executing the ADM will produce architectural content as a result of their efforts
- Provides a ***Structural Model for Architectural Content*** that allows major work products to be ***consistently Defined, Structured, and Presented***
- Core content metamodel is how to structure your content within the repository, including the extentions

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/34_contentfwk1.png" width="700"></p>

- ACF uses the following three categories (***DAB***) to describe the type of architectural work product within the context of use:
  - ***Deliverables (D)***
  - ***Artifacts (A)***
  - ***Building Blocks (B)***

<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/deliverables.png" width="2000"></p>

## Architectural Artifacts

### ***Architecture Description*** 
- A work product used to express an architecture; a collection of architecture views and models that together document the architecture

### ***Stakeholders*** 
- Individuals, teams, organizations, or classes thereof, having an interest in a system

### ***Concerns*** 
- Interests in a system relevant to ***one or more*** stakeholders. 
- Concerns may pertain to any aspect of the system's functioning, development, or operation, including considerations such as performance, reliability, security, distribution, and evolvability and may determine the acceptability of the system

### ***Architecture View*** 
- A representation of a system from the perspective of a related set of concerns. It consists of one or more architecture models of the system  
- Architecture views are representations of the overall architecture meaningful to stakeholders
- Architecture views enable the architecture to be ***Communicated*** to and ***Understood*** by the stakeholders, and ***Verify*** that the system will address their concerns 
- TOGAF encourages these steps for ***Architecture View*** creation process
  - ***Refer to an existing library*** of architecture viewpoints
  - ***Select the appropriate architecture viewpoints*** (based on the stakeholders and concerns that need to be covered by views)
  - ***Generate views*** of the system by using the selected architecture viewpoints as templates

### ***Architecture Viewpoint*** 
- A specification for a particular kind of architecture view
- More specifically, a viewpoint defines: how to construct and use a view (by means of an appropriate schema or template)

### Relationship Between ***Architecture View*** and ***Architecture Viewpoint*** 
- An ***Architecture View*** is what you see; an ***Architecture Viewpoint*** is where you are looking from that determines what you see
- ***Architecture Viewpoints*** are ***Generic***, and can be stored in libraries for re-use; an ***Architecture View*** is always ***Specific*** to the architecture
- Every ***Architecture View*** has an associated ***Architecture Viewpoint*** that describes it, at least implicitly  
- ***Example***
  - Consider two stakeholders in a new small computing system: the ***Users*** and the ***Developer***
  - The ***Users Architecture Viewpoint*** reflects their concerns when interacting with the system
    - The ***User Architecture Viewpoint*** doesn't include any technical details such as applications or Database Management Systems (DBMS) 
  - The ***Developers Architecture Viewpoint*** reflects their concerns when interacting with the system
    - The ***Developer Architecture Viewpoint*** doesn't include things such as actual live data and customer interaction
  - However, there are things that are shared, such as communications protocols etc. between both the viewpoints

### Interactions between Metamodel, Building Blocks, Diagrams, and Stakeholders
- The TOGAF content framework defines a set of architecture diagrams to address stakeholder concerns
<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/34_contentfwk3.png" width="700"></p>

## Deliverable Descriptions

### Architecture Vision
- The Architecture Vision provides a summary of the changes to the enterprise that will accrue from successful deployment of the Target Architecture. It contains
  - Problem description:
    - Stakeholders and their concerns
    - List of issues/scenarios to be addressed
  - Objective of the Statement of Architecture Work
  - Summary views necessary for the Request for Architecture Work and the Version 0.1 Business, Application, Data, and Technology Architectures created; typically including:
    - Value Chain diagram
    - Solution Concept diagram
  - Mapped requirements
  - Reference to Draft Architecture Definition Document

### Business Principles, Business Goals, and Business Drivers
- Business principles, business goals, and business drivers provide ***Context for Architecture Work***, by describing the ways of working employed by the enterprise 

### Architecture Contract
- Architecture Contracts are the joint agreements between ***Development Partners and Sponsors (DPS)*** on the deliverables, quality, and fitness-for-purpose of an architecture

### Architecture Definition Document (ADD)
- The ADD provides a ***Qualitative View of the Solution*** and aims to communicate the intent of the architects. ADD contains
  - Scope
  - Goals, objectives, and constraints
  - Architecture Principles
  - Baseline Architecture
  - Architecture models (for each state to be modeled):
    - Business/Data/Application/Technology Architecture models
  - Rationale and justification for architectural approach
  - Mapping to Architecture Repository:
    - Mapping to Architecture Landscape
    - Mapping to reference models
    - Mapping to standards
    - Re-use assessment
  - Gap analysis
  - Impact assessment
  - Transition Architecture:
    - Definition of transition states
    - Business/Data/Application/Technology Architecture for each transition state
- An example of the relationships between deliverables, artifacts, and building blocks is illustrated

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/02_concepts2.png" width="700"></p>

### Architecture Requirements Specification (ARS)
- The ARS provides a ***Quantitative View of the Solution***, stating measurable criteria for implementation. ARS Contains
  - Success measures
  - Architecture requirements
  - Business service contracts and Application service contracts
  - Implementation guidelines, specifications and standards
  - Interoperability requirements
  - IT Service Management requirements
  - Constraints
  - Assumptions

###  Architecture Roadmap
- The Architecture Roadmap lists individual work packages that will realize the Target Architecture and lays them out on a timeline to show progression from the Baseline Architecture to the Target Architecture
- Typical contents of an Architecture Roadmap are:
  - Work package portfolio:
    - Work package description (name, description, objectives, deliverables)
    - Functional requirements
    - Dependencies
    - Relationship to opportunity
    - Relationship to Architecture Definition Document and Architecture Requirements Specification
    - Business value
  - ***Implementation Factor Assessment and Deduction matrix*** (IFADM), including (Risks, Issues, Assumptions, Dependencies, Actions, Inputs)
  - ***Consolidated Gaps, Solutions, and Dependencies matrix*** (COGASODE), including (Architecture domain, Gap, Potential solutions,  Dependencies)
  - Any Transition Architectures
  - Implementation recommendations:
    - Criteria measures of effectiveness of projects
    - Risks and issues
    - Solution Building Blocks (SBBs)

### Capability Assessment
- Before embarking upon a detailed Architecture Definition, it is valuable to understand the baseline and target capability level of the enterprise.
  - ***Business Capability Assessment***- What is the capability level of the enterprise as a whole
  - ***IT Capability Assessment***- What is the capability or maturity level of the IT function within the enterprise
  - ***Architecture Maturity Assessment***- What is the capability and maturity of the architecture function within the enterprise
  - ***Business Transformation Readiness Assessment***- Where capability gaps exist, to what extent is the business ready to transform in order to reach the target capability
 
### Compliance Assessment
- It is necessary to govern that architecture during implementation to ensure that the original Architecture Vision is appropriately realized
- Periodic compliance reviews of implementation projects provide a mechanism to review project progress and ensure that the design and implementation is in line with the strategic and architectural objectives. It includes
  - Overview of project progress and status
  - Overview of project architecture/design
  - Completed architecture checklists:
    - Hardware and operating system checklist
    - Software services and middleware checklist
    - Applications checklists
    - Information management checklists
    - Security checklists
    - System management checklists
    - System engineering checklists
    - Methods and tools checklists

### Implementation and Migration Plan
- The Implementation and Migration Plan provides a schedule of the projects that will realize the Target Architecture. It includes
  - Implementation and Migration Strategy:
    - Strategic implementation direction
    - Implementation sequencing approach
  - Project and portfolio breakdown of implementation:
    - Allocation of work packages to project and portfolio
    - Capabilities delivered by projects
    - Milestones and timing
    - Work breakdown structure
    - May include impact on existing portfolio, program, and projects
  - Project charters (optional) 

### Implementation Governance Model
- Once an architecture has been defined, it is necessary to plan how the Transition Architecture that implements the architecture will be governed through implementation
- Implementation Governance Model includes
  - Governance processes
  - Governance organization structure
  - Governance roles and responsibilities
  - Governance checkpoints and success/failure criteria

### Organizational Model
- ***Organizational Model*** for EA provides information on the organization, roles, and responsibilities within the enterprise. It includes
   - Scope of organizations impacted
   - Maturity assessment, gaps, and resolution approach
   - Roles and responsibilities for architecture team(s)
   - Constraints on architecture work
   - Budget requirements
   - Governance and support strategy

## [Part 1 - Introduction ](part-1.md)
## [Part 2 - ADM ](part-2.md)
## [Part 3 - ADM Guidelines and Techniques ](part-3.md)
## [Part 5 - Enterprise Continuum ](part-5.md)
## [Part 6 - Architecture Capability Framework ](part-6.md)

### Disclaimer [The Open Group](https://pubs.opengroup.org/architecture/togaf92-doc/arch) owns the information rights.
