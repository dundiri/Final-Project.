# Proiect-Practic-Testare-Manuala
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

Application under test: [Product Store](https://www.demoblaze.com/)



Tools used:JIRA, Zephyr Squad

**Functional specifications**

____

**Testing section**

**1.1 Test Planning**

The Test Plan is designed to describe all details of testing for the **Shopping experience** module from the ***Product Store***.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

**1.1.1 Roles assigned to the project and persons allocated**

- Project manager - Letitia Mark
- Product owner - Oana Damian
- Software developer - Pop Vasile
- QA Engineer - Adelina Lumperdean

**1.1.2 Entry criteria defined**

- smoke test passed.

- testing environment is up and running.

- functional specifications are defined

- roles needed for the project are allocated

- initial project risks were detected and mitigated

**1.1.3 Exit criteria defined**

- all website features and functionalities work without critical errors.
- all links and navigation menus are functional and lead to the intended pages.
- all text and multimedia content are reviewed and free of grammatical errors.
- images and multimedia assets are properly compressed and optimized for web use.

**1.1.4 Test scope**

 **Tests in scope:**
 All the feature which were defined in software requirement specs need to be tested: functional testing and GUI testing.

Functional Testing:

- verify that all website features and functions work as expected.
- test navigation through different pages and sections.
- check the functionality of buttons, forms, and links.
- test all input fields to ensure they accept the correct types of data.
- check for proper validation messages when incorrect data is entered.
- verify that form submission works correctly.


 Layout and Design:

- verify that the layout of the web pages is consistent and visually appealing.
- check for proper alignment of text, images, and other elements.
- test the navigation flow between different pages and sections of the website.
- verify that navigation elements such as menus and links work as expected.
- check that images and multimedia elements are displayed correctly.
- verify that the look and feel of the website are consistent across all pages.
- check that headers, footers, and other common elements are uniform.

Usability Testing:

- evaluate the user interface for intuitiveness and ease of use.
- test if users can easily accomplish their tasks on the website.

Regression Testing:

- after making changes or updates to the website, perform regression testing to ensure that existing features still work as intended.


**Tests not in scope:**
  
- performance testing and load testing are not in scope.
- also test the website on different browsers (Chrome, Firefox, Safari, Edge, etc.) to ensure compatibilit and check the website's responsiveness on various devices (desktop, tablet, mobile) are not in scope
- automation testing is not in scope.

**1.1.5 Risks detected:**

 ** Project risks:**
   
   Insufficient or misallocation of resources (including personnel, equipment, or materials) can impede project progress.
   
   Lack of experience.
   
** Product risks:**
   
The web page pagination could be impacted when opened on mobile devices with different versions of systems or rooted.

 User data (transactions) might be impacted with update tests or rather the system could potentially affect the data of users, specifically their transaction records. The impact might involve changes or modifications to the user data during or after the update tests are performed.It underscores the importance of careful testing and validation to minimize any unintended consequences on user data.

Stability risks (crashes, disconnects, etc).

**1.1.6 Evaluating entry criteria**

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.


**1.2 Test Monitoring and Control**

It will be done by generating periodic reports that reflect the current status of the test.

**1.3 Test Analysis**

The testing process will be executed based on the above requirements for the ***Shopping experience***. The following test conditions were found:
- Verify that a customer can create an user account by filling the input fields with a valid values
- Verify that if all fields are left blank an error message will be displayed.
- Verify if the user is able to log into his accountwhith valid credentials.
- Verify the Password length restriction.
- Verify that an error message appears when creating account with existing username.
- Verify that the "Category" module is functional
- Verify that the website provides an option to add the selected product to my shopping cart.
- Verify that product details are displayed when product is select.
- Verify that the user can view the contents of the shopping cart.
- Verify that the website allow me to proceed to the checkout process, where I can enter my shipping and payment information.

**1.4 Test Design**

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are: functionality testing and exploratory testing.

The test cases with steps can be viewed here: [test_cases.pdf]()

**1.5 Test Implementation**

The following elements are needed to be ready before the test execution phase begins:

 - internet connection
 - all the hardware necessary
  
**1.6 Test Execution**

 - Test cases are executed on the created test Cycle summary(or Test Run): [cycle_summary_execution.pdf]()
 - Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf]()
enter here bug titles

**1.7 Test Completion**
 - Exit criteria was evaluated and passed
 - The traceability matrix was generated and can be found here: [Traceability_matrix.csv]()
 - Test execution chart was generated, the final report shows that during this testing, all 17 test cases planned for execution were tested.
 - from the 17 tests, a total number of 3 bugs were discovered, whose priorities are: 1 – high and 2 – medium;
- the reported defects were fixed and retested;
- product risks have been reduced by upgrading the application.
 - retesting and regression testing will be done for the new version of the application.
 






