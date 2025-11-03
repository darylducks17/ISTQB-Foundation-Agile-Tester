# Chapter 3: Agile Testing Methods, Techniques, and Tools – Extra Quiz

## K1 – Remember (10 Questions)

1. **What is the first step in the TDD cycle?**  
a) Write a test that fails  
b) Refactor code  
c) Deploy to production  
d) Execute regression tests  
**Answer**: ***a) Write a test that fails***  
**Explanation**: TDD starts by writing a failing test to define expected behavior.

2. **What testing technique writes tests using plain, structured language?**  
a) Exploratory Testing  
b) Boundary Value Analysis  
c) Behavior-Driven Development  
d) State Transition Testing  
**Answer**: ***c) Behavior-Driven Development***  
**Explanation**: BDD uses 'Given-When-Then' format in plain language to describe expected behavior.

3. **What is emphasized at the bottom of the test pyramid?**  
a) Manual testing  
b) GUI automation  
c) Unit tests  
d) System testing  
**Answer**: ***c) Unit tests***  
**Explanation**: The base layer of the test pyramid emphasizes automated unit tests.

4. **Which quadrant of Agile testing includes performance and load tests?**  
a) Q1  
b) Q2  
c) Q3  
d) Q4  
**Answer**: ***d) Q4***  
**Explanation**: Q4 is tech-facing and includes operational acceptance tests like performance.

5. **Which testing level confirms integration between modules?**  
a) Unit  
b) System  
c) Integration  
d) User acceptance  
**Answer**: ***c) Integration***  
**Explanation**: Integration testing checks interfaces and interactions between components.

6. **What is the output of a BDD scenario?**  
a) HTML spec  
b) Database script  
c) Executable test case  
d) Manual checklist  
**Answer**: ***c) Executable test case***  
**Explanation**: BDD frameworks can generate executable tests from structured scenario descriptions.

7. **Which Agile technique clarifies scope and minimizes redundancy in acceptance tests?**  
a) Smoke testing  
b) Pair programming  
c) Specification workshops  
d) Mutation testing  
**Answer**: ***c) Specification workshops***  
**Explanation**: Specification workshops help teams clarify and align acceptance tests before development.

8. **What is the tester’s responsibility in Sprint Zero?**  
a) Developing architecture  
b) Designing UI wireframes  
c) Creating initial test strategy  
d) Writing user manuals  
**Answer**: ***c) Creating initial test strategy***  
**Explanation**: Sprint Zero involves defining scope, tools, risks, and test strategy.

9. **Which quadrant involves exploratory testing and UX evaluation?**  
a) Q1  
b) Q2  
c) Q3  
d) Q4  
**Answer**: ***c) Q3***  
**Explanation**: Q3 contains manual, business-facing activities that critique the product.

10. **What role do configuration management tools play in Agile testing?**  
a) Run A/B tests  
b) Store code only  
c) Link builds to test runs and artifacts  
d) Maintain chat logs  
**Answer**: ***c) Link builds to test runs and artifacts***  
**Explanation**: They track source code and link it with test artifacts and versions.

---

## K2 – Understand (10 Questions)

11. **How does ATDD improve collaboration in Agile teams?**  
a) It facilitates shared understanding through early test definition  
b) It separates testing from development  
c) It ensures business stakeholders define release deadlines  
d) It encourages only testers to write tests  
**Answer**: ***a) It facilitates shared understanding through early test definition***  
**Explanation**: ATDD aligns business, dev, and test roles early through shared acceptance tests.

12. **What is the purpose of the testing quadrants in Agile?**  
a) To organize types of tests by purpose and audience  
b) To eliminate test overlap  
c) To reduce documentation  
d) To delay non-functional testing  
**Answer**: ***a) To organize types of tests by purpose and audience***  
**Explanation**: The quadrants show how different tests support dev or critique the product, from technical or business perspectives.

13. **Why are exploratory testing sessions time-boxed in Agile?**  
a) To focus tester creativity and limit waste  
b) To improve communication  
c) To reduce overtime  
d) To prepare checklists  
**Answer**: ***a) To focus tester creativity and limit waste***  
**Explanation**: Time-boxing focuses effort, maintains pace, and aligns testing with sprint cadence.

14. **Why is mind mapping used by Agile testers?**  
a) To design UI layouts  
b) To visualize test sessions and organize ideas  
c) To report bugs  
d) To write SQL queries  
**Answer**: ***b) To visualize test sessions and organize ideas***  
**Explanation**: Mind maps help visually plan test cases, charters, and data exploration.

15. **What kind of risk does 'slow response time' represent?**  
a) Performance risk  
b) Security risk  
c) Usability problem  
d) Functional defect  
**Answer**: ***a) Performance risk***  
**Explanation**: Slow response time is a non-functional quality risk under performance.

16. **Why do Agile teams evolve regression test suites?**  
a) To adapt tests to changing features and risks  
b) To ensure outdated tests are kept  
c) To satisfy audit requirements  
d) To reduce pair testing  
**Answer**: ***a) To adapt tests to changing features and risks***  
**Explanation**: Tests must evolve to stay relevant and reflect current product behavior.

