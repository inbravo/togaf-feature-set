# TOGAF 101 

## Part 3 - ADM Guidelines and Techniquies

   |    Technique  | Applicable Phase  | Description |
   | ----------- | -----------  | -----------  |
   | [Applying Iteration to the ADM](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap19.html) | ***ALL*** | ***Baseline First*** or ***Target First*** Architecture Definition |
   | [Architecture Principles](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap20.html) | ***Preliminary & Phase A*** | Principle Qualities: ***URCCS- Understandable (U), Robust (R), Complete (C), Consistent (C), Stable (S)*** |
   | [Stakeholder Management](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap21.html) | ***Phase A*** | It is important to pay particular attention to stakeholder interests by defining specific ***catalogs, matrices, and diagrams that are relevant*** for a particular Enterprise Architecture model. This enables the architecture to be communicated to, and understood by, all the stakeholders |
   | [Architecture Patterns](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap22.html) |  ***Phase A-B-C-D*** | ***Architecture*** Pattern, ***Design*** Pattern or  ***Idiom*** (programming language specific pattern)  |
   | [Gap Analysis](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap23.html) | ***Phase E*** | Highlight a shortfall between the Baseline Architecture and the Target Architecture; items that have been ***Deliberately Omitted, Accidentally Left Out, or Not Yet Defined***  |
   | [Migration Planning](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap24.html) |  ***Phase E & F*** | There are 5 techniques: ***Implementation Factor Assessment & Deduction Matrix***, ***Consolidated Gaps, Solutions, & Dependencies Matrix***, ***Architecture Definition Increments Table***, ***Transition Architecture State Evolution Table***, ***Business Value Assessment Technique*** |
   | [Interoperability Requirements](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap25.html) | ***ALL***  | Defining the degree to which the information and services are to be shared  |
   | [Business Transformation Readiness Assessment (BRTP)](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap26.html) | ***Phases B-C-D***  |Used in  ***Capability Assessment***   |
   | [Risk Management](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap26.html) |  ***ALL*** | ***Initial Risk*** (prior to mitigating actions) and ***Residual Risk*** (after mitigating actions) |
   | [Capability-Based Planning](https://pubs.opengroup.org/architecture/togaf92-doc/arch/chap27.html) |  ***ALL*** | It is business-driven and business-led and combines the requisite efforts of all lines of business to achieve the desired capability |

#### Architecture Development Approaches
- ***Baseline First or Bottom-Up Approach*** 
  - This process is most suitable when the baseline is complex, not clearly understood, or agreed upon
  - This approach is common where organizational units have had a high degree of autonomy
- ***Target First or Top-Down Approach*** 
  - This process is suitable when a target state is agreed at a high level and where the enterprise wishes to effectively transition to the target model. 
  - Typically, if the baseline is broadly understood a higher value will be obtained focusing on the target first then baseline to the extent necessary to identify changes
 
#### Risk Management
- There are two levels of risk-
   - ***Initial Level of Risk***: risk categorization prior to determining and implementing mitigating actions
   - ***Residual Level of Risk***: risk categorization after implementation of mitigating actions (if any)
- The process for risk management is -
   - Risk classification
   - Risk identification
   - Initial risk assessment
   - Risk mitigation and residual risk assessment
   - Risk monitoring

#### Principles
- Principles are general rules and guidelines, intended to be ***enduring and seldom amended***
- Recommended template for Principles
   
   |      |      |  
   | ----------- | ----------- | 
   | ***Name*** | Should both represent the essence of the rule as well as be easy to remember |
   | ***Statement*** | Should succinctly and unambiguously communicate the fundamental rule |
   | ***Rationale*** | Should highlight the business benefits of adhering to the principle, using business terminology |
   | ***Implications*** | Should highlight the requirements, both for the business and IT, for carrying out the principle |

#### Interoperability Requirements
- Architecture Vision (Phase A), the nature and security considerations of the information and service exchanges are first ***Revealed within the business scenarios***
- Business Architecture (Phase B), the information and service exchanges are further ***Defined in business terms***
- Data Architecture (Phase C), the Content of the information exchanges is ***Detailed using the corporate data and/or information exchange model***
- Application Architecture (Phase C), ***the way that the various applications are to share the information and services is specified***
- Technology Architecture (Phase D), the appropriate ***Technical mechanisms to permit the information and service exchanges are specified***
- Opportunities & Solutions (Phase E), the ***Actual solutions (e.g., Commercial Off-The-Shelf (COTS) packages) are selected***
- Migration Planning (Phase F), the ***Interoperability is logically implemented***

#### Business Transformation Readiness Assessment (BTRP)
- ***Determine*** the Readiness Factors that will impact the organization
- ***Present*** the Readiness Factors using maturity models
- ***Assess*** the Readiness Factors, including determination of readiness factor ratings
- ***Assess the Risks*** for each readiness factor and ***Identify Improvement Actions*** to mitigate the risk
- Work these actions into ***Phase E-F*** Implementation and Migration Plan

<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/30_btep_summary.png" width="700"></p>

#### Business Scenerios
- ***Business Scenerios*** used at Phase A-B
- A key factor in the success of an enterprise architecture is the extent to which it is linked to business requirements
- **Business Scenerio is a technique for discovering the need for a capability**
- A Business Scenario describes: 
   - A business process, application, or set of applications, that can be enabled by the architecture (***Process***)
   - The business and technology environment (***Platform***)
   - The people and computing components (called "actors") who execute the scenario (***People***)
   - The desired outcome of proper execution (***Results***)
- A good Business Scenario is also ***SMART*** - ***SpeMea Act Real Time***
   - ***Specific***, by defining what needs to be done in the business
   - ***Measurable***, through clear metrics for success
   - ***Actionable***, by
      - Clearly segmenting the problem, and
      - Providing the basis for determining elements and plans for the solution
    - ***Realistic***, in that the problem can be solved within the bounds of physical reality, time and cost constraints
    - ***Time-bound***, in that there is a clear statement of when the solution opportunity expires
- Creating a business scenario involves the following steps
<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf91-doc/arch/Figures/26_busscen1.png" width="500"></p>

#### Migration Planning
- TOGAF suggests a number of techniques used to support migration planning in Phases E and F

<p align="center"><img src="https://github.com/inbravo/togaf-feature-set/blob/main/references/images/migration-planning.png" width="2000"></p>

#### Capability Based Planning
- The capabilities are directly derived from the corporate strategic plan and/or include the Enterprise Architects and satisfy the enterprise goals, objectives, and strategies
<p align="center"><img src="https://pubs.opengroup.org/architecture/togaf92-doc/arch/Figures/32_relationships.png" width="900"></p>

## [Part 1 - Introduction ](part-1.md)
## [Part 2 - ADM ](part-2.md)
## [Part 4 - Architecture Content Framework ](part-4.md)
## [Part 5 - Enterprise Continuum ](part-5.md)
## [Part 6 - Architecture Capability Framework ](part-6.md)

### Disclaimer [The Open Group](https://pubs.opengroup.org/architecture/togaf92-doc/arch) owns the information rights reffered here.
