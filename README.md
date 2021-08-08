# Online-Library-Management-System
As i created a mini project on online library magement system using HTML, CSS, PHP and JS under MCA Degree.
Library Management System



Project Report

On




ONLINE LIBRARY MANAGEMENT
SYSTEM



Submitted By:
Vikaram Pratap: -2001330140062
Abhishek Singh: -2001330140004
Satyam Kumar: -2001330140046

Team VAS

In partial fulfillment for the Mini Project of the degree of


MCA


In



Noida Institute of Engineering and Technology

Affiliated to

Dr. A.P.J. Abdul Kalam Technical University (AKTU)


AUGUST 2021












 
Library Management System


ACKNOWLEDGEMENT







We take this occasion to thank God, almighty for blessing us with his grace and taking our endeavor to a successful culmination. We extend our sincere and heartfelt thanks to our esteemed guide, Mr. Hirdesh Sharma, for providing us with the right guidance and advice at the crucial junctures and for showing me the right way. We also take this opportunity to express a deep sense of gratitude to our class Mentors, Dr. Sachin Kumar and Mr. Vijay Tiwari for their cordial support, valuable suggestions, and guidance. We extend our sincere thanks to our respected Head of the department Mr. Ritesh Rastogi, for allowing us to use the facilities available. We would like to thank the other faculty members also, at this occasion. Last but not the least, we would like to thank our friends and family for the support and encouragement they have given us during our work.




























 
Library Management System






TABLE OF CONTENTS



ABSTRACT	
1. INTRODUCTION	
1.1 PROJECT AIMS AND OBJECTIVES	
1.2 BACKGROUND OF PROJECT	
1.3 OPERATION ENVIRONMENT	
2. SYSTEM ANALYSIS	
2.1 SOFTWARE REQUIREMENT SPECIFICATION	
2.2 EXISTING VS PROPOSED	
2.3 SOFTWARE TOOL USED	
3. SYSTEM DESIGN	
3.1 TABLE DESIGN	
3.2 DATA FLOW DIAGRAM’S	
4. SYSTEM IMPLEMENTATION	
4.1 SCREEN SHOTS	
	
5. SYSTEM TESTING	
5.1 UNIT TESTING	
5.2 INTEGRATION TESTING	
6. CONCLUSION & FUTURE SCOPE	
7. REFERENCES	
	
	
	
 
Library Management System





ABSTRACT




Library management system is a project which aims in developing a computerized system to maintain all the daily work of library. This project has many features which are generally not available in normal library management systems like facility of user login and a facility of admin login. It also has a facility of admin login through which the admin can monitor the whole system. It has also a facility where student after logging in their accounts can see list of books issued and its issue date and return date.

Overall, this project of ours is being developed to help the students as well as staff of library to maintain the library in the best way possible and reduce the human efforts.





























 
Library Management System






CHAPTER 1

INTRODUCTION




This chapter gives an overview about the aim, objectives, background, and operation environment of the system.


1.1 PROJECT AIMS AND OBJECTIVES

The project aims and objectives that will be achieved after completion of this project are discussed in this subchapter. The aims and objectives are as follows:

•	Online book issue
•	Request column for librarian for providing new books
•	Student login page where student can find books issued by him/her and date of return.
•	A search column to search availability of books






























 
Library Management System


1.2 BACKGROUND OF PROJECT

Library Management System is an application which refers to library systems which are generally small or medium in size. It is used by librarian to manage the library using a computerized system where he/she can record various transactions like issue of books, return of books, addition of new books, addition of new students etc.

Books and student maintenance modules are also included in this system which would keep track of the students using the library and a detailed description about the books a library contains. With this computerized system there will be no loss of book record or member record which generally happens when a non-computerized system is used.


All these modules can help librarian to manage the library with more convenience and in a more efficient way as compared to library systems which are not computerized.








































 
Library Management System


1.3 OPERATION ENVIRONMENT



PROCESSOR	INTEL CORE PROCESSOR FOR BETTER
	PERFORMANCE
	
