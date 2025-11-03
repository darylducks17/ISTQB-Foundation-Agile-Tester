# Chapter 1: Agile Software Development

| K-Level | Question Distribution | Learning Objective                                                                                         | Number of Questions |
|---------|------------------------|------------------------------------------------------------------------------------------------------------|----------------------|
| K1      | FA-1.1.1               | Recall the basic concept of Agile software development based on the Agile Manifesto                        |                     |
| K1      | FA-1.2.1               | Recall Agile software development approaches                                                               | 5                    |
| K1      | FA-1.2.5               | Know the differences between iteration and release planning, and how a tester adds value                   |                    |
| K2      | FA-1.1.2               | Understand the advantages of the whole-team approach                                                       | 2                    |
| K2      | FA-1.1.3               | Understand the benefits of early and frequent feedback                                                      | 2                    |
| K2      | FA-1.2.3               | Understand how retrospectives can be used as a mechanism for process improvement in Agile projects         | 2                    |
| K2      | FA-1.2.4               | Understand the use and purpose of continuous integration                                                    | 1                    |
| K3      | FA-1.2.2               | Write testable user stories in collaboration with developers and business representatives                  | 1                    |

**Total Questions for Chapter 1: 13**  
K1 = 5, K2 = 7, K3 = 1  
Total Points: 13

## FA-1.1.1 (K1) Recall the basic concept of Agile software development based on the Agile Manifesto

### Agile Manifesto

1. individuals and Interactions over processes and tools
    1. emphasises communication and collaboration over reliance on tools
2. working software over comprehensive documentation
    1. priorities delivering usable functionality early, allowing quick feedback and faster time to market
3. customer collaboration over contract negotiation
    1. close, continuous interaction with customers improves requirement clarity and project outcomes
4. responding to change over following a plan
    1. agile embraces change rather than resisting it, allowing adaptation to external factors like business shifts or technological advances

### Agile Principle

1. deliver valuable software early and continuously
2. welcome changing requirements, even late in development
3. deliver working software frequently (weeks to months)
4. business reps and developers must work together daily
5. build projects around motivated individuals with proper support
6. face to face communication is the primary measure of progress
7. working software is the primary measure of progress.
8. promote sustainable development at a constant pace
9. maintain technical excellence and good design
10. simplicity is essential - maximise work not done
11. self-organising teams produce the best architectures, requirements and designs
12. teams regularly reflect and improve their effectiveness

## FA-1.1.2 (K2) Understand the advantages of the whole-team approach

- whole team approach involves everyone with the knowledge and skills necessary for project success
- includes testers, developers, and business stakeholders
- ideally small (3-9 people)
- co-located to improve communication
- daily stand-ups help identify progress and impediments
- benefits of a whole team approach:
  - enhances collaboration and communication
  - leverages diverse skill sets across the team to benefit the project
  - assigns responsibility for quality to the entire team
- testers actively participate in all stages:
  - supporting business stakeholders in defining acceptance tests
  - collaborating with devs on testing strategy
  - contributing to the decision on test automation
- power of 3
  - business rep, dev and testers
  - involved in feature discussion, estimation and decision to ensure quality level is a shared responsibility

## FA-1.1.3 (K2) Understand the benefits of early and frequent feedback

- benefits of early and frequent feedback
  - helps avoid  misunderstandings in requirements by identifying issues earlier
  - allows early clarification and delivery of requested features to the customer
  - enables early detection and resolution of quality issues through CI
  - provides transparency into team performance and delivery capacity
  - supports better planning and adjustments to improve team velocity
  - maintains consistent momentum throughout the project
- frequent feedback ensures that high-value and high-risk features are prioritised and delivered first, improving customer satisfaction  and reducing rework

## FA-1.2.1 (K1) Recall Agile software development approaches

- XP - Extreme Programming
  - XP influenced many other agile frameworks e.g. scrum
  - software development approach (programmer centric)
  - 5 values
    - communication, simplicity, feedback, courage, respect
  - 14 principles
    - humanity, economics, mutual benefit, self-similarity, improvement, diversity, reflection, flow, opportunity, redundancy, failure, quality, baby steps and accepted responsibility
  - 13 practices
    - sit together, whole team, informative workspace, energised work, pair programming, stories, weekly cycle, quarterly cycle, slack, ten-minute build, continuous integration, test first programming, incremental design
- Scrum
  - Scrum is an agile management framework and does not prescribe specific testing techniques or software engineering practices.
  - 7 principles & instruments
    - sprints - fixed length iterations (2-4 weeks)
    - product increment - deliverable product at the end of each sprint
    - product backlog/todo list/set of requirements for the whole system - prioritised list of feature maintained by the product owner
    - sprint backlog - selected items for the current sprint, based on pull principle
    - definition of done - shared understanding when work is considered complete
    - timeboxing - fixed time limits to tasks for sprints and meetings
    - transparency - daily scrums and visible product status to the team
  - 3 roles
    - scrum master - facilitator and guardian of scrum practices
    - product owner - voice of the customer, manages and prioritised the product backlog
    - dev team - self organising, cross-functional team that build and tests the product
