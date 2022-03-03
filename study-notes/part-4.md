# TOGAF 101 

## Part 4 - TOGAF Architecture Content Framework (ACF)
- Architects executing the ADM will produce architectural content as a result of their efforts
- ACF provides a ***Structural Model for Architectural Content*** that allows major work products to be ***consistently Defined, Structured, and Presented***
- Core content metamodel is how to structure your content within the repository, including the extentions

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/34_contentfwk1.png" width="700"></p>

- ACF uses the following three categories (***DAB***) to describe the type of architectural work product within the context of use:
  - ***Deliverables (D)***
  - ***Artifacts (A)***
  - ***Building Blocks (B)***

<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/deliverables.png" width="2000"></p>

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
- Business principles, business goals, and business drivers provide context for architecture work, by describing the needs and ways of working employed by the enterprise. Many factors that lie outside the consideration of architecture discipline may nevertheless have significant implications for the way that architecture is developed.

### Architecture Contract
- Architecture Contracts are the joint agreements between ***Development Partners and Sponsors*** on the deliverables, quality, and fitness-for-purpose of an architecture

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
- The ARS provides a ***Quantitative View of the Solution***, stating measurable criteria that must be met during the implementation. ARS Contains
  - Success measures
  - Architecture requirements
  - Business service contracts
  - Application service contracts
  - Implementation guidelines
  - Implementation specifications
  - Implementation standards
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
  - Implementation Factor Assessment and Deduction matrix, including:
    - Risks
    - Issues
    - Assumptions
    - Dependencies
    - Actions
    - Inputs
  - Consolidated Gaps, Solutions, and Dependencies matrix, including:
    - Architecture domain
    - Gap
    - Potential solutions
    - Dependencies
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
 
