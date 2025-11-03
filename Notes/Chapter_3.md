# 3. Agile Testing Methods, Techniques, and Tools

| K-Level | Question Distribution | Learning Objective                                                                                         | Number of Questions |
|---------|------------------------|------------------------------------------------------------------------------------------------------------|----------------------|
| K1      | Keywords               | Recall relevant terms                                                                                      |                     |
| K1      | FA-3.1.1               | Recall test-driven, acceptance test-driven, and behavior-driven development concepts                       | 4                    |
| K1      | FA-3.1.2               | Recall the concept of the test pyramid                                                                     |                     |
| K1      | FA-3.4.1               | Recall different tools available to testers in Agile projects                                              |                     |
| K2      | FA-3.1.3               | Summarize testing quadrants and their relation to levels and types                                         | 2                    |
| K2      | FA-3.3.2               | Explain to business stakeholders how to define testable acceptance criteria                                | 2                    |
| K3      | FA-3.1.4               | Practice the role of a tester in a Scrum team                                                              | 1                    |
| K3      | FA-3.2.1               | Assess quality risks within an Agile project                                                               | 1                    |
| K3      | FA-3.2.2               | Estimate testing effort based on iteration content and quality risks                                       | 1                    |
| K3      | FA-3.3.1               | Interpret relevant information to support testing activities                                               | 1                    |
| K3      | FA-3.3.3               | Write acceptance test-driven development test cases for a given user story                                 | 1                    |
| K3      | FA-3.3.4               | Write black-box test cases for both functional and non-functional behavior based on user stories          | 1                    |
| K3      | FA-3.3.5               | Perform exploratory testing to support Agile project testing                                               | 1                    |

**Total Questions for Chapter 3: 15**   
K1 = 4, K2 = 4, K3 = 7     
Total Points: 15

## FA-3.1.1 (K1) Recall test-driven, acceptance test-driven, and behaviour-driven development concepts

- for each technique
  - the tests are defined before the code is written - tests first approach
  - normally supported by specific tools
- test driven development
  - low-level (unit) testing, but also include integration and system tests
  - automated test cases
    - creates reusable tests for regression testing
  - the tests are used in CI
  - process
    - add a test for the desired functionality for a small piece of code
    - run the test (which falls as no code)
    - write the code and run the test until the test passes
    - refactor (clearing out redundant code, garbage code, tidying up, housekeeping) the code after the test is passed, re-running the test to ensure it continues to pass
    - repeat this progress for the next small piece of code, always running all the previous tests
  - the tests serve as a form of executable design specification for future maintenance efforts
- acceptance test driven development
  - technique used to develop code guided by automated test cases
  - often used in continuous integration
  - helps checking of acceptance criteria
  - process
    - whole team define acceptance tests
    - create automated acceptance tests - testers and or dev
    - code to make tests pass - dev
    - execute automated acceptance tests - testers & dev
- behaviour driven  development
  - use bdd framework (generates code to create test classes)
    - **give** some initial context
    - **when** an event occurs
    - **then** ensure some outcomes
  - developer
    - focuses on testing the code currently being developed
    - focuses on expected behaviour
    - makes tests easier to understand
    - collaborates with other stakeholders to define accurate unit tests focused on business needs

## FA-3.1.2 (K1) Recall the concept of the test pyramid

- concept is based on early QA and testing (eliminate defects early)

    ![](/Resources/test_pyramid.png)

## FA-3.1.3 (K2) Summarise testing quadrants and their relation to levels and types

- the testing quadrant model ensures all important test types and test levels are considered and communicated
- testing quadrant cover dynamic (not static) testing

![](/Resources/testing_quadrant.png)

## FA-3.1.4 (K3) Practice the role of a tester in a Scrum team

- sprint zero
  - identify project scope (product backlog)
  - create an initial system architecture
  - plan, acquire, and instal tools
  - create initial test strategy
  - perform initial quality risk analysis
  - define test metrics (process, progress, product quality)
  - specify the definition of done
  - create the task board
  - define how much testing is enough
- integration
  - ideal = continuous delivery (each sprint)
  - the integration strategy should consider both desig and testing
    - important to identify all dependencies between underlying functions and features
