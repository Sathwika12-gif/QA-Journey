# Manual Testing Interview Questions

1. **What is the difference between verification and validation?**
A. Verification is the process of checking whether the software is built according to specifications and requirements, without executing the code.
    
    Validation is the process of checking whether the application meets the user’s needs and expectations by executing the application.
    
2. **What is a test scenario, and how is it different from a test case?
A.**  A **test scenario** is a high-level description of what functionality needs to be tested, usually derived from requirements.
    
    A **test case** is a detailed, step-by-step set of instructions used to verify a test scenario, including test data and expected results.
    
3. **Explain the bug life cycle in a real project.
A.**  The **bug life cycle** describes the different stages a defect goes through.
    
          When a tester finds a defect, it is logged in the **New** state.
    
    The bug is then **Assigned** to a developer.
    
    When the developer starts working on it, the status becomes **Open/In Progress**.
    
    After fixing, it is marked as **Fixed** and sent back for **Retesting**.
    
    If the issue is resolved, the tester **Closes** the bug.
    
    If the issue still exists, the tester **Reopens** it.
    
4. **What is sanity testing, and when do you perform it?
A. Sanity testing** is a type of testing performed after a bug fix or minor change to verify that the   specific functionality and its related areas are working correctly.
    
    It is **narrow and focused**, and it ensures that the build is stable enough for further testing.
    
5. **What will you do if a developer says, “This is not a bug”?
A.** If a developer says it is not a bug, I first re-check the requirement or test scenario provided by the BA or product team.
    
    If the behavior deviates from the expected requirement, I explain it to the developer with proper evidence such as steps, screenshots, or logs.
    
    If it is expected behavior, I accept it and close the defect. Otherwise, I discuss it with the BA or product owner for clarification.
    
6. **What is the difference between severity and priority? Give a real-time example.
A. Severity** defines how much the defect impacts the functionality of the application.
    
          **Priority** defines how quickly the defect should be fixed based on business needs.
    
    For example, if the **payment functionality is not working**, it is both **high severity and high priority** because it affects business transactions.
    
    If a **logo or UI text is misaligned**, it may have **low severity** but **high priority** if it affects the company’s branding.
    
7. **What is regression testing, and when do you perform it in a project?
A. Regression testing** is performed to ensure that existing functionalities are not affected by             new changes such as feature additions, enhancements, or bug fixes.
    
         In real projects, regression testing is usually performed **before every release** or after major           code changes to confirm the overall stability of the application.
    
8. **What is the difference between smoke testing and sanity testing?
A. Smoke testing** is performed on a new build to verify that the critical functionalities of the        application are working and the build is stable for further testing.
    
    **Sanity testing** is performed after minor changes or bug fixes to verify that the specific functionality and its related areas are working correctly.
    
    Smoke testing is **broad**, while sanity testing is **narrow and focused**.
    
9. **How do you write a good bug report? What details should it contain?
A.** A good bug report should contain:
    - Bug ID
    - Title/Summary
    - Description of the issue
    - Steps to reproduce
    - Expected result
    - Actual result
    - Severity and Priority
    - Environment details (browser, build, OS)
    - Screenshots or recordings
    - Assigned developer and status
10. **What will you do if you do not have proper requirement documents but still need to start testing?
A.** If requirement documents are not available, I first discuss with the **BA, product owner, or developers** to understand the expected functionality.
    
    Based on the available information, I start **exploratory testing** to understand the application behavior.
    
    Any doubts or deviations found during testing are clarified with stakeholders, and test scenarios are updated accordingly.
    
