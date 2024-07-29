# Gmail
## Revision History
Date | Description | Author | Comments |
--- | --- | --- | --- |
15.01.2024 | Test Plan Gmail | Sandu Laurentiu | version 1.0 |

### Table of Content:
##### 1. Introduction
##### 1.1 Project objective
##### 1.2 Functionalities in scope
##### 1.3 Functionalities and tests out of scope
##### 2. Test process
##### 2.1 Test planning
##### 2.2 Test analysis
##### 2.3 Test design
##### 2.4 Test implementation
##### 2.5 Test execution
##### 2.6 Test closure
##### 2.7 Test monitoring and control
##### 3. Test deliverables
##### 3.1 Test plan
##### 3.2 Test conditions
##### 3.3 Test cases
##### 3.4 Daily test summary reports
##### 3.5 Traceability matrix
##### 3.6 Test case results
##### 3.7 Bugs report
##### 3.8 Test completion report

### 1. Introduction
##### The Gmail project aims to provide its users with an accessible, secure, and user-friendly email platform.
##### This release will have limited features. Over a period of time, new and new functionalities will be added to the site.

### 1.1 Project Objective
##### We need to raise the trust in the quality of the project as high as possible before releasing it to customers.

##### Application under test: [Open here](https://mail.google.com/mail/u/0/#inbox)
##### Documentation: [Open here](https://support.google.com/mail/?hl=en#topic=3394151)

### 1.2 Functionalities in scope

##### - All features which are defined in Gmail business requirements will be tested using the following testing types: functional testing, system testing, acceptance testing, components testing, compatibility testing, User Interface (UI) Testing, Mobile Responsiveness Testing.
##### - The Gmail Web and Mobile application will be tested on the latest versions of Mozilla, Microsoft Edge and Chrome browsers.
##### - Usability Testing 

### 1.3 Functionalities and tests out of scope

##### - Non-functional testing like stress, performance is beyond scope of this project.
##### - Automation testing is beyond scope.
##### - Compatibility Testing for Specific Browsers
##### - Security Penetration Testing
##### - End-to-End Testing
##### - Localization Testing
##### - User Acceptance Testing
##### - Third-Party API Testing

### 2. Test process

### 2.1 Test planning

Roles | Responsibilities | 
------- | --- |
Laurentiu S. -QA junior | Will test the following modules: Manage your Gmail account, Read & organize emails, Settings, Write an email, Gmail - User Interface Testing |

### Entry criteria:
##### - Roles and responsibilities for the project allocated.
##### - Functional business specifications are defined.
##### - Project plan is approved
##### - Risks are identified and planned for

### Exit criteria:
##### - 100% of tests are executed.
##### - 90% of tests are passed.
##### - No Critical issues have Open status.
##### - Update tests are 100% passed (update tests will not generate other new issues that impact the application)
##### - Exploratory testing was performed on an Admin module.

### Risks:
#### Project Risks
#### Stress conditions might impact the web application
#### New browser might not be supported
#### Product Risks
#### Stability risks (crashes, disconnects, etc.).
#### Microsoft Edge browser might have performance issues.
#### The web page pagination could be impacted when opened on mobile devices.

### 2.2 Test analysis
##### - Analyze the business requirements to make sure that we have all the details for creating the test conditions.
##### - Write test conditions.

### 2.3 Test design
##### - All the test cases are written and reviewed.
##### - All test cases are created in Jira as test management tools.

### 2.4 Test implementation
##### - all the test data is available and reviewed (test data= email examples, password examples, employee, user with admin role)
##### - This test run includes only regression testing in which we will run tests that have the highest priority, this will be our main priority.
##### - Create the test suites (Cycle summary)

### 2.5 Test execution
##### - The tests will be executed on the latest versions of browsers: Chrome, Mozilla Firefox, Microsoft Edge. If time will be available, we will extend tests on other browsers.
##### - Bugs (defects) will be created based on the failed test cases.
##### - The full regression testing will be done after the new application changes.
##### - Retesting will be done after a bug fix.

### 2.6 Test closure
##### - At least 90% of tests are passed.
##### - No Critical issues have Open status.

### 2.7 Test monitoring and control
##### - Status reports will be generated to reflect the current status of the testing process.
##### - In case of major problems, control measures will be taken.

### 3. Test deliverables
![Capture](https://github.com/user-attachments/assets/ba1893c1-f7d3-477f-9517-ba15ab63a079)
![Capture2](https://github.com/user-attachments/assets/be0b897f-5805-4cc6-a52a-19d711caf32e)
![Capture3](https://github.com/user-attachments/assets/01d92457-8a8d-46f7-9a05-6e2984c51154)

#####   Schedule
##### - we have 10 days of testing
##### - we have 30 test tests
##### - in order to finish the regression run we would need to run an ~ of 3 tests/day
