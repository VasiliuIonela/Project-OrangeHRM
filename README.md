# Project-OrangeHRM
Application under test: [orangehrm](https://opensource-demo.orangehrmlive.com/web/).

 Application Documentation:[documentation](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf).
 
**The final project will be split into 2 sections:** [Testing section](https://github.com/VasiliuIonela/Project-OrangeHRM/edit/main/README.md#1-testing-section) **and** [SQL section](https://github.com/VasiliuIonela/Project-OrangeHRM/edit/main/README.md#2-sql-section).

Tools used: JIRA, Zephyr Squad.

# Functional specification

The below Stories were created in JIRA and describe the functional specifications of the Job module in the Admin account, for which this project is performed upon: [Stories]

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
* Tests out of scope: Non-functional testing like performance, security testing, integrations of the Job module with other modules, compatibility testing is beyond scope of this project.
### 1.1.5 Risks detected
* Risks project: lack of experience of the QA team, short deadline of Zephyr Squad trial.
* Risks product: data privacy risks, compliance risks.
### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.
## 1.2 Test monitoring and control
Periodic reports were generated to reflect the current status of the testing process, in case of major problems, control measures could be taken.
The following status report was generated, to view the actual progress:

![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/daily%20test%20report.jpeg)

## 1.3 Test Analysis
The testing process will be executed, based on the requirements sent by the client, for the account of Manager modules. The following test conditions were found:
**Test conditions:**
* Verify  that a new  entry in the Job titles field can be added.
* Verify the Save button functionality for adding job title, when required fields are left blank.
* Verify that a Job Title can be deleted when clicking on the check box next to Job Title name.
* Verify if you can access job title details by clicking on the name of Job Title.
* Verify that a pay grade can be added by filling in mandatory fields with correct dates.
* Verify the Save button  functionality for adding pay grade, when required field Name is left blank.
* Verify that the currency, for a Pay Grade created, can be defined.
* Verify the edit functionality of the Currency by clicking on the currency name.
* Verify the delete functionality of a  Pay Grade.
* Verify the add employment status functionality when mandatory fields are completed with valid data.
* Verify the save button functionality when fields are left blank in Add Emplyment Status.
* Verify you can edit employment status by clicking the empolyment status name.
* Verify the delete functionality of an Emplyment status by clicking on the check box next to employment status name.
* Verify you can add a job category when required field is completed.
*   Verify that a job category cannot be added when required field is left blank.  
*  Verify if you can access job category details by clicking on the job category name.
*  Verify the delete functionality by clicking on the check box next to job category name.
*  Verify if you can add work shifts when fields are completed.
*  Verify that a work shift cannot be added when fields are left blank.
* Verify that a work shift details can be accessed when clicking on its name.
*  Verify the delete functionality by clicking on the check box next to work shifts name.
## 1.4 Test Design
Functional test cases were created in Zephyr Squad. 

![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/test%20cases.jpeg)

The test cases with steps can be viewed here: [test cases](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/ZFJ-issue-export-04-27-2023-242ac113-0001%20(2).xlsx).

## 1.5 Test Implementation
* Testing environment is up and running:https://opensource-demo.orangehrmlive.com/web/
* Access to the testing environment is given: Username : Admin | Password : admin123
* Cycle summary was created.
* Test cases were added to the cycle summary.
![image](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/cycle%20summary.jpeg)

## 1.6 Test execution
* Test cases are executed on the created test Cycle summary:

* Bugs have been created based on the failed tests:

* job title details cannot be accessed by clicking on the Job Title name: the name isn't clickable.
* currency details cannot be accessed by clicking on it: name isn't clickable.
* Edit details of employment name cannot be accessed by clicking on it: name isn't clickable.
* job category details cannot be accessed by clicking on it: name isn't clickable.
* work Shifts details cennot be accessed by clicking on name.
* Shift Name is missing the '*'  as required field.

The complete bug reports can be found here: [bug reports](https://github.com/VasiliuIonela/Project-OrangeHRM/blob/main/bugs-hrm.pdf).

* Full regression testing is needed after the bugs are fixed.
## 1.7 Test Completion
* The Traceability matrix was generated and can be found here:
* Test execution chart was generated:
* The final report shows that: 
* A total number of 22 test cases were planned for execution and all of them were executed.


# 2 SQL Section

