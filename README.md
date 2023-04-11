# Project-OrangeHRM
Application under test: https://opensource-demo.orangehrmlive.com/web/

 Application Documentation:https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf
 
**The final project will be split into 2 sections:** [Testing section](https://github.com/VasiliuIonela/Project-OrangeHRM/edit/main/README.md#1-testing-section) **and** [SQL section](https://github.com/VasiliuIonela/Project-OrangeHRM/edit/main/README.md#2-sql-section)

# Functional specification
The below Story was created in JIRA and describes the functional specifications of the Admin module, for which the final project is performed upon.

The Admin Module provides you full control of all settings that affect the action of your OrangeHRM implemententatyion. Through Admin Module, you can:
*  Define the company hierarchy, pay grades, work shifts, projects, memberships, qualifications etc.
*  Add other administrators and set access levels for each user.
*  Handle security issues.
*  Configure email notifications.
*  Configure language localization and date format that will be reflected throughout the whole system.
*  Enable/Disable Module display.

The Admin Module is the central control of the system and setting it up accurately is important for smooth 
operation.
The Admin Module consists of:
* **User Management:** Add multiple HR Admins who will control the system, create logins for general users 
through ESS Users.
* **Job**: Allows the HR admin to define job titles, specifications, pay grades, employment status, job categories 
and work shifts.
* **Organization:** Allows the HR admin to enter/store general company info, structure of the organization and 
locations of sites.
* **Qualifications:** Define various skills set, education background, license types, languages and memberships.
* **Nationalities:** Define different nationalities.
* **Configuration:** Configure all email notifications, language localization and enable/disable module display.
**The User Management** field allows the HR Admin to administer users by creating logins and defining privileges by assigning Users Types(Admin or ESS).

To add a system user,  go to Admin>> User Management>> Users and click “Add”(Fields that should appear: user role, status, username, employee name, passoword, confirm password.  Click “Save” once the fields are completed.

All **job** related information can be defined in this feature. The sub menu consists of the following items:
*  Job Titles: The job titles specific to the company can be defined in this option.To add an entry, go to Admin>> Job>> Job Titles and click “Add”.
*  Pay Grades: The HR Admin can define the pay grade by setting a minimum salary, maximum salary, step increase, and the 
currency to be paid in. To add an entry, go to Admin>>Job>> Pay Grades and click “Add”.
*  Employment Status: Employment Status allows you to define the status of employment employees are hired for or if they are 
terminated. To add an entry, go to Admin>> Job>> Employment Status and click “Add”.
*  Job Categories:This feature allows the HR Admin to create job categories specific to the company to aggregate job 
classifications. To add an entry, go to Admin>> Job>> Job Categories and click on “Add”
*  Work Shifts: In this feature the HR Admin can define work shifts for an individual or a group of employees. To add an 
entry, go to Admin>> Job>> Work Shifts and click “Add”.

**Organization**

All information about the organization, the structure and locations are defined here:
* General Information

Basic details of the company can be entered on this screen. To start adding information, go to Admin>> 
Organization>> General Information and click “Edit”.
* Locations

Under Locations, the HR admin can add details of sites and branches of the company. You are also able to 
track the number of employees working for a particular location once employees are tagged to the locations 
when building up the PIM Module. 
To add a location go to Admin>>Organization>>Location and click “Add”. Click “Save” once the fields are added.
* Structure

This feature allows the admin to define the hierarchy of the company by defining sub units. Since the parent 
company is already defined in the General Information, it would automatically appear in the Company 
Structure screen. 
 You need to define the company name of the parent company before you create the Company Structure.
 
 **Qualifications**
 
This feature allows you to define all information with regards to employees’ qualifications. The sub-menu 
consists of:
* Skills
* Education
* Licenses
* Languages
* Memberships

**Nationalities**

This feature allows the HR Admin to define the different nationalities that present in the company which can 
later be used in the PIM Module. Various nationalities are already pre-defined. 
To add a nationality, go to Admin>> Nationalities and click “Add”. Click “Save” once the field is added.

**Configuration**

This feature allows you to subscribe and receive notifications and to configure the parameters in setting up 
the email so notifications will be sent to relevant persons which will quicken the communication processes.
It also allows the HR admin to configure language localization for the entire system, set up a date format and 
enable/disable module display.
* Email Configuration
* Email Subscriptions
* Localization
* Modules
* 

# 1 Testing Section
## 1.1 Test Planning
The Test Plan is designed to describe all details of testing for the Admin module from the OrangeHRM Application. This Plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
### 1.1.1 Roles asigned to the project and persons allocated
* Project manager:
* QA Lead:
* QA Testers:
### 1.1.2 Entry criteria defined
* 
### 1.1.3 Exit criteria defined
### 1.1.4 Test scope
* Tests in scope:
* Tests out of scope:
### 1.1.5 Risks detected
* Risks project:
* Risks product:
* ### 1.1.6 Evaluating entry criteria
## 1.2 Test monitoring and control
## 1.3 Test Analysis
**Test conditions:**
## 1.4 Test Design
**Test cases:**
## 1.5 Test Implementation

## 1.6 Test execution
## 1.7 Test Completion
# 2 SQL Section