- Kanban
  - Kanban is a visual workflow management method that emphasises flow and continuous delivery without mandatory sprints
  - 3 mechanisms
    - kanban board - visual workflow board with columns showing staging like development and testing where tasks move across as tickets
    - work in progress limits - each stage has maximum task limits. new work starts onnly when capacity allows.
    - lead time - measure and optimises the time to complete tasks through the workflow.
  - Kanban and scrum both use visual task tracking for transparency, with tasks moving from backlog to board when capacity allows. kanban differs by making iterations optional and allowing single-item releases, while scrum requires synchronised sprints

## FA-1.2.2 (K3) Write testable user stories in collaboration with developers and business representatives

- in agile, requirements are captured as user stories - these are created collaboratively by devs, testers and business reps - shared vision is accomplished through frequent informal reviews while the requirements are being written
- key concepts
  - user stories cover both functional and non-functional aspects
  - the AC should be defined in collaboration between business rep, devs and testers
  - the team considers a task finished when a set of AC has been satisfied
  - testers contribute by identifying gaps in the user story (missing details or NFR) by asking business reps open ended questions and confirming testability of the AC
  - documentation should be concise, sufficient and necessary
- 3C concept
  - Card - physical media describing a user story
    - accurate description - “As a [user], I want to [goal/do something], so that I [value/some reason]
    - describes the story identifying the requirements, criticality, expected development/test duration and the acceptance criteria.
  - Conversation - on how the software will be used
    - documented or verbal, between tester, developers & business reps
    - testers bring valuable input to the exchange of thoughts, opinions and experiences
    - begins during release planning and continues when the story is scheduled
  - Confirmation - validates completion thorough AC
    - AC confirm that the story is done
      - include performance, security, interoperability etc.
    - acceptance criteria may span multiple user stories
    - both positive and negative tests should be used
    - performed by various participants
- Techniques
  - **Brainstorming and mind mapping** help in collaborative authorship story creation.
  - **INVEST** criteria define quality user stories:
    - Independent
    - Negotiable
    - Valuable
    - Estimable
    - Small
    - Testable

## FA-1.2.3 (K2) Understand how retrospectives can be used as a mechanism for process improvement in Agile projects

- in agile, retrospective is a meeting held at the end of each iteration to discuss what worked, what didn’t and what to improve
- purpose and scope
  - topics include team dynamics, tools, processes and relationships
  - aim to support continual improvement in a trusted envrionment
- tester involvement
  - it can result in test-related improvement decisions focused on test effectiveness. test productivity test case quality and team satisfaction
  - testers are part of the team and bring their unique perspective.
  - all team members, testers and non-testers, can provide input on both testing and non-testing activities.

## FA-1.2.4 (K2) Understand the use and purpose of continuous integration

- in agile, CI is used to ensure software is always in a working, testable state
- all changes are merged and integrated frequently at least once a day
- agile testers can focus manual testing on new features and defect fixes while relying on automated regression tests for previously delivered functionality
- automation allows early detection of integration errors, provides fast feedback on code quality, and supports test execution throughout the sprint
- automated activities include
  - static code analysis - running analysis tools
  - compile - creating executable files
  - unit test - running tests and measuring coverage
  - deploy - installing in test env
  - integration test - running integration tests
  - report - publishing status to dashboard/email
- benefits of CI
  - faster detection and root cause analysis of integration issues
  - regular feedback to the team on software stability
  - keeps the version between development and testing within a day
  - reducing risk from refactoring through rapid re testing
  - daily confirmation that the software remain stable
  - making progress visible, which helps maintain motivation
  - eliminating the risk of last-minute “big bang” integration
  - ensuring testable, deployable software is always available
  - reducing repetitive manual testing
  - providing faster feedback on quality decisions
- risks and challenges include:
  - need for ongoing setup and maintenance of integration tools
  - complexity in defining and maintaining the integration process
  - effort required to establish automated tests and maintain coverage
  - over reliance on unit tests, with insufficient system and acceptance testing

## FA-1.2.5 (K1) Know the differences between iteration and release planning, and how a tester adds value

- release planning focuses on defining the product backlog and planning across multiple iterations. It may span months ahead and helps form a high-level test approach.
- tester contribution
  - defining testable user stories with clear acceptance criteria.
  - participating in project and quality risk analysis.
  - estimating test effort with the user stories.
  - planning test levels and test activities across iterations.
- iteration planning focuses on the scope of a single iteration. The team selects user stories based on priority and capacity, performs detailed analysis, and defines tasks.
- tester roles
  - analysing user stories risks.
  - determining story testability.
  - creating acceptance tests.
  - defining and estimating testing tasks.
  - identifying functional and non-functional testing needs.
  - supporting test automation for the selected stories.=
- release and iteration plans may change due to internal (velocity, delivery capacity) or external (market changes, competition) factors.
- agile testers must adapt quickly while maintaining a clear understanding of test objectives and strategy.
- testing must be planned in parallel with development.
- **test planning aspects include:**
  - scope and extent of testing, including goals and reasons for these decision.
  - roles and responsibilities in test activities.
  - test environments and data requirements.
  - test schedules, dependencies, and frequency.
  - risks to address and their impact on planning.
- in addition, the larger team estimation effort should include consideration of the time and effort needed to complete the required testing activities.