17. **What is a typical output of a specification workshop?**  
a) Defined test examples for acceptance criteria  
b) Wireframes  
c) Prioritized product backlog  
d) Working software  
**Answer**: ***a) Defined test examples for acceptance criteria***  
**Explanation**: Spec workshops result in clear test examples to drive development and testing.

18. **Which quadrant typically includes automated unit tests supporting developers?**  
a) Q1  
b) Q2  
c) Q4  
d) Q3  
**Answer**: ***a) Q1***  
**Explanation**: Q1 includes tech-facing, dev-supporting tests like automated units.

19. **How are testing tasks typically planned in Agile sprints?**  
a) Decomposed into small tasks during sprint planning  
b) Fixed during release planning  
c) Defined only by Scrum Masters  
d) Documented after UAT  
**Answer**: ***a) Decomposed into small tasks during sprint planning***  
**Explanation**: Agile teams plan and decompose testing tasks collaboratively per sprint.

20. **Why do Agile teams use wikis or shared dashboards?**  
a) To provide visible progress and encourage team collaboration  
b) To replace all documentation  
c) To support remote exploratory testing  
d) To limit stakeholder access  
**Answer**: ***a) To provide visible progress and encourage team collaboration***  
**Explanation**: Wikis and dashboards promote transparency and team-wide alignment.

---

## K3 – Apply (10 Questions)

21. **You join a planning session and the team identifies a high likelihood and impact of UI defects. What should you suggest?**  
a) Increase exploratory testing and usability checks  
b) Automate unit tests only  
c) Defer testing to UAT  
d) Shorten the sprint  
**Answer**: ***a) Increase exploratory testing and usability checks***  
**Explanation**: High UI risks call for exploratory and usability-focused test strategies.

22. **During a spec workshop, a tester suggests writing examples before code. What Agile practice is this?**  
a) Behavior-driven development  
b) Regression testing  
c) Static analysis  
d) User acceptance testing  
**Answer**: ***a) Behavior-driven development***  
**Explanation**: Writing examples before code aligns with BDD and ATDD principles.

23. **You're preparing exploratory testing for a new payment feature. What must your charter include?**  
a) Actor, purpose, activities, and test data  
b) Bug list from last sprint  
c) Performance benchmark  
d) Deployment plan  
**Answer**: ***a) Actor, purpose, activities, and test data***  
**Explanation**: A test charter defines the scope, purpose, and key focus for the exploratory session.

24. **The team asks for test effort estimates. What do you do?**  
a) Use planning poker considering feature complexity and risk  
b) Assign based on tester availability  
c) Assign a flat estimate to each story  
d) Ask the Scrum Master to decide  
**Answer**: ***a) Use planning poker considering feature complexity and risk***  
**Explanation**: Planning poker supports collaborative and risk-informed estimation.

25. **You identify that all acceptance tests are written post-development. What should you suggest?**  
a) Move acceptance test design earlier using ATDD  
b) Switch to black-box testing only  
c) Limit to exploratory testing  
d) Do nothing  
**Answer**: ***a) Move acceptance test design earlier using ATDD***  
**Explanation**: ATDD helps define acceptance tests early, guiding development and reducing rework.

26. **A team asks how to ensure performance tests are consistent across sprints. What approach do you recommend?**  
a) Automated performance regression testing  
b) Manual checks only  
c) Use spreadsheet logs  
d) Postpone until release testing  
**Answer**: ***a) Automated performance regression testing***  
**Explanation**: Automated performance tests detect regressions and ensure consistency.

27. **You're asked to test login behavior across devices. What tool or method helps best?**  
a) Exploratory testing with device emulators or virtualization  
b) Print the test scripts  
c) Use mind maps only  
d) Ask devs to simulate all devices  
**Answer**: ***a) Exploratory testing with device emulators or virtualization***  
**Explanation**: Emulators and virtualization allow device coverage without physical hardware.

28. **You find outdated black-box tests in the suite. What should you do?**  
a) Refactor or remove based on current requirements  
b) Keep all for traceability  
c) Duplicate and rename  
d) Convert them to white-box tests  
**Answer**: ***a) Refactor or remove based on current requirements***  
**Explanation**: Test maintenance ensures relevance and reduces noise.

29. **You review a story that lacks clear non-functional expectations. What do you do?**  
a) Clarify and add performance or usability acceptance criteria  
b) Ignore it  
c) Mark it done anyway  
d) Escalate to management  
**Answer**: ***a) Clarify and add performance or usability acceptance criteria***  
**Explanation**: Quality attributes should be defined and testable for each story.

30. **Your exploratory session revealed an unexpected crash. What's the next action?**  
a) Raise it as a defect with session documentation  
b) Skip it and rerun  
c) Wait for end of sprint  
d) Restart the app  
**Answer**: ***a) Raise it as a defect with session documentation***  
**Explanation**: Exploratory results must be documented and fed back into the defect and risk process.
