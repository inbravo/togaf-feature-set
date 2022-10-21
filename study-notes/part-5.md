# TOGAF 101 

## Part 5 - Enterprise Continuum
- The Enterprise Continuum is a view of the repository of all the architecture assets. 
- It can contain architecture descriptions, models, building blocks, patterns, viewpoints, and other artifacts 
- It contains the architectures that exist both within the enterprise and in the IT industry at large
- The Enterprise Continuum enables the organization of re-usable architecture artifacts and solution assets to maximize the enterprise architecture investment opportunities

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_entcon_oview.png" width="700"></p>

#### Architecture Continuum
- The Architecture Continuum illustrates how architectures are developed and evolved across a continuum ranging from Foundation Architectures
- The leftwards direction focuses on meeting enterprise needs and business requirements 
- The rightwards direction focuses on leveraging architectural components and building blocks

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_archcon.png" width="700"></p>

#### Solutions Continuum
- The relationship between the Architecture Continuum and the Solutions Continuum is one of ***guidance, direction, and support***
- The Solutions Continuum is a population of the architecture with reference building blocks
- The Solutions Continuum represents the detailed specification and construction of the architectures at the corresponding levels of the Architecture Continuum

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/39_solcon.png" width="700"></p>

#### Foundation Architecture
- Consists of ***generic components, inter-relationships, principles, and guidelines*** that provide a foundation on which more specific architectures can be built
- The TOGAF TRM is an example of a Foundation Architecture. It is a fundamental architecture upon which other, more specific architectures can be based

#### Common Systems Architectures
- Reflects requirements specific to a ***Generic problem domain***
- Defines building blocks specific to a ***Generic problem domain***
- Defines business, data, application, or technology standards for implementing these building blocks
- Provides building blocks for easy re-use and lower costs

#### Industry Architectures
- Reflects requirements and standards specific to a ***Vertical industry***
- Defines building blocks specific to a ***Generic problem domain***
- Contains ***Industry-specific*** logical data and process models
- Contains ***Industry-specific*** applications and process models, as well as industry-specific business rules

#### Organization-Specific Architectures
- Provides a means to communicate and manage business operations across all four architectural domains
- Reflects requirements specific to a ***Particular enterprise***
- Defines building blocks specific to a ***Particular enterprise***
- Contains ***Organization-specific*** business models, data, applications, and technologies
- Provides the criteria to measure and select appropriate products, solutions, and services
- Provides an evolutionary path to support growth and new business needs

#### Architecture Partitioning
- It is valuable to partition and organize the Enterprise Continuum into a set of related solutions and architectures with:
   - Manageable complexity for each individual architecture or solution
   - Defined groupings
   - Defined hierarchies and navigation structures
   - Appropriate processes, roles, and responsibilities attached to each grouping

##### Architecture Partitioning Activities in Preliminary Phase
- There are 4 dimensions in which Architecture Acivity Scope is limited (***BDAT- Breadth, Depth, Architecture Domains, Time Period***)
- Determine the organization structure for architecture within the enterprise
- Determine the responsibilities for each standing architecture team
- Determine the relationships between architectures

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/40_partitioning5.png" width="700"></p>

#### Architecture Repository
- Operating a mature Architecture Capability within a large enterprise creates a huge volume of architectural output 
- Effective management and leverage of these architectural work products require a formal taxonomy
- At a high level, the following classes of architectural information are expected to be held within an Architecture Repository
   -  ***Architecture Metamodel*** describes the organizationally tailored application of an architecture framework
   -  ***Architecture Capability*** defines the parameters, structures, and processes
   -  ***Architecture Landscape*** presents an architectural representation of assets
   -  ***Standards Information Base*** provides a repository area to hold a set of specifications, to which architectures must conform
      -  Types: ***Legal and Regulatory Obligations***, ***Industry Standards*** and ***Organizational Standards***
   -  ***Reference Library*** provides guidelines, templates, patterns, and other forms of reference material
   -  ***Governance Log*** provides a record of governance activity across the enterprise
      -  ***Decision Log*** (architecturally significant decisions that have been made in the organization)
      -  ***Compliance Assessments*** (logs of periodically measured compliance of the project)    
      -  ***Capability Assessments*** (logs of periodically carried out assesments to ensure that appropriate progress is being made)
      -  ***Calendar*** (schedule of in-flight projects and formal review sessions to be held against these projects)
      -  ***Project Portfolio*** (description, Architectural scope, architectural roles and responsibilities associated with the project)
   -  ***Architecture Requirements Repository*** provides a view of all authorized architecture requirements
   -  ***Solutions Landscape*** presents an architectural representation of the Solution Building Blocks (SBBs)  

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf9-doc/arch/Figures/41_archrepos.png" width="700"></p>

#### Technical Reference Model (TRM)
- The Foundation Architecture is embodied within the Technical Reference Model (TRM)
- TRM provides a model and taxonomy of generic platform services. It includes
   - A ***Taxonomy***, which defines terminology, and provides a coherent description of the components and conceptual structure of an information system
   - An associated ***TRM Graphic***, which provides a visual representation of the taxonomy, as an aid to understanding
- The high-level TRM seeks to emphasize two major common architectural objectives:
   - ***Application Portability*** via the Application Platform Interface
   - ***Interoperability*** via the Communications Infrastructure Interface

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf91-doc/arch/Figures/43_trm_detail.png" width="400"></p>

#### Integrated Information Infrastructure Reference Model (III-RM)
- Fundamentally it is an Application Architecture Reference Model. This model is a subset of the TOGAF TRM
- Model for developing, managing, and operating an integrated information infrastructure

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf91-doc/arch/Figures/44_iiirm5.png" width="700"></p>

#### Industry specific models
- TM Forum for Telecommunications
- Association of Retail Technology Standards (ARTS) for Retail
- Energistics for Petrotechnical
- Resources, Events, Agents (REA) for accounting system

## [Part 1 - Introduction ](part-1.md)
## [Part 2 - ADM ](part-2.md)
## [Part 3 - ADM Guidelines and Techniques ](part-3.md)
## [Part 4 - Architecture Content Framework ](part-4.md)
## [Part 6 - Architecture Capability Framework ](part-6.md)

### Disclaimer [The Open Group](https://pubs.opengroup.org/architecture/togaf92-doc/arch) owns the information rights.
