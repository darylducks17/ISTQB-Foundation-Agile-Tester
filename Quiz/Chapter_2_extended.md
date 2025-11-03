# Chapter 2: Fundamental Agile Testing Principles, Practices, and Processes - Extended Quiz

## K1 – Remember (10 Questions)

1. **What is an epic in Agile?**  
a) A developer-only document  
b) A completed test plan  
c) A large user story that can be split into smaller stories  
d) A final sprint  
**Answer**: ***c) A large user story that can be split into smaller stories***  
**Explanation**: Epics are large user stories broken into smaller ones over multiple sprints.

2. **What document describes small, testable Agile requirements?**  
a) User story  
b) Use case  
c) Test script  
d) Burnup chart  
**Answer**: ***c) Test script***  
**Explanation**: User stories describe testable features needed by users.

3. **Which role defines and clarifies acceptance criteria in Agile?**  
a) Product owner  
b) Project manager  
c) Business analyst  
d) UX designer  
**Answer**: ***a) Product owner***  
**Explanation**: Product owners work closely with the team to define and clarify acceptance criteria.

4. **Who performs unit testing in Agile?**  
a) Testers  
b) Developers  
c) Business analysts  
d) Customers  
**Answer**: ***b) Developers***  
**Explanation**: Developers typically perform unit testing during feature implementation.

5. **Which Agile artifact shows remaining work during a sprint?**  
a) Velocity chart  
b) Risk matrix  
c) Traceability matrix  
d) Burndown chart  
**Answer**: ***d) Burndown chart***  
**Explanation**: A burndown chart visually shows work left versus time in a sprint.

6. **What is a user story associated with?**  
a) Acceptance criteria  
b) Deployment  
c) Bug reports  
d) Release notes  
**Answer**: ***d) Release notes***  
**Explanation**: Each user story should have associated acceptance criteria for testing.

7. **Which test activity involves checking that a feature works for the user?**  
a) Static analysis  
b) Unit test  
c) Feature validation  
d) Code review  
**Answer**: ***c) Feature validation***  
**Explanation**: Feature validation confirms that the feature satisfies user needs.

8. **What is the purpose of lightweight documentation in Agile?**  
a) Avoiding all written documents  
b) Creating marketing materials  
c) Support collaboration while avoiding unnecessary detail  
d) Meeting legal compliance  
**Answer**: ***c) Support collaboration while avoiding unnecessary detail***  
**Explanation**: Agile uses minimal but sufficient documentation to support teamwork.

9. **What is typically avoided in Agile test documentation?**  
a) Heavy formal documentation  
b) Automation scripts  
c) Acceptance criteria  
d) Defect logs  
**Answer**: ***b) Heavy formal documentation***  
**Explanation**: Agile avoids heavy documents in favor of lightweight, useful ones.

10. **What test level occurs first during development?**  
a) Acceptance testing  
b) System testing  
c) Unit testing  
d) Feature validation  
**Answer**: ***d) Feature validation***  
**Explanation**: Unit testing is the first level performed by developers during implementation.

---

## K2 – Understand  (10 Questions)

11. **What is the primary role of the tester during iteration planning?**  
a) Clarify acceptance criteria and estimate effort  
b) Finalize the release plan  
c) Execute manual test cases  
d) Set marketing goals  
**Answer**: ***a) Clarify acceptance criteria and estimate effort***  
**Explanation**: Testers ensure that stories are testable and provide input on the scope and effort.

12. **How do Agile testers help manage configuration risk?**  
a) Create daily status reports  
b) Use manual regression cycles  
c) Deploy static test plans  
d) Automate build verification tests  
**Answer**: ***d) Automate build verification tests***  
**Explanation**: Build verification tests help ensure stable builds in CI/CD pipelines.

13. **What’s the tester’s role in a retrospective?**  
a) Report number of test cases  
b) Propose improvements to test strategy and quality  
c) Verify backlog is ready  
d) Skip attendance to focus on automation  
**Answer**: ***b) Propose improvements to test strategy and quality***  
**Explanation**: Testers contribute feedback to improve test processes and team collaboration.

14. **How is independent testing often integrated into Agile teams?**  
a) Using external auditors post-release  
b) Hiring third-party vendors  
c) Embedding testers within development teams  
d) Postponing testing until hardening sprints  
**Answer**: ***b) Embedding testers within development teams***  
**Explanation**: Embedded testers support real-time discussions and continuous quality checks.

15. **What’s the impact of pairing between testers and developers?**  
a) Removes need for unit tests  
b) Increases documentation overhead  
c) Strengthens collaboration and code quality  
d) Reduces feedback quality  
**Answer**: ***d) Strengthens collaboration and code quality***  
**Explanation**: Pairing builds shared understanding and quality ownership across roles.

