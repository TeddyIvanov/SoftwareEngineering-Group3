# SoftwareEngineering-Group3
Software engineering semester project.

# ![Metadrop](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/logo2.png)
> As a team we are going to build an online infrastructure for computational social scientists, social scientist, and citizens that will facilitate and centralize our understanding of online human interaction. We will create a database that will allow metadata specification to store, share, describe, and analyze data sets. This will help solve the problem of not being able to easily access the metadata, and now scientist and citizens can easily access it via the internet.  
  
### Group 3:
Andrea McGovern  
Teddy Ivanov  
Olivia Apperson  
Soya Ouk  
Xinyi Li  
## Requirement Analysis
* [Google Drive] (https://docs.google.com/document/d/1MV1TERh4RiKYwcPS5TSN___B5Fp_3C-kzdJ5ykBqi1I/edit#) 

* [Version 1](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_1/RequirementsAnalysisV1.docx.pdf)  

* [Version 2] (https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_1/RequirementsAnalysisV2.docx.pdf)

* [Sprint 1 Version 3] (https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_1/RequirementsAnalysisV3.docx.pdf)

* [Sprint 2] (https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_2/Sprint_2_FinalProject_MetaDrop.pdf)

* [Sprint 3] (https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/RequirementsDocumentationsSprint3.docx)

* [Sprint 4] (https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint4Documentation.pdf)

* [Final] ()
  
Develop a full requirements analysis (“REQS”) for the semester.  
1. Table of Contents  
2. Project Overview  
3. The requirments analysis divided different units.   
- Actors  
- Activities   
- Use Cases  
- Functional  
- Non-Functional  
- User Requirement  
- system Requirements  
4. Class List  
5. Table List  
6. Screen Design  
7. Glossary  
8. Change Log
 
 
  
## Sprint 1

Note: Due to the fact that no code was needed for this sprint, branches were not taken and merged to master

Kickoff Meeting
Date: 10/25/16 --In class meeting (2:00pm- 3:15pm) to discuss next steps of Sprint One. All members attended. Team members reviewed Sprint milestone targets and developed drill down tasks. These tasks were distributed amongsth team members and will explained below.

Tag-Up Meeting
Date 10/30/16 --Met in Lafferre (6:00pm-11:30pm) to continue working on completing all tasks needed.

General

* Sprint Documentation (Lead:Xinyi Li, Co: Olivia Apperson)
Team members developed Sprint documentation in Markdown on GitHub. They outlined the tasks, milestones, and other relevant data needed as well as linked updated documents. 

* Complete setup of Deployment Environment (MangoDB: Teddy Ivanov, AWS: Andrea McGovern)
Team members worked together to create a database on MangoDB and utilized AWS to host the website, which is now accessible [here](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com/).


* Organize GitHub Repo (Lead: Teddy Ivanov, Co: Soya Ouk)
Team members worked together to create GitHub repo and supply any necessary documentation and code here.


Database  

* Finalize ERD (Lead: Andrea McGovern, Co:Teddy Ivanov)
Team member put final touches on detailed ERD. Added Manifest table and corresponding attributes.

* Database Creation (Lead: Teddy Ivanov, Co: Andrea McGovern)
Team members setup an account on MLab and hosted our database on Amazon Web Services. Team members created a MongoDB account and installed MongoDB on their computers. Created a database in MLab named it "swfg3" and created an admin user. Then, they connected our MLab and MongoDB using via Mongo shell.

* Implement DB, seed data for development (Teddy Ivanov)
Team member logged into the Mongo Database and started to insert dummy JSON data. Utilized Elastic File Share system.
[Mlab && MongoDB](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/MLab.png)
and
[Dummy data](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/MLabData.png)

[User Interface](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com)  

* Complete design of the user interface (Olivia Apperson)
  Task 1: Reviewed past screen designs and look for improvements

  Task 2: Created home page, upload file page, search for json files, account information page, modify document page, login page, register page, and logout page using Themefisher Bootstrap templates. Screen designs are included in modified user requirements document or can be found live [here](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com/).

* Complete design of the information architecture (Olivia Apperson)
  Task 1: Developed flow of information to implement on webpages (which clicks led to where)

  Task 2: Connected webpages to flow as designed. Information architecture can be found by navigating through the pages 
  [here](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com/). 

Testing and Documentation

[Test Case Version 1](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_1/TestingVersion1.pdf) 

* User Acceptance Test (Soya Ouk)  
  Task 1: Created google documents for user acceptance cases
  Task 2: Created google documents to test to insert files
  Task 3: Created google documents to update files and delete files.  
  
* Build Unit Test Scenarios (Soya Ouk)
  Individual tasks are each unit test scenario
  
* Describe regression testing and your regression testing plan (Soya Ouk)
  Task 1: Described regression testing
  Task 2: Created Regression testing plan

* Describe how your team will perform integration testing (Olivia Apperson)
  Task 1: MangoDB, UI, and AWS need to communicate at all times
  Task 2: When this needs to be integrated? All at once.

* Test Types (Olivia Apperson)
  Task 1: Described Tests for Verification (Login, Data Upload, Data Edits)
  Task 2: Described Tests for Validation (Login)
  
Backlog: Entering of dummy data. MangoDB is difficult to implement with File storage and requires more work (Andrea McGovern, worked several hours to accomplish this).


## Sprint 2
####Branches-Students created their own branches for this Sprint. Branches are denoted as pawprint_Sprint2.

####Meeting-November 7th, 2016
All members attended meeting starting at 4pm and ending 10pm. Met to discuss individual progress and work together to complete other tasks. Discussed Sprint goals to ensure all parts were covered. Also worked on revising Sprint 1 for redo. These tasks determined to complete in Sprint 2 were divided amongst team members and will be explained below. 

####Tag-Up Meeting-November 10th 2016
All members attended meeting starting at 6pm and ending at 9pm. Finalized changes and updates for Sprint 2. Continued working to improve Sprint 1 content.

####General

* [Sprint Documentation](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_2/Sprint_2_FinalProject_MetaDrop.pdf) 
Lead: Olivia Apperson Co: Xinyi Li
* Students worked to provide accurate and thorough documentation for Sprint 2. 

####Database
Leads: Teddy Ivanov and Andrea McGovern
* We worked together to create insert, delete, and update commands into the database and use in php scripts. These can be found in the DML folder above. 
* We met on Monday from 4-6, Wednesday from 4-6:30, and Thursday from 4-8. 
* We had to start over from scratch, and create a new ubuntu instance on AWS becasue php 7 wasnt compatible with Mongodb. It is also easier to debug on a linux server rather than a Mocrosoft one.
* We met with Jeremy during his office hours to set up the new service. He helped us download php 5, mongodb driver, and filezilla.
* We then continued working on our own to download Apache and figured out how to access the root folder with the correct permissions to host all of our files on the instance. Firebase allows you to store JSON files as well, but instead of using php we chose JavaScript. It allows to easily be able to ensure that a user is logged in cross site.  
* We met again on Friday from 2 - 8, and decided to change from a MongoDB to a Firebase database, becasuse we thought it would be easier to handle the login. Firebase is a NoSQL Json database that allows us to host our web app and helps maintain state across the domain. 
* Separate Directory found [here] (https://github.com/TeddyIvanov/SoftwareEngineering-Group3/tree/master/DML)
* Website can be found here with UI: [website](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com/)


####User Interface
  
  Stub-calls for all interactive elements on UI can be found here:[Stub Calls](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_2/subcalls.js)
  
  Lead: Soya Ouk Co: Olivia Apperson
  These include:
  * Registration
  * Files
    
   Begin UI Elements; Website can be found here with UI: [website](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com/)
   
   Lead: Olivia Apperson Co: Soya Ouk
   Pages Include:
   * Login
   * Register
   * Edit File
   * Search File
   * Upload File
   * Landing Page

####Other

Management of users/roles (User Accounts)
* Lead: Xinyi Li Co: Teddy Ivanov
* Researcher/User:
    * Logging in and out of the system 
    * Uploading metadata files to be stored in the database 
    * Search metadata files through key words
    * Download own files for use
    * Edit own metadata files
    * Delete own metadata files
* Administrators:
    * Logging in and out of the system
    * Edit metadata files by all users
    * Delete metadata files by all users
    * Search files through key words
    * Add/delete users to the system

  
####Testing and Documenation

  Link to Sprint 1 and 2 is at the top of this page

####Unfinished Tasks

* Further additions to the database will be needed but current status is on par with Sprint 2
* Further modifications and additions to the UI will be needed but current status is on par with Sprint 2
* Integration tests may need improvements 

####Log

* Updated Webpages
* Switched to Ubuntu server
* Updated Test Cases 
* Updated Documentation
* Added user/admin roles
* Added stub-calls



## REVISIONS FROM SPRINT 1

General 
* Link to Github root included in submission
* Test cases now included in Sprint 2 document

Database/UI
* ERD revised and included in Sprint 2 document
* Information architecture (flow) is included in Sprint 2 document and [here](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint_2/Sprint_2_FinalProject_MetaDrop.pdf)

Testing 
* Revised Test cases included in Sprint 2 document

* Github links with pawprints now available
## Sprint 3

####Branches
Students created new branches (pawprint_Sprint3) to commit and merge with master for this sprint 

####Meetings
* Met November 14 at 4pm to 8pm to work decide responsibilities and start on tasks.
* Met November 17th in class to work on finishing sprint 3 requirements.

####General
* Sprint documentation can be found [here](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/RequirementsDocumentationsSprint3.docx) and within this Sprint 3 Markdown

Deploy to Group Account
* Finally, Uploaded all our files to github and reorginzed them in a efficient manor. 

####User Interface (Beware of using google chrome and firefox, it stores passwords and causes our login and logout to glitch, safari works well with our page. It will need to be fixed in the future.)
* Pages were updated to correctly connect to database and to check if links were still in working condition
* The following pages were added/edited for additional features:
  * Account.html --Changed fields of user information and correctly linked Edit button
  * EditAccount.html --Added this page to allow user to edit personal information
  * Modify.html --Added a comments section for more user input
  * search.html -- Updated to go to correct page.
  * SearchResults.html -- Created a results page for editing and needs more updating.
  * app3.js --Created Javascript file to handle uploading all files to our firebase data. Doesn't display anything on website but stores them into the database. Needs more tuning and polishing.
  
####Other
* [Temporal Logic](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Temporal%20Logic%20of%20UI.docx)

* Added Data Visualizations images for descriptions on how firebase works with our data.
[Files Uploaded Into Firebase](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/FilesUploadedIntoDatabase.png)

[Inserted Info to Firebase](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/InsertedInfoToDatabase.png)

[Overall User Usage of Firebase](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/UsageOfDatabase.png)

[Users Authenication](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/UsersAuthenication.png)


####Testing and Documentation

[Test Case Version 4](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Testing_sprint3.pdf) 

* Description of user tests
* Edge cases

####User Documentation

User Documentation was structured and started. The following sections were added:
* Introduction (Olivia Apperson)
* Software and Applications needed (Andrea McGovern)
* Deployment (Andrea McGovern and Teddy Ivanov)
* End User Manual (Olivia Apperson)

####Database Update

* Met on November 14 from 7 to 9 to work on finishing the insert, update, and search quieries.
* Also worked on file uploads using a Google Cloud Storage Bucket to hold the JSON files in the database.
* Worked Novemeber 17th on fixing errors in upload and started working on delete.

###Improvements to Sprint 2

8 points were lost in Sprint Documentation
* Sprint 2 added to Requirements and Design Documentation
* Fixed all Broken links, including Stub Calls and DML, fixed
* Link to Commits added

2 points lost for Testing
* User Acceptance testing not included in Regression testing
* Verification/Validation revised

## Sprint 4

####Meetings
* Collaborated over GroupMe application in order to coordinate jobs over Thanksgiving Break. All members attended.
* Met 11/27/16 from 1:30pm-6pm to work on and complete tasks for Sprint 4. All members attended.
* Met 11/28/16 from 6pm to 10pm to work on completing tasks and modify code. All members attended.


####General
* Sprint documentation is included [here](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/Sprint4Documentation.pdf) and was submitted on 11/28/16. It is also included in the Markdown page on Github. 
* Automated Script- confused on how this should be deployed. Deployment instructions are included later in this document.

####User Interface 
* Website can be found [here](http://ec2-35-163-197-29.us-west-2.compute.amazonaws.com/)
* SearchResults.html modified toward full functionality.
* Upload JavaScript file cleaned and made more robust for easy use and understanding.
* All pages now include scripts to make sure they are accessed only when user is registered and logged in.
* All titles now uniformly Metadrop
* Added JSON only requirement for uploading documents. Popup now appears if document is accepted or not.

####Testing
* Tests elaborated from Sprint 1 and Sprint 3 can be found [here](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/testcasesprint4.docx.pdf)

####Deployment Instructions
* User Documentation can be found [here](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/METADROP-USER-MANUAL.docx%20(1).pdf) in the GitHub.
* Readme.MD includes deployment instructions. This can be found below.

####Improvements From Sprint 3
* User documentation included (shown above).
* Pages require login to be accessed. Problem resolved. Can be shown by navigating website.
* Test cases improved for integration (showing in testing section).
* Register now logs in users automatically (issue from before)
* Error messages added to login/register page to inform user
* Fixed code for login back button issue
* Uploading now displays warning messages for wrong file types and uploads files.


##Final 

Tasks completed
* Sprint 4 Revisions
* Additions of links to all necessary information
* Creation of final document

####Sprint 4 Revisions
* Documentation cleaned up for clarity -- Olivia Apperson and Xinyi Li
* Code finalized and in working condition -- Teddy Ivanov
  * Users can see all entries using the word "all" when searching
  * For other queries, searches must be exactly how they were entered into the system (See bottom section)
* Deployment instructions reworked and edited -- Soya Ouk
* Test cases revised and edited -- Andrea McGovern 


#### Deployment

1. Create an Amazon Web Service Account (AWS)
  * Choose 'Services' from the top dropdown menu
  * Click 'Launch Instance'
  * Scroll down the page, and choose the Ubuntu Server 14.04 LTS (HVM), SSD Volume Type - ami-01f05461 (this one is easier to debug issues with a MAC on terminal)
  * Choose the t2.micro (free tier)
  * Choose 'create a new key pair' from the dropdown menu
  * Name the key pair
  * Download, and save the key pair to your desktop 
  * Click 'Launch Instance'
  * Navigate to the 'EC2 Dashboard', and choose 'Running Instances' to ensure that the instance is running correctly (may need to log out of the AWS account and back in to refresh the page)
2. Then, use a file sharing system (we used both FileZilla and WinSCP) to host our website files to the root folder of the EC2 instance these files are located on GitHub in the DML folder
  * You will need the credentials from the AWS Ubuntu instance to login to the instance through the file sharing system
  * Download our files from the DML folder on GitHub to your desktop
  * To be able to get all of our file to connect to your new Firebase database you will need to change the key at the top of file in app.js to your credentials that are located within Firebase here is a picture(this will be explained in setting up the database)
  # ![Firebase](https://github.com/TeddyIvanov/SoftwareEngineering-Group3/blob/master/images/Firebase.JPG)
  * Drag and drop them from your desktop to the root folder of the EC2 intstance on the file sharing system
3. Next, set up the FireBase database by creating a FireBase account (you will need a gmail email account)
  * Click 'Create New Project' on the main page: Name the project and choose the United States from the dropdown box as the region, and then click 'Create Project'
  * Change the Authentication by going under 'Authentication' from the side bar: Choose the 'Sign-In Method' from the top menu, and then enable the 'Email/Password' opption since this is what we use for out login
  * Click 'Storage' on the menu to the left: Choose 'Rules' from the top menu, then change the allow section to 'allow read, write;', and finally click 'Public'
  * Click 'Overview' in the side menu: Click 'Add Firebase to your App', and then copy and paste it to the app.js file
  * Click Database on the side menu bar: Click Data at the top menu bar, Click the green '+', Click the next green '+', give the first one the name of 'uploads', name the next one whatever you want and add a value of whatever you want, and click 'Add'
  

#### Things that we did not get to Accomplish and Why

1. Edit Account Page: This page was not finished due to time constraints. It was put on the bottom of our list of things to accomplish, and with other finals and projects we were not able to get to it.
2. The search functionality was tricky, becasue Firebase is so new, and a NoSQL database. There was not a lot of documentation about how to implement this, and there are not SQL quieres we can run against the database. This caused our search functionality to not be able to search for multiple files at a time. It is no longer a case sensitive search, but the key words must be exact searches. The searches can not be just partial words or letters. To be more user friendly since the user will not know what is in the database to search for a file exactly as it is spelled. The user can search 'all', and all of the files in the database will be displayed. If a user decides to edit or delete one of these files they must then search for just that file.
3. To edit a document a user must first search for a document if it is not already on your desktop. After, searching download the document, and copy and paste it into the edit area to begin edits. By clicking the 'Update' button the file is updated in the database, and saved to your desktop. The delete button has also been removed from the edit page.
