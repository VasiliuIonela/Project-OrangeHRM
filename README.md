# Project-OrangeHRM
Application under test: https://opensource-demo.orangehrmlive.com/web/

 Application Documentation:https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf
 
**The final project will be split into 2 sections:** [Testing section](https://github.com/VasiliuIonela/Project-OrangeHRM/edit/main/README.md#1-testing-section) **and** [SQL section](https://github.com/VasiliuIonela/Project-OrangeHRM/edit/main/README.md#2-sql-section).

Tools used: JIRA, Zephyr Squad.

# Functional specification

The below Epic and Stories were created in JIRA and describe the functional specifications of the Job module in the Admin account, for which the final project is performed upon.

![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/jobModule.jpeg)
![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/job%20titles.jpeg)
![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/pay%20grade.jpeg)
![image 1](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/employment%20status.jpeg)
![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/job%20categories.jpeg)
![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/workShifts.jpeg)

# 1 Testing Section
## 1.1 Test Planning
The Test Plan is designed to describe all details of testing for the Job module in the Admin account, from the OrangeHRM Application. This Plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
### 1.1.1 Roles asigned to the project and persons allocated
* Project manager:
* QA Lead:
* QA Tester: Ionela Vasiliu
### 1.1.2 Entry criteria defined
* All test hardware platform have been successfully instaled, configured and functioning properly.
* All the necessary documentation, design and requirements information is available(that will allow testers to operate the system and judge the correct behaviour).
* Functional specifications are defined.
* Roles needed for the project are allocated.
* QA testers have completely understood the requirements.
* Test scenarios, test cases were reviewed.
* Initial project risks were detected and mitigated.
### 1.1.3 Exit criteria defined
* A certain level of requirements coverage has been achieved.
* All tests have been executed.
* No high priority or severe bugs are left outstanding.
* All resolved bugs have been re-tested and appoved by the QA team.
* All high-risk areas have been fully tested, with only minor residual risks left outstanding.
* The schedule has been achieved.
### 1.1.4 Test scope
* Tests in scope: The scope of this project is limited to the testing of the features in the succeeding sections of this document. All the features of Job module which were defined in software requirements specifications need to be tested.
* Tests out of scope: Non-functional testing like performance, security testing, integrations of the Job module with other modules, compatibility testiong is beyond scope of this project.
### 1.1.5 Risks detected
* Risks project: lack of experience of the QA team, short deadline of Zephyr Squad trial,
* Risks product:
### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.
## 1.2 Test monitoring and control
Periodic reports were generated to reflect the current status of the testing process, in case of major problems, control measures could be taken.
The following status report was generated after
## 1.3 Test Analysis
The testing process will be executed, based on the requirements sent by the client, for the account of Manager modules. The following test conditions were found:
**Test conditions:**
* Verify if you can add an entry in the Job titles field
* Verify the Save button functionality after you have entered valid data in the mandatory fields.
* Verify the Save button functionality when the fields are left blank.
* Verify the delete functionality by clicking on the check box next to the Job Title name.
* Verify if you can access job title details by clicking on the name of Job Title.
* Verify if you can add a pay grade.
* Verify the save button functionality when mandatory field is completed with credentials.
* Verify the save button functionality when field is left blank.
* Verify the add curency functionality 
* Verify the edit functionality of the Currency by clicking on the currency name.
* Verify the delete functionality of a  Pay Grade.
* Verify the add emplyment stasus functionality.
* Verify the save button functionality when filed is completed.
* Verify the save button when field is left blank.
* Verify you can edit emplyment status by clicking the empolyment status name
* Verify the delete functionality of an Emplyment status by clicking on the check box next to employment name.
* Verify you can add a job category.
* Verify the save button functionality when field is completed.
*  Verify the save button functionality when field is left blank.
*  Verify if you can access job category details by clicking on the job category name.
*  Verify the delete functionality by clicking on the check box next to job category name.
*  Verify if you can add work shifts.
*  Verify the save button functionality when field is left blank.
*  Verify the save button functionality when field is completed.
*  Verify the delete functionality by clicking on the check box next to work shifts name.
## 1.4 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are 
**Test cases:**



bug job title details cannot be aceesed. the nanme isn't clickable
currency name isn't clickable
emplyment name isn't clickable
job category name isn't clickable
Shift name doesn't appear as mandatory
## 1.5 Test Implementation
Testing environment is up and running:https://opensource-demo.orangehrmlive.com/web/
Access to the testing environment is given: Username : Admin | Password : admin123
Cycle summary was created.
Test cases were added to the cycle summary.

## 1.6 Test execution
* Test cases are executed on the created test Cycle summary:
* Bugs have been created based on the failed tests. The complete bug reports can be found here:
* Full regression testing is needed after the bugs are fixed.
## 1.7 Test Completion

# 2 SQL Section