16. **Why is automated regression testing important in Agile?**  
a) Prevents exploratory testing  
b) Supports continuous integration and change readiness  
c) It allows ignoring test failures  
d) Eliminates performance testing  
**Answer**: ***d) Supports continuous integration and change readiness***  
**Explanation**: Regression automation enables agility while keeping quality intact.

17. **What test data practice supports evolving Agile tests?**  
a) Maintain version-controlled test data  
b) Use data from production only  
c) Avoid storing test data  
d) Reuse unchanged data  
**Answer**: ***b) Maintain version-controlled test data***  
**Explanation**: Versioned test data supports repeatability and adaptability of test cases.

18. **What is a task board used for in Agile?**  
a) Automate unit tests  
b) Record daily work hours  
c) Track test and dev tasks across states  
d) Replace requirement documents  
**Answer**: ***b) Track test and dev tasks across states***  
**Explanation**: Task boards track progress visually across stages like To Do, In Progress, and Done.

19. **Which tester behavior adds risk to Agile quality?**  
a) Working closely with developers  
b) Accepting low test coverage silently  
c) Communicating concerns in retrospectives  
d) Focusing on exploratory testing  
**Answer**: ***a) Accepting low test coverage silently***  
**Explanation**: Ignoring or accepting quality issues can compromise Agile quality principles.

20. **Which Agile test practice helps ensure fast feedback loops?**  
a) Waterfall handoffs  
b) Continuous integration with automated tests  
c) Monthly test reviews  
d) Heavy release planning  
**Answer**: ***b) Continuous integration with automated tests***  
**Explanation**: CI and test automation ensure rapid detection and resolution of defects.

---

## K3 – Apply  (10 Questions)

21. **You find that a critical regression test has started failing after a refactor. What should you do first?**  
a) Ignore it until more fail  
b) Blame the developer  
c) Investigate if it's a valid failure or a broken test  
d) Disable the test  
**Answer**: ***a) Investigate if it's a valid failure or a broken test***  
**Explanation**: Regression test failures must be reviewed to determine root cause.

22. **Your team automates UI tests, but they're flaky and unreliable. What’s the best immediate action?**  
a) Refactor the tests to stabilize them  
b) Delete all tests  
c) Stop testing UI  
d) Switch to only manual testing  
**Answer**: ***a) Refactor the tests to stabilize them***  
**Explanation**: Flaky tests erode trust. Stability comes from good design and maintenance.

23. **During stand-up, the tester mentions that a test case can’t run due to missing test data. What should happen?**  
a) Collaborate with the team to create the required test data  
b) File a bug  
c) Escalate to senior management  
d) Wait until the sprint ends  
**Answer**: ***c) Collaborate with the team to create the required test data***  
**Explanation**: Agile encourages immediate team-level resolution of blockers.

24. **A new feature was completed, but no acceptance criteria were defined. What is the tester’s best action?**  
a) Test based on previous sprint items  
b) Collaborate with the product owner to define testable criteria  
c) Skip testing  
d) Create their own criteria  
**Answer**: ***a) Collaborate with the product owner to define testable criteria***  
**Explanation**: Acceptance criteria must be clear and agreed on before testing can proceed.

25. **The team wants to release faster but testers are overwhelmed with regression tests. What can help?**  
a) Automate regression tests strategically  
b) Ignore minor bugs  
c) Reduce test scope  
d) Add more manual testers  
**Answer**: ***d) Automate regression tests strategically***  
**Explanation**: Automation reduces manual load and supports frequent releases.

26. **A tester finds that the test suite includes outdated tests. What should they do?**  
a) Archive or remove tests no longer relevant  
b) Run them anyway  
c) Rewrite them blindly  
d) Ignore them  
**Answer**: ***d) Archive or remove tests no longer relevant***  
**Explanation**: Old or obsolete tests add noise and slow down feedback loops.

27. **The team is unsure if a user story is testable. What should the tester do?**  
a) Estimate anyway  
b) Help refine the story with clear acceptance criteria  
c) Skip the story  
d) Wait for the developer to implement it  
**Answer**: ***b) Help refine the story with clear acceptance criteria***  
**Explanation**: Testers ensure clarity and testability before implementation begins.

28. **You observe that developers are not checking unit test results before pushing code. What do you do?**  
a) File a bug  
b) Let it go  
c) Notify the scrum master privately  
d) Address it during a retrospective  
**Answer**: ***a) Address it during a retrospective***  
**Explanation**: Retrospectives are the right time to raise process improvements.

29. **You’re asked to report test progress. Which tool is most appropriate?**  
a) Task board and burndown chart  
b) Whiteboard at home  
c) External newsletter  
d) Daily email blast  
**Answer**: ***c) Task board and burndown chart***  
**Explanation**: Agile teams use visual tools to communicate test status transparently.

30. **Which test type best helps uncover unexpected issues in new features?**  
a) Regression  
b) UAT  
c) Exploratory  
d) Unit  
**Answer**: ***c) Exploratory***  
**Explanation**: Exploratory testing helps identify issues not covered by predefined cases.