OPERATING SYSTEM	WINDOWS VISTA, WINDOWS 7 or LATER VERSION, UBUNTU
	
MEMORY	2GB RAM OR MORE
	
HARD DISK SPACE	MINIMUM 10 GB FOR DATABASE USAGE FOR
	FUTURE
	
DATABASE	MY SQL
	







































	 
Library Management System





CHAPTER 2


SYSTEM ANALYSIS



In this chapter, we will discuss and analyze about the developing process of Library Management System including software requirement specification (SRS) and comparison between existing and proposed system. The functional and non-functional requirements are included in SRS part to provide complete description and overview of system requirement before the developing process is carried out. Besides that, existing vs proposed provides a view of how the proposed system will be more efficient than the existing one.

2.1	SOFTWARE REQUIREMENT SPECIFICATION

2.1.1 GENERAL DESCRIPTION


PRODUCT DESCRIPTION:

Library Management System is a computerized system which helps

user(librarian) to manage the library daily activity in electronic format. It reduces

the risk of paperwork such as file lost, file damaged and time consuming.

It can help user to manage the transaction or record more effectively and time-

saving.


PROBLEM STATEMENT:

The problem occurred before having computerized system includes:

•	File lost

When computerized system is not implemented file is always lost because of human environment. Sometimes due to some human error there may be a loss of records.


•	File damaged When a computerized system is not there file is always lost due to some accident like spilling of water by some member on file accidentally. Besides some natural disaster like floods or fires may also damage the files.


 
Library Management System


•	Difficult to search record

When there is no computerized system there is always a difficulty in searching of records if the records are large in number.

•	Space consuming

After the number of records become large the space for physical storage of file and records also increases if no computerized system is implemented.

•	Cost consuming

As there is no computerized system the to add each record paper will be needed which will increase the cost for the management of library.

2.1.2 SYSTEM OBJECTIVES

•	Improvement in control and performance

The system is developed to cope up with the current issues and problems of library

. The system can add user, validate user and is also bug free.

•	Save cost

After computerized system is implemented less human force will be required to maintain the library thus reducing the overall cost.

•	Save time

Librarian can search record by using few clicks of mouse and few search keywords thus saving his valuable time.

•	Option of online Notice board

Librarian will be able to provide a detailed description of workshops going in the college as well as in nearby colleges

•	Lecture Notes

Teachers have a facility to upload lectures notes in a pdf file having size not more than 10mb












 
Library Management System


2.1.3 SYSTEM REQUIREMENTS

2.1.3.1 NON-FUNCTIONAL REQUIREMENTS

•	Product Requirements

EFFICIENCY REQUIREMENT

When a library management system will be implemented librarian and user will easily access library as searching and book transaction will be very faster.


RELIABILITY REQUIREMENT

The system should accurately perform member registration, member validation, report generation, book transaction and search


USABILITY REQUIREMENT

The system is designed for a user-friendly environment so that student and staff of library can perform the various tasks easily and in an effective way.


ORGANIZATIONAL REQUIREMENT

IMPLEMENTATION REQUIREMNTS

In implementing whole system, it uses html in front end with php as server side scripting language which will be used for database connectivity and the backend ie the database part is developed using MySQL.


DELIVERY REQUIREMENTS

The whole system is expected to be delivered in six months of time with a weekly evaluation by the project guide.
















 
Library Management System


2.1.3.2 FUNCTIONAL REQUIREMENTS

1. NORMAL USER


1.1 USER LOGIN

Description of	feature

This feature used by the user to login into system. They are required to enter user id and password before they are allowed to enter the system. The user id and password will be verified and if invalid id is their user is allowed to not enter the system.




Functional requirements

-user id is provided when they register

-The system must only allow user with valid id and password to enter	the system

-The system performs authorization process which decides what user level can acess to.

-The user must be able to logout after they finished using system.


1.2 REGISTER NEW USER

Description of feature

This feature can be performed by all users to register new user to create account.


Functional requirements

-System must be able to verify information

-System must be able to delete information if information is wrong