11. **What are the different types of black-box testing techniques?
A. Black box testing** is a testing method where the tester validates the functionality of the application **without knowing the internal code structure**.

    
    **Types of Black Box Testing Techniques**
    
    These are also called **Test Case Design Techniques** (this answers Question 2 also).
    
    The main ones are:
    
    ### 1. Equivalence Partitioning
    
    Divide input data into valid and invalid groups.
    
    Example:
    
    If age field accepts 18–60
    
    You test:
    
    - 25 (valid)
    - 10 (invalid)
    - 70 (invalid)
    
    Instead of testing all numbers.
    
    ---
    
    ### 2. Boundary Value Analysis (Very Important 🔥)
    
    Test values at boundaries.
    
    For 18–60:
    
    - 17
    - 18
    - 19
    - 59
    - 60
    - 61
    
    Interviewers love this one.
    
    ---
    
    ### 3. Decision Table Testing
    
    Used when output depends on multiple conditions.
    
    Example:
    
    Discount based on:
    
    - Membership
    - Purchase amount
    
    ---
    
    ### 4. State Transition Testing
    
    Used when application changes state.
    
    Example:
    
    Login attempts:
    
    - 3 wrong passwords → account locked
12. **What are the different test case design techniques you have used?**
    
    A. These are the **methods used to design effective test cases**.
    
    The main techniques:
    
    - Equivalence Partitioning
    - Boundary Value Analysis
    - Decision Table Testing
    - State Transition Testing
13. **What are the different types of non-functional testing?
A.** 
    
    > Non-functional testing verifies the **performance, usability, reliability, and security** of the application.
    > 
    > 
    > ### Types:
    > 
    > - Performance Testing
    > - Load Testing
    > - Stress Testing
    > - Security Testing
    > - Usability Testing
    > - Compatibility Testing
    > - Reliability Testing
14. **What are the different stages in the Software Testing Life Cycle (STLC)?
A.** Stages of STLC:
    1. Requirement Analysis
    2. Test Planning
    3. Test Case Design
    4. Test Environment Setup
    5. Test Execution
    6. Test Closure
15. **What are the entry criteria and exit criteria in testing?**
    
     A. **Entry Criteria**
    
    Conditions that must be met before testing starts.
    
    Examples:
    
    - Requirements available
    - Test cases ready
    - Test environment ready
    
    ## Exit Criteria
    
    Conditions that must be met before testing is stopped.
    
    Examples:
    
    - All test cases executed
    - Critical bugs fixed
    - Test coverage achieved
16. **What is exploratory testing? When do you perform it?**
    
    **A. Exploratory testing** is a testing approach where the tester simultaneously learns the application, designs test cases, and executes them.
    
    It is performed without predefined test cases and helps identify unexpected defects.
    
    It is commonly used when a new feature is implemented, requirements are unclear, or there is limited time for formal test case creation.
    
17. **What is the difference between functional testing and non-functional testing?**
    
    **A. Functional testing** verifies that the application features work according to the requirements, such as login, add to cart, and checkout.
    
    **Non-functional testing** verifies the non-functional aspects of the application, such as performance, usability, security, and reliability.
    
    Functional testing checks *what the system does*, while non-functional testing checks *how well the system performs*.
    
18. **What is User Acceptance Testing (UAT)? Who performs it?**
    
    **A.User Acceptance Testing (UAT)** is the final level of testing where the end users or clients verify that the application meets their business requirements.
    
    It is performed by end users, product owners, or business stakeholders before releasing the application to production.
    
19. **What is the difference between retesting and regression testing?**
    
    **A.Retesting** is performed to verify that a specific defect has been fixed correctly.
    
    **Regression testing** is performed to ensure that existing functionalities are not affected by new changes, bug fixes, or feature additions.
    
    Retesting focuses on the specific defect, while regression testing focuses on the overall application stability.
    
20. **What is a test plan, and what does it contain?**
    
    A. A **test plan** is a document that defines the testing strategy, scope, objectives, schedule, and resources required for testing.
    
    It includes details such as:
    
    - Testing scope
    - Test strategy
    - Test environment
    - Resources and roles
    - Test schedule
    - Entry and exit criteria