- agile testing practices
  - pairing
  - incremental test design
  - mind mapping
- test planning
  - release and sprint
  - sprint planning
    - tasks on taskboard
      - 1-2 days work
      - testing tasks to keep steady flow of testing
- team attributes
  - cross functional
  - self organising
  - located
  - collaborative
  - empowered
  - commited
  - transparent
  - credible
  - open to feedback
  - resilient

## FA-3.2.1 (K3) Assess quality risks within an Agile project

- quality risk = product risk
  - rather than project/planning risk
  - e.g. incorrect calculation, slow response times,  difficult to understand screens
- ongoing risk analysis
  - additional information may change the risk set and or the level of risk - result in adjustments to the test
    - identifying new risks
    - re-assessing existing risks
    - evaluation the effectiveness of risk mitigation
- release planning
  - high level overview
  - business reps
    - the whole team, including testers may assist in the risk identification and assessment
- iteration planning
  - the whole team identifies and assesses the quality risks
  - risk analysis process
    - gather the agile team members together including tester
    - list all the backlog items for the current iteration (e.g. on a task board)
    - identify the quality risks associated with each item, considering all relevant quality characteristics
    - assess each identified risk, which includes tow activities: categorising the risk and determining its level of risk based on the impact and the likelihood of defects (likelihood x impact)
    - risk mitigation
      - by test design, test implementation , test execution, other e.g. user story reviews
      - determine the extent of testing proportional to the level of risk
        - task prioritisation based on risk
        - high risk - earlier testing task, more test effort
        - low risk - later testing task, less test effort
      - select the appropriate test technique to mitigate each risk, based on the risk, the level of risk and the relevant quality characteristics

    ![image.png](attachment:f2476080-c653-456d-923c-f85715d0102e:image.png)

## FA-3.2.2 (K3) Estimate testing effort based on iteration content and quality risks