Admin Features
•	Admin Dashboard
•	Admin can add/update/ delete category
•	Admin can add/update/ delete author
•	Admin can add/update/ delete books
•	Admin can issue a new book to student and update the details when student return book
•	Admin can search student by using their student ID
•	Admin can also view student details
•	Admin can change own password



 
Library Management System


Students-

•	Student can register yourself and after registration they will get student
•	After login student can view own dashboard.
•	Student can update own profile.
•	Student can view issued book and book return date-time.
•	Student can also change own password.
•	Student can also recover own password.

2.1.4 SOFTWARE AND HARDWARE REQUIREMENTS

This section describes the software and hardware requirements of the system 2.1.4.1 SOFTWARE REQUIREMENTS

•	Operating system- Windows 10 is used as the operating system as it is stable and supports more features and is more user friendly

•	Database MYSQL-MYSQL is used as database as it easy to maintain and retrieve records by simple queries which are in English language which are easy to understand and easy to write.

•	Development tools and Programming language- HTML is used to write the whole code and develop webpages with CSS, java script for styling work and php for sever side scripting.


2.1.4.2 HARDWARE REQUIREMENTS

	Intel core i5 7th generation is used as a processor because it is fast than other processors an provide reliable and stable and we can run our pc for longtime. By using this processor, we can keep on developing our project without any worries.

	RAM 4 GB is used as it will provide fast reading and writing capabilities and will in turn support in processing
















 
Library Management System


2.2	EXISTING VS PROPOSED SYSTEM



i.	Existing system does not have any facility of teacher’s login or student login whereas proposed system will have a facility of student login as well as teacher’s login

ii.	Existing system does not have a facility of online reservation of books whereas proposed system has a facility of online reservation of books

iii.	Existing system does not have any facility of online notice board where description of workshops happening in our college as well as nearby colleges is being provided.

iv.	Existing system does not have any option of lectures notes uploaded by teachers whereas proposed system will have this facility

v.	Existing system does not have any facility to generate student reports as well book issue reports whereas proposed system provides librarian with a tool to generate reports

vi.	Existing system does not have any facility for book request and suggestions where as in proposed system after logging in to their accounts student can request books as well as provide suggestions to improve library




























 
Library Management System





2.3	SOFTWARE TOOLS USED

The whole Project is divided in two parts the front end and the	back end.

2.3.1 Front end
The front end is designed using of HTML, Php, CSS, Java Script

•	HTML- HTML or Hyper Text Markup Language is the main markup language for creating web pages and other information that can be displayed in a web browser.HTML is written in the form of HTML elements consisting of tags enclosed in angle brackets (like <html>), within the web page content. HTML tags most come in pairs like <h1> and </h1>, although some tags represent empty elements and so are unpaired, for example <img>. The first tag in a pair is the start tag, and the second tag is the end tag (they are also called opening tags and closing tags). In between these tags web designers can add text, further tags, comments, and other types of text-based content. The purpose of a web browser is to read HTML documents and compose them into visible or audible web pages. The browser does not display the HTML tags but uses the tags to interpret the content of the page.HTML elements form the building blocks of all websites. HTML allows images and objects to be embedded and can be used to create interactive forms. It provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items. It can embed scripts written in languages such as JavaScript which affect the behavior of HTML web pages.


•	CSS- Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document written in a markup language. While most often used to style web pages and interfaces written in HTML and XHTML, the language can be applied to any kind

of XML document, including plain XML, SVG and XUL. CSS is a cornerstone specification of the web and almost all web pages use CSS style sheets to describe their presentation.CSS is designed primarily to enable the separation of document content from document presentation, including elements such as the layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification


 
Library Management System



of presentation characteristics, enable multiple pages to share formatting, and reduce complexity and repetition in the structural content (such as by allowing for table less web design).CSS can also allow the same markup page to be presented in different styles for different rendering methods, such as on-screen, in print, by voice (when read out by a speech-based browser or screen reader) and on Braille-based, tactile devices. It can also be used to allow the web page to display differently depending on the screen size or device on which it is being viewed. While the author of a document typically links that document to a CSS file, readers can use a different style sheet, perhaps one on their own computer, to override the one the author has specified. However, if the author or the reader did not link the document to a specific style sheet the default style of the browser will be applied.CSS specifies a priority scheme to determine which style rules apply if more than one rule matches against a particular element. In this so-called cascade, priorities or weights are calculated and assigned to rules, so that the results are predictable.

