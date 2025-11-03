# Chapter 3: Agile Testing Methods, Techniques, and Tools – Extended Quiz

## K1 – Remember (10 Questions)

1. **Which practice ensures that unit-level automated tests are always in place before implementing new functionality in Agile?**  
a) Exploratory Testing  
b) Code Walkthrough  
c) Test-Driven Development  
d) Behavioral Modeling  
**Answer**: ***c) Test-Driven Development***  
**Explanation**: TDD mandates writing unit-level tests first, guiding code development by the desired behavior.

2. **What is the characteristic output of BDD when correctly implemented in Agile environments?**  
a) Automated acceptance tests written in natural language  
b) Code-level test stubs used only by developers  
c) Manual test cases reviewed after release  
d) Checklists derived from regression defects  
**Answer**: ***a) Automated acceptance tests written in natural language***  
**Explanation**: BDD focuses on natural-language definitions like 'Given-When-Then' that are executable and reflect business intent.

3. **According to the Agile test pyramid, which type of test is most numerous and foundational to early defect detection?**  
a) Acceptance tests based on business needs  
b) Unit tests validating low-level functionality  
c) Manual exploratory tests  
d) Performance tests executed late in sprint  
**Answer**: ***b) Unit tests validating low-level functionality***  
**Explanation**: Unit tests form the foundation of the pyramid and catch issues early and frequently.

4. **What role do integration tests play in the Agile testing strategy?**  
a) They validate user interface consistency  
b) They confirm business rules across systems  
c) They simulate full system behavior  
d) They verify interaction between multiple modules or components  
**Answer**: ***d) They verify interaction between multiple modules or components***  
**Explanation**: Integration tests ensure components interact correctly after unit validation.

5. **Which of the following best reflects the structure used in Behavior-Driven Development?**  
a) Setup → Execution → Result  
b) What → Who → Why  
c) Given → When → Then  
d) Arrange → Act → Assert  
**Answer**: ***c) Given → When → Then***  
**Explanation**: BDD scenarios follow a structured format to express behavior and expected outcomes.

6. **Which layer of the Agile test pyramid focuses on automated testing of interfaces between modules?**  
a) Bottom (Unit Tests)  
b) Middle (Integration Tests)  
c) Top (System Tests)  
d) Auxiliary (Usability Tests)  
**Answer**: ***b) Middle (Integration Tests)***  
**Explanation**: Integration tests reside in the middle layer of the pyramid and test API or module connections.

7. **In which Agile quadrant do performance and reliability tests typically belong?**  
a) Quadrant 1  
b) Quadrant 2  
c) Quadrant 4  
d) Quadrant 3  
**Answer**: ***c) Quadrant 4***  
**Explanation**: Quadrant 4 focuses on technology-facing tests that critique product quality like load and performance.

8. **What is the outcome of successfully executed ATDD in an Agile project?**  
a) Shared, testable acceptance criteria before coding  
b) Automated user interface testing scripts  
c) Static documentation of business expectations  
d) Retrospective-driven feedback forms  
**Answer**: ***a) Shared, testable acceptance criteria before coding***  
**Explanation**: ATDD ensures acceptance tests are defined collaboratively before coding starts.

9. **Which Agile technique reduces ambiguity in user stories by clarifying examples with stakeholders?**  
a) System simulation modeling  
b) Test automation debugging  
c) Specification workshops  
d) Technical backlog grooming  
**Answer**: ***c) Specification workshops***  
**Explanation**: Specification workshops help define tests and scope clearly before development.

10. **How are exploratory test results typically documented in Agile?**  
a) As structured scripts stored in version control  
b) In oral debriefs during retrospectives  
c) Inside automated test tools via source annotations  
d) Through session notes capturing charters, actions, and observations  
**Answer**: ***d) Through session notes capturing charters, actions, and observations***  
**Explanation**: Session-based exploratory testing uses charters and notes to document purpose, findings, and test coverage.

---

## K2 – Understand  (10 Questions)

11. **Why does the Agile test pyramid recommend fewer system-level tests compared to unit tests?**  
a) System tests are more reliable and easier to maintain than unit tests  
b) System-level tests are expensive to run, slow, and often brittle in fast iterations  
c) Unit tests are more effective at detecting integration-level defects early  
d) Agile discourages automated testing at system level entirely  
**Answer**: ***b) System-level tests are expensive to run, slow, and often brittle in fast iterations***  
**Explanation**: System-level tests are harder to maintain and slower, so Agile emphasizes automation at lower levels.

