# BusTransportation
Features of the Project Online Admin Dashboard Home, Schedule, Booklist, Maintenance, Bust list, Location List, User, Manage Account. Schedule Show Entries, Search, Id Numbers, Date, Bus, Location, Departure, ETA, Availability, Price, Action, Delete, and Edit. Booked List ID Number, Ref Number, Full Name, Quantity, Amount, Status, Show Entries, Search, and Edit. Bus List ID Number, Bus Number, Bus Name, Show Entries, Edit, Delete, and Search. Location List ID Number, Terminal, City, Province State, Show Entries, Edit, Delete, and Search. User ID Number, Name, User Name, Edit, Delete, Show Entries, and Search. User Dashboard Schedule ID Number, Date, Bus, Location, Departure, ETA, Availability, Price, Book, Show Entries, and Search. Functions 1. User functions I. Booking II. Select Schedule 2. Server functions I. User functions II. select order from list of existing orders III. add items to existing order IV. remove items from existing order V. create new order VI. close order VII. total price of order (automatic) 3. Admin functions I. User functions II. Server functions III. Manage User IV. Add an admin V. Remove an admin VI. Edit bus schedule VII. Edit location VIII. Change name IX. Change id X. Edit payment method XI. Add new location XII. Remove location XIII. Add new bus XIV. Change bus name XV. Remove bus XVI. Change ticket price
International Islamic University Chittagong(IIUC)
Computer and Communication Engineering(CCE)
LAB REPORT -04
Write a report on Testing and Implementation of the System of your assigned project including:
i. Test Case Design
ii. White-Box Testing
iii. Black-Box Testing
iv. Documentation
Course Code: CCE-3508
Course Title: System Analysis, Design and Development Sessional
Submitted To
Muhammad Kamal Hossen
Associate Professor
Adjunct Faculty
International Islamic University Chittagong
Submitted by :
Samir Raihan (E191003)
Ahmed Jaser Mahdi (E191006)
Arif Hasnat (E191034)
Date of Submission: 03/01/2021
Introduction:
Software bugs will usually exist in any application or software module. However, it's not because of the programmer's carelessness or irresponsibility; it's due to the complexity. Humans have a limited capacity for dealing with complexity. The testing of the solution and implementation of our project has been shown below.
Testing
Software Testing is the process of executing a program or system with the intent of finding errors. The scope of software testing often includes examination of code as well as execution of that code in various environments and conditions. Testing stages of the project can be explained as below and system was tested for all these stages.
 Component or unit testing
-Individual components are tested independently;
-Components may be functions, objects, or coherent groupings of these entities.
 System testing
-Testing of the system as a whole. Testing of emergent properties is particularly important.
 Acceptance testing