•	JAVA SCRIPT- JavaScript (JS) is a dynamic computer programming language. It is most used as part of web browsers, whose implementations allow client-side scripts to interact with the user, control the browser, communicate asynchronously, and alter the document content that is displayed. It is also being used in server-side programming, game development and the creation of desktop and mobile applications. JavaScript is a prototype-based scripting language with dynamic typing and has first-class functions. Its syntax was influenced by C. JavaScript copies many names and naming conventions from Java, but the two languages are otherwise unrelated and have very different semantics. The key design principles within JavaScript are taken from

the Self and Scheme programming languages. It is a multi-paradigm language, supporting object-oriented, imperative,

and functional programming styles. The application of JavaScript to use outside of web pages—for example, in PDF documents, site-specific browsers, and desktop widgets—is also significant. Newer and faster JavaScript VMs and platforms built upon them (notably Node.js) have also increased the popularity of JavaScript for server-side web applications. On the client side, JavaScript was traditionally implemented as


 
Library Management System



an interpreted language but just-in-time compilation is now performed by recent (post-2012) browsers.

•	PHP- PHP is a server-side scripting language designed for web development but also used as a general-purpose programming language. PHP is now installed on more than 244 million websites and 2.1 million web servers. Originally created by Rasmus Leadoff in 1995, the reference implementation of PHP is now produced by The PHP Group. While PHP originally stood for Personal Home Page, it now stands for PHP: Hypertext Preprocessor, a recursive backronym code is interpreted by a web server with a PHP processor module, which generates the resulting web page: PHP commands can be embedded directly into an HTML source document rather than calling an external file to process data. It has also evolved to include a command-line interface capability and can be used

in standalone graphical applications. PHP is free software released under the PHP License. PHP can be deployed on most web servers and also as a standalone shell on almost every operating system and platform, free of charge.

 

2.3.2 Back end
The back end is designed using MySQL which is used to design the Database. 


	MYSQL- MySQL ("My S-Q-L", officially, but also called "My Sequel") is (as of July 2013) the world's second most widely used open-source relational database management system (RDBMS). It is named after co-founder Michael Wideners daughter, My. The SQL phrase stands for Structured Query Language. The MySQL development project has made its source code available under the terms of the GNU General Public License, as well as under a variety

of proprietary agreements. MySQL was owned and sponsored by a single for-profit firm, the Swedish company MySQL AB, now owned by Oracle Corporation

. MySQL is a popular choice of database for use in web applications and is a central component of the widely used LAMP open-source web application software stack (and other 'AMP' stacks). LAMP is an acronym for "Linux, Apache, MySQL, Perl/PHP/Python." Free-software-open-source projects that require a full-featured database management system often use MySQL. For commercial use, several paid editions are available, and offer additional functionality. Applications which use MySQL databases


 
Library Management System



include: TYPO3, MoD, Joomla, WordPress, phpBB, MyBB, Drupal and other software. MySQL is also used in many high-profile, large-scale websites, including Wikipedia, Google (though not for searches), Facebook, Twitter, Flickr, and YouTube



























































 
Library Management System





CHAPTER 3

SYSTEM DESIGN



3.1	TABLE DESIGN


VARIOUS TABELS TO MAINTAIN INFORMATION

	Admin table

 

Table tblauthors track the details of authors
 







Library Management System


	Table tblcategory track the record of category

 

 

	Table tbalbooks for books records
 
 


 













Library Management System


	Table tblstudents for students record and student login details

 



Table tblissuedbookdetails for maintain issued book and returned book record
 
 
 
Library Management System


	Relationship between tables

















 
Library Management System








3.2	DATA FLOW DIAGRAMS