12. **Which principle supports the collaborative creation of acceptance tests before coding begins?**  
a) Acceptance Test-Driven Development  
b) Continuous deployment  
c) Behavior-Driven Code Reviews  
d) Regression-First Planning  
**Answer**: ***a) Acceptance Test-Driven Development***  
**Explanation**: ATDD ensures shared understanding by defining acceptance tests with business and devs before development.

13. **What is the tester's primary role during specification workshops?**  
a) To negotiate timelines for QA environments  
b) To contribute examples and help define testable acceptance criteria  
c) To verify system test scripts post-development  
d) To validate build success for previous sprint items  
**Answer**: ***b) To contribute examples and help define testable acceptance criteria***  
**Explanation**: Testers use domain and testing expertise to ensure acceptance criteria are clear and testable early.

14. **How do Agile testing quadrants help teams design a comprehensive test strategy?**  
a) They divide testing by product feature and module ownership  
b) They provide a matrix to select tools for automated deployment  
c) They represent a timeline for each test activity across sprints  
d) They organize tests by whether they support development or critique the product, and by audience focus  
**Answer**: ***d) They organize tests by whether they support development or critique the product, and by audience focus***  
**Explanation**: The quadrants help teams organize test types by their purpose and who benefits from the feedback.

15. **What is the benefit of applying risk-based prioritization during iteration planning?**  
a) It reduces the need for exploratory testing  
b) It ensures the test team has fewer blockers  
c) It allows automation scripts to be reused across stories  
d) It helps allocate effort to backlog items that present the highest risk  
**Answer**: ***d) It helps allocate effort to backlog items that present the highest risk***  
**Explanation**: Agile testers help the team direct test effort where the business or technical risk is greatest.

16. **In Agile, how does test effort estimation account for feature complexity?**  
a) By mapping user story points to test case counts  
b) By considering risk, testing scope, and level of uncertainty during Planning Poker  
c) By calculating code coverage percentage  
d) By referencing the test matrix from previous releases  
**Answer**: ***b) By considering risk, testing scope, and level of uncertainty during Planning Poker***  
**Explanation**: Test effort in Agile uses collaborative estimation based on feature risk, size, and complexity.

17. **Why is exploratory testing considered valuable even when test automation is in place?**  
a) Because it replaces the need for regression suites  
b) Because automation cannot detect performance defects  
c) Because exploratory testing is always faster than automated scripts  
d) Because automated tests only cover specified paths and miss context-based issues  
**Answer**: ***d) Because automated tests only cover specified paths and miss context-based issues***  
**Explanation**: Exploratory testing finds unexpected issues and fills gaps left by automation based on assumptions.

18. **What is a key difference between black-box test design techniques in Agile compared to traditional contexts?**  
a) They focus more on code coverage metrics in Agile  
b) They are driven by evolving user stories and acceptance criteria rather than fixed specs  
c) They are automated by default in Agile  
d) They exclude non-functional testing from the start  
**Answer**: ***b) They are driven by evolving user stories and acceptance criteria rather than fixed specs***  
**Explanation**: Agile black-box tests are derived dynamically from living artifacts like stories, criteria, and charters.

19. **How does the 'definition of done' influence testing activities in Agile teams?**  
a) It defines the criteria for when testing of a story is considered complete  
b) It forces only exploratory testing to be completed  
c) It is maintained solely by Scrum Masters  
d) It includes activities unrelated to product validation  
**Answer**: ***a) It defines the criteria for when testing of a story is considered complete***  
**Explanation**: The definition of done ensures agreed test coverage, quality gates, and completion standards are met.

20. **What makes test charters especially important in session-based exploratory testing?**  
a) They serve as formal test plans  
b) They provide traceability to release documents  
c) They ensure testers avoid exploratory bias  
d) They define scope, purpose, data, and priorities for each exploratory session  
**Answer**: ***d) They define scope, purpose, data, and priorities for each exploratory session***  
**Explanation**: Charters outline the structure and goals of a time-boxed session, keeping testing focused and effective.

---

## K3 – Apply  (10 Questions)

21. **You're reviewing a user story where no negative behavior has been defined. What’s your best next step as a tester in an Agile team?**  
a) Refuse to test the story until it's rewritten  
b) Request a formal sign-off from the product owner  
c) Collaborate with the team to define negative acceptance test cases before implementation begins  
d) Focus only on the 'happy path' scenario for automation  
**Answer**: ***c) Collaborate with the team to define negative acceptance test cases before implementation begins***  
**Explanation**: Agile testers help improve story clarity by suggesting negative test cases early, especially in ATDD.