21. **What is the difference between a test case and a test script?
A.**A **test case** is a document that contains step-by-step instructions, test data, expected results, and conditions to verify a specific functionality manually.
    
    A **test script** is an automated version of a test case written using a programming language and automation tools like Playwright or Selenium to execute tests automatically.
    
22. **What is defect leakage?
A.Defect leakage** occurs when a defect is missed during testing and is found later in production by the end users.
    
    It indicates that the defect was not detected in earlier testing phases.
    
23. **What is defect density?
A.Defect density** is the number of defects found per unit size of the software, such as per module or per lines of code.
    
    It is used to measure the quality of the software.
    
24. **What is a test summary report?
A.**A **test summary report** is a document prepared after test execution that summarizes the testing activities and results.
    
    It includes:
    
    - Total test cases executed
    - Passed and failed test cases
    - Defects found and fixed
    - Test coverage
    - Overall test status
25. **What are the different types of test environments you have used?
A.**In my project, I have used multiple environments such as:
    
    **Development environment (Dev)** – Used by developers for development and unit testing.
    
    **Test/QA environment** – Used by testers for functional and regression testing.
    
    **Pre-production (Pre-prod/UAT)** – Used for final validation before release.
    
    **Production environment (Prod)** – Live environment used by end users.
    
26. **What is the difference between alpha testing and beta testing?
A.Alpha testing** is performed internally by the testing team or employees before releasing the product to external users. It is usually done in a controlled environment.
    
    **Beta testing** is performed by a limited number of real users in a real environment before the final release.
    
    Alpha is internal testing, while Beta is external testing.
    
27. **What is risk-based testing?
A. Risk-based testing** is a testing approach where testing activities are prioritized based on the risk level of features.
    
    Features that have high business impact or high failure risk (like payment gateways or login systems) are tested more thoroughly and earlier.
    
    This helps reduce critical production issues.
    
28. **What is the difference between static testing and dynamic testing?
A. Static testing** is performed without executing the application. It includes reviewing requirements, design documents, and test cases.
    
    **Dynamic testing** is performed by executing the application to verify its functionality.
    
29. **What is a Requirement Traceability Matrix (RTM)? Why is it important?
A.** A **Requirement Traceability Matrix (RTM)** is a document that maps requirements to corresponding test cases.
    
    It ensures that every requirement has at least one test case and that no requirement is missed during testing.
    
    RTM helps ensure complete test coverage.
    
30. **How do you ensure complete test coverage in a project?
A.** Complete test coverage can be ensured by:
    - Preparing RTM to map all requirements to test cases
    - Reviewing test cases regularly
    - Performing positive and negative testing
    - Covering boundary conditions
    - Conducting regression testing before release
31. **List the different types of testing performed in the Software Development Life Cycle (SDLC).
A.** 
    
    > In the Software Development Life Cycle (SDLC), different types of testing are performed at different stages. These include:
    > 
    
    ### 🔹 Based on Testing Levels:
    
    - **Unit Testing**
    - **Integration Testing**
    - **System Testing**
    - **User Acceptance Testing (UAT)**
    
    ---
    
    ### 🔹 Based on Testing Type:
    
    **Functional Testing:**
    
    - Smoke Testing
    - Sanity Testing
    - Regression Testing
    - Retesting
    
    **Non-Functional Testing:**
    
    - Performance Testing
    - Load Testing
    - Stress Testing
    - Security Testing
    - Usability Testing
    - Compatibility Testing
32. **List the different attributes of a good test case.
A.**
    
    > A good test case should have the following attributes:
    > 
    - **Test Case ID** – Unique identifier
    - **Test Case Title** – Clear description of what is being tested
    - **Preconditions** – Conditions required before execution
    - **Test Steps** – Clear, detailed, and easy-to-follow steps
    - **Test Data** – Input values used for testing
    - **Expected Result** – Expected outcome of the test
    - **Actual Result** – Result observed after execution
    - **Status (Pass/Fail)** – Execution result