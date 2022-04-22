<head>
<link rel="stylesheet" href="github.css">
 </head>
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2022** 
<h3 align='center'>Introduction to Linux & Installing Ubuntu</h3>

<p align="justify">Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.</p>

- Download the linux distribution of your choice.
- Creating Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8, F2 etc.)
- Select your boot device in boot menu.
- Select Install Ubuntu then Click Noraml Installation.
- Select where to install alongside window or Erase disk or something else.
- Then Click next and start ubuntu installation.
- For More detail about Installation Guide [Click here](https://phoenixnap.com/kb/install-ubuntu-20-04)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Feb-2022** 
<h3 align='center'>Introduction to LAMP Stack</h3>

<p align="justify">The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:</p>

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Feb-2022**
<h3 align='center'>Run Cgi Script</h3>

<p align="justify">CGI stands for Common Gateway Interface. CGI defines a standard way in which information may be passed to and from the browser and server. Any program or script that can process information according to the CGI specification can, in theory, be used to code a CGI script.</p>

- Create a cgi scirpt.
- Run it on Localhost using Apache Server.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Feb-2022**
<h3 align='center'>Image to video</h3>

- Create a python Script.
- install pip,Image-MagicK on your system.
- goto ---- /etc/ImageMagick-6/policy.xml file. 
- Comment out line "policy domain="path" rights="none" pattern="@*" 
- Run the script by using python3 filename.py.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Feb-2022**
<h3 align='center'>Introduction to frappe</h3>

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.</p>
#### Why Frappe?
<p align="justify">The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.</p>

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Feb-2022**
<h3 align='center'>Creating App and Site & run on local server in Frappe</h3>

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2022**
<h3 align='center'>Introduction to Github Pages</h3>

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Feb-2022** 
<h3 align='center'>Introduction to Reveal.JS, Pandoc, Use of Markdown in Reveal.js</h3>

- What is Reveal.JS, Pandoc, Use Markdown in Reveal.js.
- Creating Presentation in Reveal.JS using Markdown only.
- Learn how to show presentation on Local machine.
- Converting .md file into .pdf file using Pandoc.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-Feb-2022** 
<h3 align='center'>Introduction to Docker, Virtual Machine and ERPNext</h3>

**What is Docker?**
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up
time.</p>
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>
- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

**What is ERPNext?**
<p align="justify">ERPNext is a full-featured business management solution that helps SMEs to record all their business transactions in a single system. With ERPNext, SMEs can make informed, fact-based, timely decisions to remain ahead in the competition. It serves as the backbone of a business adding strength, transparency, and control to your growing enterprise.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Feb-2022** 
<h3 align='center'>Installing ERPNext in Frappe-bench</h3>

- If Frappe-bench installed in system follow second method otherwise you will get error.
- Installion done with two manner 
- By Adduser in linux
- And create Erpnext app and site in frappe-bench Diretory.
- For installation steps [Click here](https://github.com/D-codE-Hub/ERPNext-installation-Guide/blob/main/README.md). 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Feb-2022** 
<h3 align='center'>Introduction to Selenium, Budibase, Coding standard for program</h3>
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- <p align="justify">With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.</p>
- <p align="justify">How to write code in Any script so that it can easily read by other programmer who contribute to your project, take variable name which should be relevant with its function.</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Feb-2022** 
<h3 align='center'>Try to Solve error redis-server during Installation</h3>
**error while loading shared libraries: libatomic.so.1: cannot open shared object file: No such file or directory**
- sudo apt purge libatomic1.
- install houncho  if file is missing.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Feb-2022** 
<h3 align='center'>Introduction to Education module in Erpnext</h3>
<p align="justify">The Education domain in ERPNext is designed to meet requirements of any organization which imparts knowledge and believe in doing so in an organized fashion. It has already been used at schools, colleges and even in private firms.
It helps you to effectively manage administration and allows you to focus on what is most important for your institute, to educate!</p>
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Feb-2022** 
<h3 align='center'>Introduction to Jinja Templating</h3>
<p align='justify'>Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Feb-2022** 
<h3 align='center'>Trying to fetch data from database using Jinja Templating</h3>
- Write a Python Script for establish connection with Mariadb.
- Still it gives permission error try to solve it.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Feb-2022** 
<h3 align='center'>Working with server</h3>
- Resetting the password of server.
- Trying to install Erpnext on server.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Feb-2022** 
<h3 align='center'>Mysql Administration, Converting pdf to md file</h3>
- Today I created a new doctype in erpnext with different options
- then learned about the administration concept of database
- Converting pdf file to md and applying changes using markdown.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Feb-2022** 
<h3 align='center'>Add new user in ubuntu</h3>
- Add new user in ubuntu.
- trying to give access of database to other user.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Feb-2022** 
<h3 align='center'>How to use ssh</h3>
- Login to Server, Try to help other member to install ldap on server.
- Apply different permission related queries on database for different user.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Feb-2022** 
<h3 align='center'>Learning about how to import data in erpnext from csv file</h3>
- Try to import data in erpnext app throught csv file.
- Apply pagination in erpnext webpage.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Feb-2022** 
<h3 align='center'>Import Data in Mysql</h3>
- Try to import data in MariaDB throught csv file.
- Learning the concept of permission on Server.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Feb-2022** 
<h3 align='center'>Creating Web page in ErpNext</h3>
- Creating Static Webpage on Erpnext.
- Learning Frappe School Module.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Mar-2022** 
<h3 align='center'>Learn Module from Frappe School</h3>
- Creating new site with new app.
- Creating Doctype and linking doctype with other.
- Learn Jinja Script for frappe doctypes. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 3-Mar-2022** 
<h3 align='center'>Learn Meeting App</h3>
- Understand the structure of meeting app.
- Understand the javascript code and python code of meeting app.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 4-Mar-2022** 
<h3 align='center'>Presentation and discussion of meeting app</h3>
- Telling about the importance of doctype in Frappe-Framework.
- Discuss with all team how it works and how we create new custom app.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Mar-2022** 
<h3 align='center'>Creating own Noticeboard app</h3>
- First create App and install it on website.
- Create Doctype according to structure discussed in team.
- Provide it web view.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Mar-2022** 
<h3 align='center'>Customize Noticeboard app</h3>
- Writing code to show correct date format eg. March 7, 2022.
- Writing code to show the name of user who upload the notice.
- Making its view user friendly in form and webpage both.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Mar-2022** 
<h3 align='center'>Learning about built in Note Doctype</h3>
- Today I'm Differentiate between Noticeboard app and inbuilt note app.
- Trying to understand note doctype functionality.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Mar-2022** 
<h3 align='center'>Learning about Workflow</h3>
- Today I'm learning Workflow in ErpNext.
- Understand how to pass control to different manager.
- Trying to implement Purchase order list and trying to approve it from purchase manager and material manager.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Mar-2022** 
<h3 align='center'>Working with Dynamic pages in Frappe</h3>
- First I need to create www directory in any Frappe app.
- Then I need to create two files Python file for fetching data from database.
- Other file is html file in which i use jinja template to show record on webpage.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Mar-2022** 
<h3 align='center'>Trying to add pagination on Dynamic page</h3>
- First try to control send data to python file from html file.
- But this won't work then i create post on discuss Erpnext where i get answer and trying to use javascript.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-Mar-2022** 
<h3 align='center'>Learning about Fee Module in Erpnext</h3>
- Here I get details how to create new fees for student.
- Learning Different prerequisites before creating new fees.
- Like Student, Fee Category, Fee Structure etc.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-Mar-2022** 
<h3 align='center'>Creating Fees in Erpnext on server</h3>
- Creating Different Fees Categories available in school like Tution Fee, Hostle Fee etc.
- Searching how to add bus fees based on their route.
- Creating student, Enroll them in a program, Creating courses etc. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Mar-2022** 
<h3 align='center'> Creating Fee Structure</h3>
<p align="justify">Creating  new Fees structures. So while creating new fees, fees should be added automatically by selecting Fee Structure. We are trying to add an admission fee in Student form along with this we are exploring where all the records are saved so that we keep track how many fees are paid or pending. We track this record in 'Report Student fee collection' doctype. We are also trying to add a penalty on overdue fees but we find this feature is not currently available in erpnext.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-Mar-2022** 
<h3 align='center'>Solve Problem While deleting records</h3>
<p align="justify">I'm exploring how to delete such payment entries which are linked with GL Entry. For this we need to go to Account Settings and Enable a checkbox Delete Accounting and Stock Ledger Entries on the deletion of Transaction and then all such Cancelled entries deleted normally.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Mar-2022** 
<h3 align='center'>Add Frappe app in repository</h3>
- First I go through the git documentation, so that every thing done properly.
- In add on I'm finding a command how to add repositiory from terminal to github.
- After doing task completely I made documentation on github pages so that it help other team-members
- For Documentation [Click here](https://vishal78626.github.io/Add-Frappe-app-in-GitRepo/) 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Mar-2022** 
<h3 align='center'>Understand the code available in Frappe</h3>
<p align="justify">Understanding the code available in all-products, then we are trying to add items in item lists, then we face problem after few search then we add items in (item lists), then add item in (website item), then setting up e-commerce settings now we successfully use search, prev & next. Now we are trying to apply it in a pagination file.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Mar-2022** 
<h3 align='center'>Installing new Erpnext on server</h3>
- First we install frappe framework then install erpnext with education domain.
- After this we are collecting students and teachers data from Nankana Sahib Public School.
- Arranging data according to doctype in erpnext.  

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 23-Mar-2022** 
<h3 align='center'>Arrange naming series company wise</h3>
<p align="justify">While new applicant is registered in system by default system generate naming series. We are trying to change it company wise For eg. if we are member of company A, then naming series include A-2022-00001.</p>
For this we follow official erpnext tutorial [More Detail](https://docs.erpnext.com/docs/v13/user/manual/en/customize-erpnext/articles/company-wise-naming-series#:~:text=The%20need%20is%20to%20create,be%20SINV%2DB%2D0001.)
Using this we get error the we take reference from other discuss.erpnext where we use (.abbr.-.YYYY.-) in option of Naming Series. 
 
 <br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-Mar-2022**
<h3 align='center'>Arranging Student data</h3>
- As there are large data of students in school we need to make it correct.
- so we all divide work in team and understanding the concept of filter, concatinate etc. in excel.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-Mar-2022** 
<h3 align='center'>Learning Employee Salary module</h3>
- For Employee or Teacher salary I need to lean Payroll module in Erpnext.
- In this I learn Payroll Period, Income Tax Slab, Salary Component and Structure, Generating Salary Recipt.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Mar-2022** 
<h3 align='center'>Implementing Payroll in Erpnext</h3>
- First Create Salary Component where i create New Component type as Earning and create PF as Deduction and add base amount in condition section.
- Create Salary Structure with Earning and Deduction, Selecting account,Payroll Frequency as montly, daily, weekly etc.
- In New Salary Structure Assignment we assign employee to Salary Structure.
- After this we go to Salary slip here i need to create holiday list and assign holiday to company then we successfully generate salary slip.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-Mar-2022** 
<h3 align='center'>Payroll Entry in Erpnext</h3>
- In payroll entry we can create salary for bulk of employee.
- For payroll entry we have an attendance of employees, only then we can create payroll entry for employee.  

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-Mar-2022**
<h3 align='center'>Web Manager Vs Website Manager</h3>
- For new users we create web manger who has permission to create webpage,See on website, Search box, can't create webform.
- Website Manager can delete webpage, read webpage but cannot create, Search bar not shown.
- We assign new user web user so that they can access gne11 website with some restriction.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-Mar-2022**
<h3 align='center'>Adding New role and Give Permission to new Users</h3>
- When we got new user for allow them to create Library Management System we need to give them the access of doctype modules.
- For this we go to doctype list and create new role where new user create doctype by can't delete doctype.
- Similarly for Module we use select permission where user can select module but can't read module.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Apr-2022**
<h3 align='center'>Working with Client Script in Form</h3>
- Client Script is script in which we add some action on form so that we validate data or do other function.
- Webform script is which is done in webform while creating new webform.
- For Reference we use Web form Scripting Documentation [Click here](https://frappeframework.com/docs/v13/user/en/api/form) 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-Apr-2022**
<h3 align='center'>Sending Daily report to Student Group</h3>
- For Sending daily report in student group First we add student and Intructor in student group with batch name.
- Then we create email group and add students email where we send them email at same time.
- In Student group on view option we create new newsletter with content and add email group then we are able to send email to group of Student.
 
<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-Apr-2022**
<h3 align='center'>Trying to create Daily Daity without using email</h3>
- For this first we create a doctype.
- Trying to add permission in doctype so that only student group can access these Dairy.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-Apr-2022**
<h3 align='center'>Creating Library Management System</h3>
- As per official documentation I create Library Management App.
- Install app on site then creating doctype.
- Use Features like Naming Series, Permission Rules.
- Learn Controller methods, Doctype Features, Form Scripts.
- Adding Web view for preview Articles on web.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-Apr-2022**
<h3 align='center'>Trying to make pagination and filter on webpage</h3>
- First we are's trying to read built-in frappe file so that we can use it in webpage.
- Make changes in built in files to apply it on global in frappe.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Apr-2022**
<h3 align='center'>Making Questions based on Library Management Tutorial</h3>
- The Topics for preparing questions for trainee are Creating Apps, Sites & Doctype.
- Making mcq question's based on steps followed when creating Library management system.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Apr-2022**
<h3 align='center'>Learning bash script</h3>
- As per Questions Created for Trainee it contain different format.
- Then I need to create bash script using sed to find and replace the wrong format symbols.
- The example of sed command is 'sed 's/$ //gI' filename'. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-Apr-2022**
<h3 align='center'>Learning Human Resource Module</h3>
<p align='justify'>The Human Resources (HR) module covers the processes related to the HR department of a company. It maintains a complete employee database including contact information, salary details, attendance, performance evaluation, leaves, and appraisal records.The most important feature here is processing the payroll by using Payroll Entry to generate Salary Slips. Most countries have complex tax rules stating which expenses the company can make on behalf of its Employees.</p>
<p align='justify'>There are a set of rules for the company to deduct taxes and social security from employee payroll. ERPNext accommodates all types of taxes and their calculation.</p>

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-Apr-2022**
<h3 align='center'>Learning Permission for Human Resource & Payroll</h3>
- For Finding permission rule of HR Role we create a user in Erpnext.
- Then assign HR User role to new user and find what permissions are available.
- After this we use HR manager Role and learn its role for Human Resource & Payroll.
- We find that HR manager has more power than HR user in some case like to delete and cancel records etc. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 13-Apr-2022**
<h3 align='center'>Email Notification for every push operation</h3>
- For this we need to go inside the repository settings.
- Go to Integration section, Add email address the limitation is only two email address are used there.
- To solve this notification, We find one more solution where in commit section optional description.
- We can add the user profile name where we want to send email notification. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-Apr-2022**
<h3 align='center'>Working on Daily Dairy as per new specification</h3>
- First we create new app named Daily Dairy.
- Create new doctype under new app Daily Dairy Class1.
- Creating fields and write some code for add fields automatically.
- Now we are working on permission how to show it to only specific group.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-Apr-2022**
<h3 align='center'>Creating Daily Diary module in Notification App</h3>
- Installing Notification app on local system.
- Creating module named Daily Diary save it on notification app.
- Then push app on other team-mate github repository. 

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-Apr-2022**
<h3 align='center'>Adding app on friend Repository</h3>
- First I fork Repository in my Repository.
- Install App on another local system then made changes on notification app like adding some code and fields.
- Then again push code in my github Repository.
- Create new pull request for Repository where I Frok Repository & Merge changes in main Repository.
- But when we use desk there is no changes in desk as per changes on git, then we check the local directory changes must there but it can't refelect in frappe.
- So here we again remove app and again install app & this time chnages work properly.

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 20-Apr-2022**
<h3 align='center'>Adding Filters on doctype as per requirement</h3>
- As per requirement changes for achieve this we add filter in list-view like class-wise, subject-wise, date-wise filter.
- For creating filters on desk we need to go to Doctype.
- On click edit we need check option In List View, In Standard Filter.
- Then on save changes filters are available on desk list-view of doctype.


<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-Apr-2022**
<h3 align='center'>Adding Role and permission to Users</h3>
- When all the task done then we find Roles and permission for Daily Diary Doctype.
- For this we add new user whom we give role Student and create new role under Doctype named DocPerm Who has permission to read.
- In Daily Diary Doctype we give read permission to Student and all permission to Instructor.
- Then assign Two Role to new user 'Student' + 'Docperm' for student & 'Instructor' + 'Docperm' for Instructor.
- Also we restrict user from Modules.       

<br>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-Apr-2022**
<h3 align='center'></h3>

<br>