- Testing with customer data to check that the system meets the customer's needs
Test Cases
Three sample Test Cases and result have been attached in below Table 1.1, Table 1.2 and Table 1.3 .
Test Case ID: 1
User Interface: Book ticket
Operation: Ticket Booking
Action
Input
Expected Output
Status
To show home page.
Any user can access this page and view the list of main sections provided on the platform.
User can access this page and view the list of main sections provided on the platform properly
Pass
To show Schedule page
Any user can access this page and view the list of main sections provided on the platform.
User can access this page and view the list of main sections provided on the platform properly
Pass
To Book a ticket
Any user can access this page and Book ticket by select schedule
User can access this page and Book ticket by select schedule properly.
Pass
Table 1.1 : Test Case for Test Case ID 1
Test Case ID: 2
Admin Interface: Login
Operation: System Login
Action
Input
Expected Output
Status
Type User Name
Password and click log in button.
(Correct user name and correct password )
admin
admin
Login to the System with appropriate permissions.
Pass
Type invalid User name and keep password empty then click log in button
Admin1
Display error message "Incorrect username or password.”
After pressing OK button, set cursor focus to Username input box.
Pass
Type invalid User name and type correct password then click log in button
Admin1 admin
Display error message “Incorrect username or password."
After pressing OK button, set cursor focus to Username input box.
Pass
Type valid User name and keep password empty then click log in button
admin
Display error message “Incorrect username or password “
Pass
Type valid User name and invalid password then click login button
admin
5456456
Display error message “Incorrect username or password. “Set focus on password field
Pass
Keep both user name and password empty and click login button
Display error message “Incorrect username or password." After pressing OK button, set cursor focus to username input box.
Pass
Type both user name and password invalid and click login button
adminn
adddminnn
Display error message " Incorrect username or password."
After pressing OK button, set cursor focus to Username input box.
Pass
Keep user name blank and type correct password and click login button
-
admin
Display error message “Incorrect username or password."
After pressing OK button, set cursor focus to Username input box.
Pass
Keep user name blank and type incorrect password and click login button
-
Admin1233
Display error message “Incorrect username or password."
After pressing OK button, set cursor focus to Username input box.
Pass
Table 1.2 : Test Case for Test Case ID 2
Test Case ID: 3
Admin Interface: Add/Edit/Remove Location, Schedule
Operation: Add / Modify
Action
Input
Expected Output
Status
Add New Admin
-Jaser
-123456
Data Successfully Saved
Pass
Add New Location
Bohoddarhat Bus Terminal,
Chittagong
Enable true the Save button and once press the save button, data Successfully Saved
Pass
Delete Bus
5001, S.Alam
Data Successfully Deleted
Pass
Edit Schedule Estimated Arrival Time 2022/01/3 07:00 Availability 31 Price: 250
Data Successfully Deleted
Pass
Table 1.3: Test Case for Test Case ID 3
White Box Testing:
White box testing (glass box testing) strategy deals with the internal data structures and algorithms. The tests written based on the white box testing strategy incorporate coverage of the code written, branches, paths, statements and internal logic of the code etc. These testers require programming skills to identify all paths through the software.
Types of white box testing includes code coverage (creating tests to satisfy some criteria of code coverage.), mutation testing methods, fault injection methods, static testing.
WHITE BOX TESTING: -
Techniques of white-box testing are -
1) Basic path of Testing.
2) Condition Testing.
3) Data Flow Testing.
White box testing involves the testing of the software code for the following:
 Internal security holes
 Broken or poorly structured paths in the coding processes
 The flow of specific inputs through the code
 Expected output
 The functionality of conditional loops
 Testing of each statement, object, and function on an individual basis