DATA FLOW DIAGRAM FOR ADMIN LOGIN







ADMIN
DATABASE




		ENTER	
ADMIN	ENTER	USERNAME	CHECK
	URL	&	VALIDITY
			
		PASSWORD	

IF VALID

ADMIN
WEB SERVER	LOGIN
PAGE

After entering to the home page of the website, Admin can choose the ADMIN LOGIN option where they are asked to enter username & password, and if he/she is a valid user then a teacher login page will be displayed.























 

Library Management System














Admin Dataflow diagram
 	 
Library Management System


DATA FLOW DIAGRAM FOR Issuing Book








	

	




	


                                  Student id
                                                              ISBN no.




























Library Management System




Data Flow Diagram for Students
 











Entity Relationship Diagram




	







                                                     	
 
Testing


 
                                   CHAPTER 4

SYSTEM IMPLEMENTATION






4.1.1	Screenshot for homepage
 


























Library Management System


User signup

 













Dadmin Dashboard
 











CHAPTER 5

SYSTEM TESTING







The aim of the system testing process was to determine all defects in our project. The program was subjected to a set of test inputs and various observations were made and based on these observations it will be decided whether the program behaves as expected or not. Our Project went through two levels of testing

1.Unit testing

2.integration testing



UNIT TESTING




Unit testing is undertaken when a module has been created and successfully reviewed. In order to test a single module we need to provide a complete environment i.e. besides the module we would require

•	The procedures belonging to other modules that the module under test calls

•	Nonlocal data structures that module accesses

•	A procedure to call the functions of the module under test with appropriate parameters

1.	Test For the admin module


 
Library Management System


•	Testing admin login form-This form is used for logging in of administrator of the system. In this we enter the username and password if both are correct administration page will open other wise if any of data is wrong it will get redirected back to the login page and again ask for username and password

•	Student account addition- In this section the admin can verify student details from student academic info and then only add student details to main library database it contains add and delete buttons if user click add button data will be added to student database and if he clicks delete button the student data will be deleted

•	Book Addition- Admin can enter details of book and can add the details to the main book table also he can view the books requests.






2.	Test for Student login module

•	Test for Student login Form-This form is used for logging in of Student. In this we enter the library, username, and password if all these are correct student login page will open otherwise if any of data is wrong it will get redirected back to the login page and again ask for library, username and password.

•	Test for account creation- This form is used for new account creation when student does not fill the form completely it asks again to fill the whole form when he fills the form fully it gets redirected to page which show waiting for conformation message as his data will be only added by administrator after verification.

3.	Test for teacher login module-

•	Test for teacher login form- This form is used for logging in of teacher. In this we enter the username and password if all these are correct teacher login page will open otherwise if any of data is wrong it will get redirected back to the login page and again ask for username and password.



 
Library Management System






INTEGRATION TESTING


In this type of testing, we test various integration of the project module by providing the input

. The primary objective is to test the module interfaces to ensure that no errors are occurring when one module invokes the other module.















































 
Library Management System





CHAPTER 6

CONCLUSION & FUTURE SCOPE




This website provides a computerized version of library management system which will benefit the students as well as the staff of the library.

It makes entire process online where student can search books, staff can generate reports and do book transactions. It also has a facility for student login where student can login and can see status of books issued request as well for book or give some suggestions. It has a facility of teacher’s login where teachers can add lectures notes and give necessary suggestion to library and also add info about workshops or events happening in our college or nearby college in the online notice board.


There is a future scope of this facility that many more features such as online lectures video tutorials can be added by teachers as well as online assignments submission facility, a feature of group chat where students can discuss various issues of engineering can be added to this project thus making it more interactive more user friendly and project which fulfills each users need in the best way possible
























 
Library Management System








CHAPTER 7

REFERENCES

•	http://www.w3schools.com/html/html_intro.asp
•	https://www.w3schools.com/php/default.asp
•	https://www.w3schools.com/sql/default.asp

•	Fundamentals of software engineering by Rajib mall, PHI learning

•	Web development and application development by Ivan Byross BPB publications






