- for each story
  - estimation
    - assign story points
      - test effort
        - considering…development and testing effort, complexity of the story and scope of testing (which means risk level is useful
      - development effort
    - usign e.g. planning poker
      - read the story to the estimators
      - estimator discuss the feature
      - estimators choose a card/estimate and reveal their estimates together
        - estimators have planning poker card
        - typically fibonacci like - good as growing gaps relect growing uncertainity
        - maybe XS to XXL
      - if estimates agree - OK
      - if estimates disagree - discuss and repeat until agreement reached

## FA-3.3.1 (K3) Interpret relevant information to support testing activities

- project information
  - tester knowledge and skills
  - available tool support
- test basis
  - important = user story
  - others =
    - experience from previous projects
    - existing functions, features and quality characteristics of the system
    - code, architecture and design
    - user profiles ( context, system, configurations, and user behaviour
    - information on defects from existing products and from previous projects
    - a categorisation of defects in a defect taxonomy
    - applicable standards
    - quality risks
  - other relevant info for testers
    - how the system is supposed to work and be used
    - the system interfaces that can be used/accessed to test the system
    - whether current tool support is sufficient
    - whether the tester has enough knowledge and skill to perform needed tests
- definition of done (iteration and release)
  - iteration
    - all features are ready and individually tested according to the feature level criteria
    - any outstanding non critical defects are added to the product backlog and prioritised
    - integration of all features for the iteration completed and tested
    - documentation written, reviewed and approved
  - release
    - coverage
      - all relevant test basis element for all contents of the release have been covered by testing
    - quality
      - the defect intensity (e.g. how many defects are found per day or per transaction) defect density (e.g. the number defects found compared to the number of user stories, effort and or quality attributes) and estimated number of remaining defects are within acceptable limits
      - the consequences of resolved and remaining defects (e.g. the severity and priority are understood and acceptable
      - the residual level of risk associate with each identified quality risk is understood and acceptable
    - time
      - if the pre-determined delivery date has been reached, the business consideration associated with releasing and not releasing need to be considered.
    - cost
      - the estimated lifecycle return on investment for the delivered system (i.e. the calculated development and maintenance cost should be considerably lower than the expected total sales of the product. The main part of the lifecycle cost often comes from maintenance after the product has been release due to the number of defects escaping to production.
- definition of done (within an iteration)
  - unit testing
    - static analysis - all code
    - all code, unit tests, and unit test results reviewed
    - 100% decision coverage (with reviews of infeasible paths)
    - unresolved major defects (ranked based on prioirity and severity)
    - no unacceptable technical debt (in design and the code)
    - all unit tests automated
  - integration testing
    - 100% functional requirements coverage, including both positive and negative tests
      - number of tests based on size, complexity and risks
    - 100% of interfaces between unit tested
    - all quality risks covered according to the agreed extent of testing
    - all regression tests automated, where possible, and stored in a common repo
    - all defects reported
    - all major defects resolved
  - system testing
    - end-to-end test of features, user stories and functions
    - 100% of user personas covered
    - testing done in production-like environment
      - including all hardware and software for all supported configurations, to the extent possible
    - all quality risks covered according to the agreed extent of testing
    - all regression tests automated, where possible and stored in a common repo
    - all defects reported
    - all major defects resolved
  - user story
    - all elements are specified and reviewed
      - including the user story acceptance tests
    - understood by the team
    - have detailed, testable acceptable criteria
    - tasks identified and estimated
  - feature (may cover a group of user stories or an epic)
    - all user stories and acceptance criteria approved by the customer
    - design is complete with no technical debt
    - code is complete with no remaining technical debt or unfinished refactoring
    - unit tests have been performed and have achieved the defined level of coverage
    - integration and system tests have been performed according to the defined coverage criteria
    - no major defects remain to be corrected
    - documentation complete
      - may include release notes, user manuals and on-line help functions

## FA-3.3.2 (K2) Explain to business stakeholders how to define testable acceptance criteria

- testable acceptance criteria address:
  - functional behaviour
  - quality characteristics (NFR)
  - scenarios (use cases)
  - business rules (user procedures)
  - external interfaces (e.g. user interface, other systems)
  - constraints (design and implementation), e.g. size (memory, volume), weight, interfaces protocols
  - data definitions (format, type, allowed/default values) e.g. postcodes

## FA-3.3.3 (K3) Write acceptance test-driven development test cases for a given user story

- acceptance test driven development (atdd)
  - a technique used to develop code guided by automated test cases
  - creates reusable tests for regression testing
  - high level testing
    - system and acceptance test levels
  - atdd process
    - user story is analysed and clarified including handling of error conditions
      - specification workshop
      - devs, testers and the business reps
    - test creation and independent validation
      - tests = natural language examples of specific characteristics of the user story
        - start with basic examples and open questions
        - positive (correct behaviour)
        - negative path (exception and error conditions)
        - cover NF attributes
        - do NOT add to the story
          - no two examples should describe the same characteristics
        - format
          - preconditions
          - inputs
          - outputs

## FA-3.3.4 (K3) Write black-box test cases for both functional and non-functional behaviour based on user stories

- tests created concurrently with development (except exploratory)
  - based on user stories and AC
- black box techniques
  - equivalence partition (EP) DATA DRIVEN - grouping where behaviour is the same for all in the group - divide and conquer
  - boundary value analysis (BVA) DATA DRIVEN - 1 — 10 (0 -2) ( 9-11) - look around the boundaries
    - also for NF quality characteristics e.g. performance, reliability
  - state transition testing (STT) - move from one mode of operation to another —> start state —> event —> state is now ended
  - decision tables - t/f, y/n, 1/0

## FA-3.3.5 (K3) Perform exploratory testing to support Agile project testing

- rationale for exploratory
  - limited tie available for analysis and limited detail of user storeis
  - explatory is best combined with other experience-based techniques as part of a reactive testing strategy
    - blended with
      - analytical risk based tesitng a requirements based tesitng
      - model based tesing
      - regression averse testing
- tester requirement
  - creativity, intuition, cognition and skill
  - knowledge and understanding of the software under test
    - business domain knowledge
    - how used
    - can determine when the system fails
- approach
  - test design and test execution occur at the same time, guided by a prepated test charter
    - the results of the most recent tests guide the next test
    - the usual white box and black box techniques
  - time based testing sessions
  - exploratory questions
    - what is most important to find out about the system
    - in what way may the system fail
    - what happens if
    - what should happen when
    - are customer needs, requirements and expectations fulfilled
  - exploratory heuristics
    - boundaries
    - CRUD (create, read, update, delete)
    - configuration variations
    - interruptions (e.g. log off, shut down, reboot)
- session based test management
  - session
    - 60-120 mins
    - session types
      - survey session
        - to learn how it works
      - analysis session
        - functionality
        - characteristics
      - deep coverage session
        - corner cases
        - scenarios
        - interactions
      - documentation
        - test coverage
        - evaluation notes (observations)
        - risk coverage
        - strategy  followed (changes needed)
        - issues, questions and anomalies
        - actual behaviour (video, screen captures, output data files)
        - captured/summarised - using status management tools
- test charter
  - actor
  - purpose
  - setup
  - prioirty
  - reference
  - data
  - activities
  - oracle notes - where do we get the information from
  - variations
-

## FA-3.4.1 (K1) Recall different tools available to testers in Agile projects

- software build and distribution tools
  - agile teams rely on daily builds and frequent deployments, which require continuous integration and build distribution tools. These tools help:
    - build the application frequently
    - detect integration issues early
    - automate deployment into test environments
- task management and tracking tools
  - record stories and tasks
  - capture/calculate task/story estimates for iteration planning
  - link tasks with stories
  - aggregate task status to provide story status
  - visually show story status
    - metrics, charts, and dashboards
    - task boards
    - burndown charts
  - integrate with configuration management tools
- communication and information sharing tools
  - wikis
    - product documentation
      - feature diagrams, feature discussions, prototype diagrams, photos of whiteboard discussions
    - product status
      - metric, charts, and dashboards
      - ideally integrated with other tools such as the build server and task management system
      - development and testing tools/techniques
      - shared team conversations
    - IM, audio teleconferencing and video chart
      - real time communication between team members
      - involve distributed team in stand up meetings
      - reduce communication costs for distributed teams
        - VOIP to reduce phone bills
    - desktop sharing
      - product demos, code reviews and pairing
    - desktop capture
      - product demos for wiki
  - cloud computing and visualisation tools
    - visualisation allows a single physical resource to operate as many separate, smaller resources
    - virtual machines or cloud instances provide a greater number of servers for development and testing
      - can help avoid delays association waiting for physical servers
    - provisioning a new server or restoring a server is more efficient with snapshot capabilities build into most virtualisation tools
    - some test management tools use virtualisation technologies to snapshot servers when a fault is detected
      - snapshot can be shared with deverlopers
    - configuration management tools
      - allows for rapid change without losing historical information
      - store (with traceability)
        - source code
        - automated tests
        - manual tests
        - other test work products
      - types
        - centralised source control systems
        - distributed version control systems
        - choice depends on
        - team size, structure, location and requirements to integrate with other tools
    - test design, implementation and execution tools
      - test design tools
        - mind maps for test design and specification
      - test case management tools
        - may be part of the agile teams application lifecycle management or task management tool
      - test data prep and generation tools
        - generate data to populate an applications db (good when a lot of data and combinations of data)
        - can help re define the db structure as the product undergoes changes during an agile project and refactor the scripts to generate the data
          - allows quick updating of test data as changes occur
        - some use production data sources as a raw material and use scripts to remove or anonymise sensitive data
        - some help with validating large data inputs or outputs
        - many of the data generator tools include an integrated data load component
      - test data load tools
        - load data into application
          - as manual data entry is often time consuming and error prone
        - in some cases, bulk loading using database management systems is possible
      - automated test execution tools
        - tools support test first approaches
        - such as behaviour-driven development, test-driven development and acceptance test-driven development
        - allow testers and business staff to express the expected system behaviour in tables or natural language using keywords
      - exploratory test tools
        - tools can capture and log activvities performed on an application during an exploratory test session
          - useful when a defect is found for defect reporting
          - useful if the test test is later included in the automated regression test suite