22. **During iteration planning, your team agrees a payment feature is high-risk and technically complex. What should guide your testing approach?**  
a) Use only unit tests since the risk is already known  
b) Defer testing to user acceptance sessions  
c) Prioritize test effort using quality risk analysis and apply layered testing techniques  
d) Rely on exploratory testing alone due to complexity  
**Answer**: ***c) Prioritize test effort using quality risk analysis and apply layered testing techniques***  
**Explanation**: Testers should apply risk-based test planning and choose appropriate techniques to mitigate each risk.

23. **You need to assess how well testing activities have covered the key user stories in a sprint. Which action best supports this?**  
a) Run every automated test case twice  
b) Trace acceptance criteria to test cases and check session-based exploratory coverage  
c) Reassign all bugs to the developers  
d) Evaluate overall team velocity  
**Answer**: ***b) Trace acceptance criteria to test cases and check session-based exploratory coverage***  
**Explanation**: Coverage is ensured by aligning acceptance criteria, exploratory charters, and test execution artifacts.

24. **You're leading exploratory testing of a feature with multiple paths and a complex UI. Which exploratory session setup is most suitable?**  
a) Single, unstructured session with full feature scope  
b) Regression session using prior scripts only  
c) Multiple short sessions with focused charters covering inputs, outputs, and edge behaviors  
d) Session targeting UI aesthetics  
**Answer**: ***c) Multiple short sessions with focused charters covering inputs, outputs, and edge behaviors***  
**Explanation**: Agile testers use focused exploratory sessions with clear charters to uncover deeper behaviors in complex features.

25. **A story contains a requirement for password input to reject invalid entries. What black-box technique would be most effective?**  
a) Use state transition to evaluate page redirections  
b) Use exploratory testing only  
c) Apply equivalence partitioning and boundary analysis for input validation  
d) Measure code coverage to determine inputs  
**Answer**: ***c) Apply equivalence partitioning and boundary analysis for input validation***  
**Explanation**: Input validation scenarios benefit from equivalence partitioning and boundary value analysis.

26. **During refinement, the team discusses a story with unclear performance expectations. What should you do?**  
a) Add a placeholder test case to cover it later  
b) Suggest deferring the story until QA builds a test plan  
c) Work with stakeholders to define measurable performance acceptance criteria for inclusion in the story  
d) Flag the story as testable without change  
**Answer**: ***c) Work with stakeholders to define measurable performance acceptance criteria for inclusion in the story***  
**Explanation**: Clarifying non-functional criteria early ensures accurate testing scope and prevents gaps.

27. **The team frequently reuses exploratory sessions without updating them between sprints. What’s your recommendation?**  
a) Convert all sessions to regression scripts  
b) Archive past sessions and focus only on automation  
c) Review and update test charters based on sprint goals, risks, and product changes  
d) Eliminate session testing entirely to save time  
**Answer**: ***c) Review and update test charters based on sprint goals, risks, and product changes***  
**Explanation**: Session-based testing should adapt to sprint context and current risks. Charters must evolve.

28. **You're designing acceptance tests for a login feature. Which approach aligns best with ATDD?**  
a) Create functional and non-functional test cases post-release  
b) Document login UI expectations without scenarios  
c) Define collaborative examples with 'Given-When-Then' format to guide development and verification  
d) Base tests only on UI wireframes  
**Answer**: ***c) Define collaborative examples with 'Given-When-Then' format to guide development and verification***  
**Explanation**: ATDD uses business-facing examples to define expectations before development starts.

29. **Mid-sprint, a new user role is introduced affecting access to multiple features. What should you prioritize?**  
a) Run security tools after deployment  
b) Test happy-path scenarios only  
c) Review and extend exploratory and acceptance tests to reflect new role permissions  
d) Notify management but skip testing changes  
**Answer**: ***c) Review and extend exploratory and acceptance tests to reflect new role permissions***  
**Explanation**: The tester adapts scope to evolving stories and access conditions, especially for user roles and permissions.

30. **Your team uses Planning Poker for effort estimation. What do you consider when estimating test effort for a highly volatile story?**  
a) Only the size of the UI and number of input fields  
b) Recent bug counts from unrelated stories  
c) Risk level, required test types, and historical complexity of similar features  
d) Static code analysis tool output  
