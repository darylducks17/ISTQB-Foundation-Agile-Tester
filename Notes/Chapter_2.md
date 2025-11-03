# Chapter 2: Fundamental Agile Testing Principles, Practices, and Processes

| K-Level | Question Distribution | Learning Objective                                                                                         | Number of Questions |
|---------|------------------------|------------------------------------------------------------------------------------------------------------|----------------------|
| K1      | Keywords               | Recall relevant terms                                                                                      | 1                    |
| K2      | FA-2.1.1               | Describe the differences between testing activities in Agile and non-Agile projects                        | 1                    |
| K2      | FA-2.1.2               | Describe how development and testing activities are integrated in Agile projects                           | 1                    |
| K2      | FA-2.1.3               | Describe the role of independent testing in Agile projects                                                 | 2                    |
| K2      | FA-2.2.1               | Describe tools and techniques used to communicate testing status, test progress, and product quality       | 2                    |
| K2      | FA-2.2.2               | Describe test evolution and the role of automation in regression risk management in Agile                  | 2                    |
| K2      | FA-2.3.1               | Understand the skills (people, domain, testing) of a tester in an Agile team                               | 1                    |
| K2      | FA-2.3.2               | Understand the role of a tester within an Agile team                                                       | 2                    |

**Total Questions for Chapter 2: 12**
K1 = 1, K2 = 11, K3 = 0
Total Points: 12

## FA-2.1.1(K2) Describe the differences between testing activities in Agile and non-Agile projects