How to perform white box testing
1. Understand the source code
A tester must first know the software programming language and be familiar with secure coding practices. Security is a primary reason to test software, so the goal is to find security concerns to prevent hacker attacks and malicious code from being unknowingly injected into an application.
2. Test the software
Step two involves examining the software source code for correct flow and structure. One way to test the software is by designing and writing additional code which can then appraise the source code. A tester who has a good knowledge of code typically develops little tests each application process. Manual testing — another testing method — uses testing tools for the job.
Black box Testing:
Black box testing is testing without the knowledge of the internal workings of an application or a website. By short when a user login into a website of an application the functions are shown or available to the user are the functions of the Black box testing. In other words, it shows the output and hides how the output is shown.
In the following project, the black box is used for the user interface. In this project, online ticket booking system the focus of black box testing is on the validation of the functional requirements. It also gives abstraction from code and focuses on testing effort on the software system behavior. In addition, the Black box testing facilitates testing communication amongst modules.
BLACK BOX TESTING: - a) Black box testing relies on the specification of the system or component, which is being tested to drive test cases. b) The system in a ‘Black-Box’ whose behavior can only be determined by studying its inputs and the related outputs. c) Another name for this is Functional Testing because mathematical functions can be specified using only their inputs and outputs. d) This model is the same as that used for reliability testing. e) The key problem for the defect tester is to select inputs that have a high probability of being members of the set. In many cases, the selection of these test cases is based on the previous experience of test engineers. They use domain knowledge to identify test cases, which are likely to reveal defects. f) Objectives of Black-Box testing are to find out: 1) Incorrect or missing functions. 2) Interface errors.
3) Errors in data structure and external database access. 4) Performance errors. 5) Initialization and termination errors.
Here the black box is a function dedicated for the user. It shows the inputs of the result needed to show the user. For example-In the login page if the user inputs or selects an unavailable option then the user will face an error or it will show no data. If only and only if the user selects the valid options or inputs and valid data the system will take an entry. Also there is a bug where if the admin adds too many bus entries or locations the (Add New+) button will become inaccessible.
Table 1:
Data Sample(Admin Panel) Estimated Result Result Conclusion Username: admin' – Password: admin' -- No Entry No Entry Incorrect username or password Username: admin'# Password: admin' # No Entry Entry Login Successful Username: admin'/* Password: admin'/* No Entry No Entry Incorrect username or password. Username:' or 1=1— Password:' or 1=1-- No Entry Entry login Successful Username: ' or 1=1— Password: ' or 1=1# No Entry Entry login Successful Username: ' or 1=1--Password: ' or 1=1/* No Entry No Entry Incorrect username or password. Username: ') or '1'='1— Password: ') or '1'='1— No Entry No Entry Incorrect username or password. Username:') or '1'='1– Password: ') or '1'='1–
No Entry No Entry Incorrect username or password.
Table 2:
Data Sample Estimated Result Result Conclusion Bohoddarhat, Bus terminal entry entry Show Booking option Dampara, CTG entry entry Show Booking option 1/01/2022 No data No data
Failed
Documentation
Implementation:
The implementation phase of the project has by far been the most challenging of the phases of this project. Many hopes and dreams were shattered. Because of the significant time constraint, many functions that initially seemed trivial to implement became very time consuming to implement. Below is a list of features & functions that we intended to implement.
Features of the Project
Online Admin Dashboard Home, Schedule, Booklist, Maintenance, Bust list, Location List, User, Manage Account. Schedule Show Entries, Search, Id Numbers, Date, Bus, Location, Departure, ETA, Availability, Price, Action, Delete, and Edit. Booked List ID Number, Ref Number, Full Name, Quantity, Amount, Status, Show Entries, Search, and Edit. Bus List ID Number, Bus Number, Bus Name, Show Entries, Edit, Delete, and Search. Location List ID Number, Terminal, City, Province State, Show Entries, Edit, Delete, and Search. User ID Number, Name, User Name, Edit, Delete, Show Entries, and Search. User Dashboard Schedule ID Number, Date, Bus, Location, Departure, ETA, Availability, Price, Book, Show Entries, and Search.
Functions
1. User functions
I. Booking
II. Select Schedule
2. Server functions
I. User functions
II. select order from list of existing orders
III. add items to existing order
IV. remove items from existing order
V. create new order
VI. close order
VII. total price of order (automatic)
3. Admin functions
I. User functions
II. Server functions
III. Manage User
IV. Add an admin
V. Remove an admin
VI. Edit bus schedule
VII. Edit location
VIII. Change name
IX. Change id
X. Edit payment method
XI. Add new location
XII. Remove location
XIII. Add new bus
XIV. Change bus name
XV. Remove bus
XVI. Change ticket price
Database Table Design: - This module is consisting the different tables that are being utilized by the system. While designing the database records for the system proper care has been taken for not allowing the duplicate records and unnecessary redundancy of data.
Table 1 : booked
Table 2 : bus
Table 3 : location
Table 4 : schedule_list
Table 5: users
USER INTERFACE DESIGN
Because of the nature of our project, an intuitive graphical user interface is required. The user interface design was made by:
Language Used: PHP
Database Used: MySQL
Design Interface: Bootstrap JavaScript, HTML, Ajax, JQuery
The button on the middle is for user to book ticket. On the top right side, there are two button named home and schedule. The home button is for homepage. The schedule is for viewing bus schedules.
Homepage
Select Schedule
Confirm Ticket
Admin Interface
Online Ticket
Login
Schedule
Add New Schedule
Edit Schedule
Booked List
Bus List
Add New Bus
Edit Bus Name & No
Location
Add New Location
Administration
Edit Admin List
Summary:
This project is about designing a Bus Transportation System. In this project, we made a website by using PHP as the scripting language, HTML, CSS , JS and we used XAMPP for local host..The webpage has different options for a user to select his/her desired destination and bus. By using some simple steps, a user can easily book a bus ticket for any given location. Although, there are some bugs in the whole process but it run smoothly.
