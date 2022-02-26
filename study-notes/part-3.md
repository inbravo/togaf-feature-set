# TOGAF 101 

## Part 3 - ADM Guidelines and Techniquies

   |    Technique  | Applicable Phase  | Description |
   | ----------- | -----------  | -----------  |
   | [Applying Iteration to the ADM](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap19.html) | ***All*** | ***Baseline First*** or ***Target First*** Architecture Definition |
   | [Architecture Principles](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap20.html) | ***Preliminary & Phase A*** | Principle Qualities: ***URCCS- Understandable (U), Robust (R), Complete (C), Consistent (C), Stable (S)*** |
   | [Stakeholder Management](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap21.html) | ***Phase A*** | It is important to pay particular attention to stakeholder interests by defining specific ***catalogs, matrices, and diagrams that are relevant*** for a particular Enterprise Architecture model. This enables the architecture to be communicated to, and understood by, all the stakeholders |
   | [Architecture Patterns](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap22.html) |  ***Phase A-B-C-D*** | ***Architecture*** Pattern, ***Design*** Pattern or  ***Idiom*** (programming language specific pattern)  |
   | [Gap Analysis](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap23.html) | ***Phase E*** | Highlight a shortfall between the Baseline Architecture and the Target Architecture; items that have been ***Deliberately Omitted, Accidentally Left Out, or Not Yet Defined***  |
   | [Migration Planning](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap24.html) |  ***Phase E & F*** | There are 5 techniques: ***Implementation Factor Assessment & Deduction Matrix***, ***Consolidated Gaps, Solutions, & Dependencies Matrix***, ***Architecture Definition Increments Table***, ***Transition Architecture State Evolution Table***, ***Business Value Assessment Technique*** |
   | [Business Transformation Readiness Assessment (BRTP)](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap25.html) | ***Phases B-C-D***  |Used in  ***Capability Assessment***   |
   | [Risk Management](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap26.html) |  ***All*** | ***Initial Risk*** (prior to mitigating actions) and ***Residual Risk*** (after mitigating actions) |
   | [Capability-Based Planning](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap27.html) |  ***All*** | Often the need for these capabilities are discovered and refined using business scenarios |

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