- structured around short iterations that each produce working software
- planning is done at both release and iteration planning
- special agile test levels:
  - testing occurs throughout each iteration - not at the end
  - feature (acceptance)testing
    - feature verification testing (often automated against the user story acceptance criteria by developer or testers
    - feature validation testing (usually manual) by developers, testes and business stakeholders
- test doc
  - still needed but lightweight doc is favoured
- test techniques
  - more scripted automation means more use of experience-based and defect based for manual testing e.g. software attacks, exploratory testing and error guessing
- everyone tests - whole team take ownership of quality:
  - devs
    - perform unit testing during feature implementation
    - may use tdd
    - hopefully automated and as part of CI including static analysis
  - testers
    - verify completed features
    - may serve as testing and quality coaches
  - both devs and testers may pair up to test (and develop) a feature
  - business stakeholders
    - test the stories during implementation (scripted/unscripted) to provide immediate feedback
- some teams use “hardening” iterations to resolve defects/ technical debt, although best practice is to finish each feature fully within its own iteration
- a fix bug first approach can be used, where defects from one iteration are handled early in the next → can complete effort estimation
- release activities may follow the full iteration cycle or happen at the end of each iteration
- high rate of change
  - means more regression testing
  - encourage test automation
    - favours technical testers
    - automated integration, system and system integration tests

## FA-2.1.2 (K2) Describe how development and testing activities are integrated in Agile projects

- development, integration and testing activities take place throughout each iteration, with considerable parallelism and overlap
- business reps
  - test the stories during implementation
  - might use written test cases, but they also might simply experiment with and use the feature to provide fast feedback
- devs
  - perform unit tests as they develop features from the user stories
    - TDD - incrementally before each portion of code
    - after code
  - often create automated unit tests, especially using open-source frameworks such as CPP-unit and J-Unit
  - CI
    - mature orgs incorporate unit integration tests into their unit test frameworks
    - mature orgs incorporate unit integration tests in the automated regression tests
- Testers
  - test the story features
    - pairing involves a tester working collaboratively with a dev to develop and test a feature
  - focus on creating automated integration, system and system integration tests
    - favours testers with a strong and test automation background

## FA-2.1.3 (K2) Describe the role of independent testing in Agile projects

- rationale for independent testing
  - Independent testers are often more effective at finding defects
    - provide an objective, unbiased evaluation
- independent testing options
  - embedded testers
    - one or more testers embedded within the team performing testing tasks
    - pros
      - enhanced communication and collaboration
    - cons
      - risk losing independence
      - lack objective evaluation
  - semi-independent test team
    - testers loaned long-term to agile team
    - also specialised testers kept outside of the agile teams (work on long-term and/or iteration-independent activities)
      - developing automated test tools
      - carrying out non-functional testing
      - creating and supporting test envs and data
      - carrying out test levels that don’t fit well within a sprint (e.g. system integration testing)
    - pros
      - maintain their independence
      - gain a good understanding of the product
      - strong relationships with the rest of the team
  - fully independent, separate test teams
    - assign tester on demand during the final days of each sprint
    - pros
      - independence
      - objective, unbiased evaluation
    - cons
      - time pressures
      - lack of understanding of the new features
      - relationship issues with business stakeholders and devs

## FA-2.2.1 (K2) Describe tools and techniques used to communicate testing status, test progress, and product quality

- test progress
  - agile taskboard
    - test tasks
      - relate to AC defined for user story
        - test automation scripts
        - manual tests
        - exploratory tests
      - stories
  - burndown charts
    - across entire release
    - within an iteration
  - status reports
    - test automation results
    - task progress
  - communicated via
    - wiki dashboards
    - dashboard style emails
    - verbally during standup meeting
      - what have you completed?
      - what do you plan to complete?
      - what is getting in your way?
- product quality
  - customer satisfaction surveys
  - metrics
    - test pass/fail rates
    - defect discovery rates
    - confirmation and regression test results
    - defect density
    - defects found and fixed
    - requirements coverage
    - risk coverage
    - code coverage
    - code churn
    - note used to reward, punish or isolate team members

## FA-2.2.2 (K2) Describe test evolution and the role of automation in regression risk management in Agile

- evolving testing
  - why?
    - required to maintain alignment with changing code
      - review tests to select those for the regression test suite to retire others
  - tests assets:
    - automated tests
    - manual test cases
    - test data
  - requirements
    - configuration management tool
      - to enable version control
      - to ensure ease of access byu all team members
      - to support making changes while still preserving historic information
    - good test design and implementation (adopted early and applied consistently)
      - for ease of maintenance
    - test automation
      - provides rapid feedback on product quality by specifying required functionality and corresponding test results
- regression test automation
  - why?
    - to maintain velocity without incurring too much technical debt
  - types
    - unit
    - build verification tests
      - critical subset of automated tests
      - run on new build deployment
      - provide instant feedback on the build
    - acceptance tests are run at least daily against a complete system build as part of CI
      - measure product quality with respect to regression, but they do not measure overall product quality
    - if regression test failure
      - due to functional changes
        - the test may need to be updated
        - the test may need to be retired
      - due to a defect
        - fix the defect prior to progressing with new features

## FA-2.3.1 (K2) Understand the skills (people, domain, testing) of a tester in an Agile team

- proficiency in
  - test automation
  - test-driven development
  - acceptance test-driven  development
  - white-box testing
  - experience-based testing
- interpersonal skills
  - be positive and solution-oriented with team members and stakeholders
  - display critical, quality-oriented, skeptical thinking about the product
  - actively acquire information from stakeholders (rather than a written specification)
  - accurately evaluate and report test results, test progress and product quality
  - work with customer representatives and stakeholders to define testable user stories, especially acceptance criteria
  - collaborate within the team, working in pairs with the programmers and others
  - respond to change quickly or improve test cases
  - plan and organise their own work

## FA-2.3.2 (K2) Understand the role of a tester within an Agile team

- required activities
  - understand, implement and update the test strategy
  - measure and report test coverage
  - ensure proper use of testing tools
  - configure, use and manage test envs and test data
  - report defects and work with the team to resolve them
  - coach other team members in testing
  - ensure testing tasks are scheduled during release and iteration planning
  - collaborate to clarify requirements, especially in terms of testability and implementing improvements
  - shared responsibility for product quality
- provide feedback on
  - test status
  - test progress
  - product quality
  - process quality
