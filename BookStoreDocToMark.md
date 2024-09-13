# A project report on BCA-CC-606

## “Bookstore Management System”

### Submitted to Smt. K.B. Parekh College of Computer Science-Mahuva
(Affiliated to Maharaja Krishnakumarsinhji Bhavnagar University)

![spiral model](https://github.com/KRam0n/tesztek01/blob/main/kepek/cimer.png)

**in partial fulfillment for the award of degree of BACHELOR OF COMPUTER APPLICATIONS**

Submitted by:  
- **Makwana Dhaval N.** (BCA SEMESTER-6 SEAT NO: 21260256)  
- **Baraiya Kumar K.** (BCA SEMESTER-6 SEAT NO: 21260254)  

Guided by:  
**Ashsish Pandya**  
Assistant Professor  
Smt. K.B. Parekh College of Computer Science-Mahuva  
**March - 2019**

![spiral model](https://github.com/KRam0n/tesztek01/blob/main/kepek/cimer2.png)

---

## CERTIFICATE

This is to certify that the Student **Makwana Dhaval** and **Baraiya Kumar** of Smt.K.B.Parekh College of Computer Science Mahuva have satisfactorily completed their project **BOOKSTORE MANAGEMENT SYSTEM** during the period December 2019 to March 2019 in partial fulfillment of BCA-CC-606.

---

## Acknowledgment

We have taken efforts in this project. However, it would not have been possible without the kind support and help of our Faculties. We would like to extend our sincere thanks to all of them.

We are highly indebted to K. B. Parekh College of Computer Science Mahuva for their guidance and constant supervision, as well as for providing necessary information regarding the project & their support in completing the project.

We would like to express my gratitude towards my parents & member of KBP for their kind co-operation and encouragement which help us in completion of this project. Last but not least, many thanks go to the head of the project, Mr. Ashsish Pandya whose have invested his full effort in guiding the team in achieving the goal. We have to appreciate the guidance given by other supervisor as well as the panels especially in our project presentation that has improved our presentation skills thanks to their comment and advices.

We would like to express our special gratitude and thanks to all above mentioned people for giving us such attention and time. Our thanks and appreciations also go to our colleague in developing the project and people who have willingly helped us out with their abilities.

---

## Abstract

**Bookstore Management System** is designed to build a web application that helps people find and buy books from various categories like Biography, Programming, Management, etc. This application makes it easier to buy books and provides a user-friendly interface.

Today most of the book shop is useful for shopping site. The admin have lots of paper work and they are using desktop, spread sheet like MS Excel application to manage data in soft copy about user record. In this proposed Bookstore System it will run in server and user can handle whole the registration activities.

This application maintains the centralized database so that any changes done at a location reflects immediately. This is an online tool so more than one user can login into system and use the tool simultaneously.

The aim of this application is to reduce the manual effort needed to manage transactions and historical data used in various gods owns. Also this application provides an interface to users to view the details And Design about Bookstore.

---

# Table of Contents

1. [Introduction](#introduction)  
   1.1 [Project Background](#project-background)  
   1.2 [Objectives of the project](#objectives-of-the-project)  
   1.3 [Purpose of the Project](#purpose-of-the-project)  
   1.4 [Scope of the Project](#scope-of-the-project)  
   1.5 [Applicability of the Project](#applicability-of-the-project)
   
2. [Requirement and Analysis](#requirement-and-analysis)  
   2.1 [Problem Statement](#problem-statement)  
   2.2 [Requirement specifications](#requirement-specifications)  
   2.3 [Hardware requirement](#hardware-requirement)  
   2.4 [Software requirement](#software-requirement)  
   2.5 [Planning and Scheduling](#planning-and-scheduling)
   
3. [System Design](#system-design)  
   3.1 [Overall System Design Using Designing Tools](#overall-system-design-using-designing-tools)  
   3.2 [Data dictionary](#data-dictionary)  
   3.3 [Input/Output design](#input-output-design)

4. [Testing and Implementation](#testing-and-implementation)  
   4.1 [Testing Approach Used](#testing-approach-used)  
   4.2 [Test Cases](#test-cases)  
   4.3 [Implementation Approaches](#implementation-approaches)

5. [Conclusion](#conclusion)  
   5.1 [Limitation of the System](#limitation-of-the-system)  
   5.2 [Future Scope of the System](#future-scope-of-the-system)  
   5.3 [Bibliography](#bibliography)

---

## Contents of Figures

| Figure No | Figure Name                             | Page No |
|-----------|------------------------------------------|---------|
| 1         | Planning and Scheduling                  | 14      |
| 2         | Spiral Model                             | 20      |
| 3         | Data Flow Diagram Symbols                | 25      |
| 4         | 0 Level Data Flow Diagram                | 25      |
| 5         | 1st Level Data Flow Diagram              | 26      |
| 6         | BMS Flowchart Diagram                    | 26      |
| 7         | User Flow Diagram                        | 27      |
| 8         | Use Case Diagram Symbols                 | 28      |
| 9         | User Use Case Diagram                    | 29      |
| 10        | BMS Use Case Diagram                     | 30      |
| 11        | Activity Diagram Symbols                 | 32      |
| 12        | User Activity Diagram                    | 33      |
| 13        | Login System Activity Diagram            | 34      |
| 14        | E-R Diagram Symbols                      | 35      |
| 15        | E-R Diagram for Bookstore Management System | 36   |
| 16        | BMS Home Page                            | 41      |
| 17        | BMS Selected Category                    | 42      |
| 18        | BMS Book Details                         | 43      |
| 19        | BMS Login Page                           | 44      |
| 20        | BMS Register Page                        | 45      |
| 21        | BMS Contact Us Page                      | 46      |
| 22        | BMS Cart Page Viewers                    | 46      |
| 23        | BMS Order Page                           | 47      |
| 24        | Logged in Home Page                      | 48      |
| 25        | BMS Users Book Details                   | 49      |
| 26        | BMS Users Cart Page                      | 50      |
| 27        | BMS Search Books                         | 51      |
| 28        | BMS Admin Login Page                     | 51      |
| 29        | BMS Admin Home Page                      | 52      |
| 30        | BMS Add New Category                     | 52      |
| 31        | BMS View Category                        | 53      |
| 32        | BMS Add New Books                        | 53      |
| 33        | BMS View Books                           | 54      |
| 34        | BMS Contacted List Books                 | 54      |
| 35        | BMS Users List                           | 55      |
| 36        | BMS Forget Password Page                 | 55      |
| 37        | Black Box Testing                        | 57      |
| 38        | Gray Box Testing                         | 59      |
| 39        | Test Cases 1                             | 60      |
| 40        | Test Cases 2                             | 61      |
| 41        | Test Cases 3                             | 61      |
| 42        | Test Cases 4                             | 62      |


---

# Introduction

## 1.1 Project Background

-	This Software allows the Admin to store the book details and the customer details.
-	Easier access to information like customer information and  availability.
- Provide facility of storing data to reduce the paper work.
- In Bookstore Management System Users can by a book and Admin shows their name and other background of the user.
- A  new idea about Project how Bookstore Management System works. For make a system computerized.
  
---

## 1.2 Objectives of the Project

- To reduce paperwork and create a computerized system.
- Increase operational speed and improve accuracy.
- Provide large storage for data using databases.
- Facilitate faster information retrieval, improving overall efficiency.
  
---

## 1.3 Purpose of the Project

- The main purpose of Book-store Management System is to focused on the solution of all the problems related to the paper work from the different reasons.
- It provides a facility to handle all the activities at one place. With the help of this application, admin can perform different kind of operations at the same time and place.
- Bookstore management System has an ability to keep the records safe related to Books.
- We provide the best service in our website or focuses on user choice. We will improve new feat user can easily understand and trust our system.

---

## 1.4 Scope of the Project

This system aims to:
- Reduce overtime and increase the number of records handled efficiently.
- Provide accurate search results based on specific queries.
- Allow customers to book books quickly.
- Provide flexibility to admins for database management and various tools like notepad and calculator.

---

## 1.5 Applicability of the Project

- Suitable for customers who want to purchase books anytime, anywhere.
- Admins can manage the list of books.
- The system uses a database for storing and retrieving user and book data.

# Chapter 2: Requirement and Analysis

## 2.1 Problem Statement

- Excessive paperwork.
- The process is time-consuming.
- Extra expenses in managing paper records.
- Large data storage required.
- Manual vehicle purchase and sales processes, both in cash and on finance, are difficult to manage.
- Slow information retrieval.
- Inconsistent accuracy in manual systems.
- Delays caused by the manual system.
- Difficult to search for specific records manually after a long time.
- Increase in staff workload and time wastage during tests.

---

## 2.2 Requirement Specifications

The system has two main modules:

1. **Admin Module**  
   The Admin module includes:
   - Entry of book categories.
   - Managing the category list.
   - Adding new books.
   - Viewing books.
   - Viewing messages sent by clients.

2. **Client Module**  
   The Client module includes:
   - Viewing available books.
   - Adding books to the cart.
   - Searching for books.
   - Viewing and adding items to the cart.

---

## 2.3 Hardware Requirement

- 32-bit operating system.
- Supported OS: Windows 7/8/8.1/10, Linux (Ubuntu), Mac OS.
- 350 MB RAM.

---

## 2.4 Software Requirement

- **Server**: Wamp Server.
- **Database**: MySQL.
- **Browser**: Mozilla Firefox, Google Chrome, Internet Explorer 8.0+.
- **Development Tools**: PHPMyAdmin.
- **Processor**: Dual-core processor, 2.20 GHz or above.
- **RAM**: 512 MB or more.
- **Hard Disk**: 45 MB available space required.

---

## 2.5 Planning and Scheduling

Different amounts of time may be required for each stage of the project cycle, depending on the key aspects of development. The information obtained during the requirement gathering phase provides the foundation for the analysis and design phases.

| ID  | Task Name      | Start/Finish             | Duration |
| --- | -------------- | ------------------------ | -------- |
| 1   | Analysis       | 25/12/2018 to 01/01/2019 | 8 Days   |
| 2   | Design         | 01/01/2019 to 09/01/2019 | 9 Days   |
| 3   | Coding         | 10/01/2019 to 08/02/2019 | 4 Weeks  |
| 4   | Implementation | 08/02/2019 to 12/02/2019 | 5 Days   |
| 5   | Testing        | 12/02/2019 to 17/02/2019 | 6 Days   |
| 6   | Documentation  | 18/02/2019 to 10/03/2019 | 3 Weeks  |

### *(Figure 1: Planning and Scheduling)*
The above schedule specifies the estimated time that will be required in various software development phases, considering all situational factors. Team members are technically ready accepting few days training on to get the Technology Awareness. Thus, according to calculation, it is feasible to build such solution in time. 
"The schedule will be revised at the end of each phase and updated as necessary."

---

## Brief Overview of the Technology

### Front End - HTML, CSS, Bootstrap

**HTML**  
- HTML stands for HYPER TEXT MARKUP LANGUAGE, which is most widely used language on web to develop web pages. HTML refers to the way in which Web pages (HTML documents) are linked together. Thus, the link available on a web page is called Hypertext.
- HTML was created by Berners-Lee in late 1991 but “HTML 2.0” was the first standard HTML specification which was published in 1995. HTML 4.01 was a major version of HTML and it was published in late 1999. Though HTML 4.01 version is widely used but currently we are having HTML-5 version which is an extension to HTML 4.01, and this version was published in 2012.
- As its name suggests, HTML is a Mark-up Language which means you use HTML to simply “mark-up” a text document with tags that tells a web browser how to structure it to display.
- Originally, HTML was develop with the intent of defining the structure of documents like heading, paragraph, lists, and so forth to facilitate the sharing of scientific information between researchers. Now, HTML is being widely used to format web pages with the help of different tags available in HTML.

**CSS**  
- Cascading Style Sheet is a style sheet language used for describing the presentation of a document written in a markup language Although most often used to set the visual style of web page and user interfaces written in HTML and XHTML, the language can be applied to any XML document, including plain XML, SVG and XUL, and is applicable to rendering in speech, or on other media. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications.
- CSS is designed primarily to enable the separation of document content from document presentation, including aspects such as the layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple HTML pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content.
- The CSS specifications are maintained by the World Wide Web Consortium (W3C). Internet media type (MIME type) text/css is registered for use with CSS by RFC 2318 (March 1998). The W3C operates a free CSS validation service for CSS documents 
- CSS has a simple syntax and uses a number of English keywords to specify the names of various style properties. A style sheet consists of a list of rules. Each rule or rule-set consists of one or more selectors, and a declaration block.

**Bootstrap**  
- Bootstrap is a free and open-source, front-end web frame work for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only.
- Bootstrap is modular and consists of a series of less stylesheets that implement the various components of the toolkit. These stylesheets are generally compiled into a bundle and included in web pages, but individual components can be included or removed. Bootstrap provides a number of configuration variables that control things such as color and padding of various components.
- Since Bootstrap 2, the Bootstrap documentation has included a customization wizard which generates a customized version of Bootstrap based on the requested components and various settings.
- As of Bootstrap 4, is used instead of less for the stylesheets. Each Bootstrap component consists of an HTML structure, CSS declarations, and in some cases accompanying JavaScript code.

---

### Back End - PHP, MySQL

**PHP**  
The PHP Hypertext Pre-processor (PHP) is a programming language that allows web developers to create dynamic content that interacts with databases. PHP is basically used for developing web based software applications. This tutorial helps you to build your base with PHP. PHP started out as a small open source project that evolved as more and more people found out how useful it was. Rasmus Lerdorf unleashed the first version of PHP way back in 1994.

- PHP is a recursive acronym for "PHP: Hypertext Preprocessor".
- PHP is a server side scripting language that is embedded in HTML. It is used to manage dynamic content, databases, session tracking, even build entire e-commerce sites.
- It is integrated with a number of popular databases, including MySQL, Postgre SQL, Oracle, Sybase, Informix, and Microsoft SQL Server.
- PHP is pleasingly zippy in its execution, especially when compiled as an Apache module on the Unix side. The MySQL server, once started, executes even very complex queries with huge result sets in record-setting time.
- PHP supports a large number of major protocols such as POP3, IMAP, and LDAP. PHP4 added support for Java and distributed object architectures (COM and CORBA), making n-tier development a possibility for the first time.
- PHP is forgiving: PHP language tries to be as forgiving as possible.
- PHP Syntax is C-Like.

**MySQL**

- MySQL is a database, widely used for accessing querying, updating, and managing data in databases.
- MySQL is an open source RDBMS that relies on SQL for processing the data in database. MySQL provides APIs for the languages like C, C++, Eiffel, JAVA, Perl, PHP and Python. MySQL is most commonly used for web applications and for embedded applications and has become a popular alternative to proprietary database system because of its speed and reliability. MySQL can run on UNIX, Windows and Mac OS.

---

## Project Analysis and Planning

The BMS is critical to set-up online order, customers to browse through book categories. This is a small scale project for BMS. The basic idea is that the customers can buy a book from anywhere during any time by the cash through.


### User Module

- Users can register, log in, and log out.
- View book categories and purchase books.
- Contact Admin.
- Add books to the cart and place orders.

### Admin Module

- Manage the bookstore system.
- Insert new books and manage records.

---

## Spiral Model

The **Spiral Model** combines elements of both iterative and waterfall models, with a strong focus on risk analysis. It is particularly suitable for large, high-risk projects where requirements are unclear and need to be refined over time. The model allows for incremental development and continuous refinement through multiple iterations or "spirals."

### Key Phases of the Spiral Model:

1. **Identification Phase**:
    - In the initial spiral, the business requirements are gathered and analyzed.
    - In subsequent spirals, system requirements, subsystem requirements, and unit requirements are identified and refined.
    - Regular interaction between the customer and system analyst ensures that the requirements are well understood.
    - At the end of this phase, a prototype or version of the product is deployed in the identified market for feedback and further refinement.

2. **Design Phase**:
    - Begins with a conceptual design during the baseline spiral.
    - Subsequent spirals involve detailed architectural design, logical design of modules, physical product design, and final design.
    - As each spiral progresses, the design becomes more refined based on the feedback from previous spirals and risk analysis.

3. **Construction or Build Phase**:
    - A working prototype or a Proof of Concept (PoC) is developed during the early spirals.
    - As the product matures through iterations, higher clarity on design and requirements allows for the construction of increasingly refined working models.
    - These models are shared with the customer for feedback, ensuring that the final product is aligned with customer expectations.
  
4. **Evaluation and Risk Analysis Phase**:
    - Risk analysis is a crucial element in each spiral, focusing on both technical and management risks such as schedule delays, cost overruns, or technical feasibility issues.
    - After each iteration, the customer evaluates the progress of the software, tests the build, and provides feedback.
    - Based on this feedback, the development team addresses potential risks and plans the next iteration.



### Spiral Model Process

The **Spiral Model** operates through multiple spirals, each consisting of four phases: Identification, Design, Construction, and Risk Evaluation. After completing each spiral, a new version of the product is released or further refined, depending on customer feedback and risk analysis. This cyclical process repeats until the final product is developed.

The **Spiral Model** diagram represents the cyclical nature of the development process, showing how each iteration passes through the four phases.

*(Figure 2: Spiral Model)*

![spiral model](https://github.com/KRam0n/tesztek01/blob/main/kepek/spiral.png)

### Advantages of the Spiral Model:
- **Risk Management**: The model emphasizes early identification and mitigation of risks through continuous evaluation.
- **Customer Feedback**: Frequent iterations allow for customer feedback at every stage, ensuring the final product aligns with expectations.
- **Flexibility**: The model can accommodate changes in requirements as the project progresses, making it ideal for projects with evolving needs.
- **Prototyping**: Prototyping is a core feature, allowing for testing and refining ideas early in development.
- **Scalability**: Suitable for large, complex projects that need to be developed and delivered incrementally.

### When to Use the Spiral Model:
- When project requirements are unclear or likely to change over time.
- For medium to high-risk projects where risk management is crucial.
- In long-term projects where there is a need for continuous refinement.
- When customer feedback is essential throughout the development cycle.

### Disadvantages of the Spiral Model:
- **Complexity**: Managing the spirals can be complex and requires strict oversight and careful planning.
- **Cost**: The model can be expensive due to the high emphasis on risk management and continuous iterations.
- **Risk of Continuous Iteration**: Without proper control, the project may fall into an endless loop of development and evaluation without reaching completion.

### Spiral Model in Bookstore Management System

In the development of the **Bookstore Management System**, the Spiral Model was adopted to ensure flexibility and continuous improvement based on customer feedback. Each iteration involved:
- **Risk Assessment**: Evaluating potential risks in database design, user interface development, and system performance.
- **Prototyping**: Building and refining prototypes at the end of each spiral, ensuring the system met user expectations for usability and functionality.
- **Customer Interaction**: Engaging with stakeholders at regular intervals to gather feedback and make necessary adjustments.

By using the **Spiral Model**, the project was able to handle evolving requirements, maintain focus on risk management, and incorporate customer feedback effectively, resulting in a robust and user-friendly **Bookstore Management System**.

---

# Chapter 3: System Design

## 3.1 Overall System Design Using Designing Tools

The Purpose of Design Phase is to plan a solution for problem specified by the requirements. System Design aims to identify the modules that should be in the system, the specification of those modules and how they interact with other to produce the results. The goal of the design process is to produce a model that can be used later to build that system. The produced model is called design of the system.

System Design is the process of defining the architecture, components, modules, interfaces and data for a system to satisfy specified requirements.

---

### Physical Design

The Physical Design is a graphical representation of the system’s internal and external entities and the flow of data into and out of these entities. Tools like Data Flow Diagrams (DFD), E-R Diagrams, and Use Case Diagrams are used to represent the system.

#### Data Flow Diagram (DFD)

The Data Flow Diagrams (DFD) is a graphical representation of the flow of data through an information system. Data Flow Diagrams are used by systems analysis to design information processing systems but also a way to model whole organization. The main merit of DFD is that it can provide an overview of what data a system would processes. What transformations of data are done, what data are stored and which stored data is used, and where the result is flow.

### Standard Symbols used in DFD:

| Symbol           | Name              | Function                                                |
| --- |-------------------|---------------------------------------------------------|
| --- | Data Flow         | Used to connect processes to each other. The arrowhead indicates the direction of data flow. |
| --- | Process           | Represents a transformation of input data into output data. |
| --- | Input / Output    | Indicates data entering or leaving the system.            |

- **0 Level DFD**: Represents the website flow.

  *(Figure 4: 0 Level Data Flow Diagram)*
  ![dataflow](https://github.com/KRam0n/tesztek01/blob/main/kepek/dataflow.png)

- **1st Level DFD**: Represents detailed data flow for user interactions.

*(Figure 5: 1st Level Data Flow Diagram)*
  ![flowchart](https://github.com/KRam0n/tesztek01/blob/main/kepek/flowchart.png)

*(Figure 6: BMS Flowchart Diagram)*
  ![userflow](https://github.com/KRam0n/tesztek01/blob/main/kepek/userflow.png)

---

### Use Case Diagram

A use case is a set of scenarios that describing an interaction between a user and a system.  A use case diagram displays the relationship among actors and use cases.  The two main components of a use case diagram are use cases and actors.


- **User Use Case Diagram**

*(Figure 9: User Use Case Diagram)*
  ![usecase](https://github.com/KRam0n/tesztek01/blob/main/kepek/usecase.png)

- **BMS Use Case Diagram**

  An actor is represents a user or another system that will interact with the sys

  Item you are modeling.  A use case is an external view of the system that represents some action the user might perform in order to complete a task.
  
  *(Figure 10: BMS Use Case Diagram)*
  ![userusecase](https://github.com/KRam0n/tesztek01/blob/main/kepek/userusecase.png)

---

### Activity Diagram

Activity diagrams represent the flow of activities or operations within a system. Below is a table of the standard symbols used in an activity diagram.

| Name of Symbols                      |Simbols| Description                                                                 |
|--------------------------------------|------------------------------|-----------------------------------------------------------------------------|
| **Start Symbol**                     |![symbols](https://github.com/KRam0n/tesztek01/blob/main/kepek/start.png)| Represents the beginning of a process or workflow in an activity diagram.    |
| **Activity Symbol**                  |![symbols](https://github.com/KRam0n/tesztek01/blob/main/kepek/activity.png)| Indicates the activities that make up a modeled process.                    |
| **Connector Symbol**                 |---|Shows the directional flow or control flow of the activity.                 |
| **Decision Symbol**                  |![symbols](https://github.com/KRam0n/tesztek01/blob/main/kepek/decision.png)| Represents a decision, always with at least two paths branching out.        |
| **End Symbol**                       |![symbols](https://github.com/KRam0n/tesztek01/blob/main/kepek/end.png)| Marks the end state of an activity and represents the completion of all flows.|
| **Joint Symbol/Synchronization Bar** |![symbols](https://github.com/KRam0n/tesztek01/blob/main/kepek/joint.png)| Combines two concurrent activities into a single flow.              |
| **Fork Symbol**                      |![symbols](https://github.com/KRam0n/tesztek01/blob/main/kepek/fork.png)| Splits a single activity flow into two concurrent activities.               |

*(Figure 11: Activity Diagram Symbols)*

---

### E-R Diagram

Entity-Relationship (E-R) diagrams represent entities in the system and their relationships.  
*(Figure 15: E-R Diagram for Bookstore Management System)*

## 3.2 Data Dictionary

The database structure for the system involves several tables. Below is the detailed design for each table used in the system.

##Database Design & Structure Design

Various tables used in the System are as follows:

- Admin
- Book
- Category
- Contact
- Register
- Order

Detail of all the tables with its all the fields are as below:

### Table Name: Admin
- **Primary Key**: `a_id`
- **Description**: Stores Admin login details.

| Field  | Type        | Description                      |
|--------|-------------|----------------------------------|
| a_id   | int(4)      | Used to store Admin ID           |
| a_unm  | varchar(3)  | Used to store the Admin username |
| a_pwd  | varchar(30) | Used to store the Admin password  |

---

### Table Name: Book
- **Primary Key**: `b_id`
- **Description**: Stores book details.

| Field  | Type        | Description                               |
|--------|-------------|-------------------------------------------|
| b_id   | int(10)     | Used to store Book ID                     |
| b_nm   | varchar(50) | Used to store the book name               |
| b_cat  | int(6)      | Used to store the category ID of the book |
| b_desc | longtext    | Stores the description of the book        |
| b_price| int(4)      | Used to store the price of the book       |
| b_img  | varchar(50) | Stores the image name of the book         |
| b_time | int(20)     | Stores the time the book was added        |

---

### Table Name: Category
- **Primary Key**: `cat_id`
- **Description**: Stores category names.

| Field   | Type        | Description                  |
|---------|-------------|------------------------------|
| cat_id  | int(10)     | Used to store the Category ID |
| cat_nm  | varchar(50) | Used to store the Category name|

---

### Table Name: Contact
- **Primary Key**: `c_id`
- **Description**: Stores client/user contact details.

| Field  | Type        | Description                                 |
|--------|-------------|---------------------------------------------|
| c_id   | int(4)      | Stores Contact ID of the client/user        |
| c_fnm  | varchar(100)| Stores the full name of the client/user     |
| c_mno  | int(10)     | Stores the mobile number of the client/user |
| c_email| varchar(60) | Stores the email address of the client/user |
| c_msg  | longtext    | Stores the message/query of the client/user |
| c_time | varchar(20) | Stores the time of contact data insertion   |

---

### Table Name: Register
- **Primary Key**: `r_id`
- **Description**: Stores registration details of visitors/users.

| Field  | Type        | Description                        |
|--------|-------------|------------------------------------|
| r_id   | int(8)      | Stores the user registration ID    |
| r_fnm  | varchar(100)| Stores the full name of the user   |
| r_unm  | varchar(50) | Stores the username of the user    |
| r_pwd  | varchar(30) | Stores the password of the user    |
| r_cno  | varchar(10) | Stores the contact number of the user |
| r_email| varchar(60) | Stores the email address of the user |
| r_time | varchar(20) | Stores the registration time       |

---

### Table Name: Order
- **Primary Key**: `o_id`
- **Description**: Stores order details.

| Field     | Type        | Description                     |
|-----------|-------------|---------------------------------|
| o_id      | int(11)     | Stores the order ID             |
| o_name    | varchar(30) | Stores the full name of the user|
| o_address | varchar(200)| Stores the user's address       |
| o_pincode | int(20)     | Stores the city pincode         |
| o_city    | varchar(30) | Stores the city name            |
| o_state   | varchar(30) | Stores the state                |
| o_mobile  | bigint(20)  | Stores the mobile number        |
| o_rid     | int(8)      | Stores the registration ID      |

---

## 3.3 Input/Output Design

The input/output design of the **Bookstore Management System** includes various forms and page layouts used by both Admin and Users.

### Home Page
Home page for BMS without logged-in users.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/homepage.png)

*(Figure 16: BMS Home Page)*

---

### Selected Category
When a user selects a category (e.g., Detective), the system shows books within that category.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/selectedcategory.png)

*(Figure 17: BMS Selected Category)*

---

### Book Details (Before Login)
Book details page for visitors (users who have not logged in). Visitors are unable to add books to the cart.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/bookdetails.png)

*(Figure 18: BMS Book Details)*

---

### Visitor Login Page
Login page for visitors.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/loginuser.png)

*(Figure 19: BMS Login Page)*

---

### Register Page
Registration page for new users.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/userregistration.png)

*(Figure 20: BMS Register Page)*

---

### Contact Us Page
Contact Us page allows users to send messages or queries to the admin.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/contactus.png)

*(Figure 21: BMS Contact Us Page)*

---

### Cart Page
The cart page for users where they can review books added to the cart before making an order.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/cart.png)

*(Figure 22: BMS Cart Page Viewers)*

---

### Order Page
Users can place their orders. Only **Cash On Delivery** payment method is available.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/order.png)

*(Figure 23: BMS Order Page)*

---

### Home Page (Logged In)
Logged-in users will see a different navigation bar and can log out.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/homepageloggedin.png)

*(Figure 24: BMS Logged In Page)*

---

### Book Details (Logged In)
Logged-in users can view detailed book information and add books to the cart.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/bookdetailsloggedin.png)

*(Figure 25: BMS Users Book Details)*

---

### Add to Cart (Logged In)
Logged-in users can add books to their cart and view detailed price information.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/cartloggedin.png)

*(Figure 26: BMS Users Cart Page)*

---

### Search Books
The system allows users to search for books.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/search.png)

*(Figure 27: BMS Search Books)*

---

### Admin Login Page
Login page for the Admin using a new template.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/adminlogin.png)

*(Figure 28: BMS Admin Login Page)*

---

### Admin Home Page
Admin dashboard page using a new template.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/adminhomepage.png)

*(Figure 29: BMS Admin Home Page)*

---

### Add Category (Admin)
Admin can add new book categories.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/add.png)

*(Figure 30: BMS Add New Category)*

---

### View Category (Admin)
Admin can view a list of book categories.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/view.png)

*(Figure 31: BMS View Category)*

---

### Add Books (Admin)
Admin can add new books to the system.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/adminadd.png)

*(Figure 32: BMS Add New Books)*

---

### View Books (Admin)
Admin can view the list of available books.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/adminview.png)

*(Figure 33: BMS View Books)*

---

### View Contacted List (Admin)
Admin can view the list of people who have contacted them through the Contact Us page.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/admincontact.png)

*(Figure 34: BMS Contacted List)*

---

### Users List (Admin)
Admin can view the list of registered users.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/userlist.png)

*(Figure 35: BMS Users List)*

---

### Forget Password
Forgot password page for users.

![bookstore](https://github.com/KRam0n/tesztek01/blob/main/kepek/forgetpassword.png)

*(Figure 36: BMS Forget Password Page)*

# Chapter 4: Testing and Implementation

## 4.1 Testing Approach Used

### Black Box Testing
Black-box testing is a method of software testing that examines the functionality of an application without peering into its internal structures or workings. It is also known as specification-based testing. This method can be applied to every level of software testing, including unit, integration, system, and acceptance testing.

![bookstoretest](https://github.com/KRam0n/tesztek01/blob/main/kepek/blackbox.png)

*(Figure 37: Black Box Testing)*

Black-box testing helps identify:
- Incorrect or missing functions.
- Interface errors.
- Data structure errors or external database access issues.
- Behavioral or performance issues.
- Initialization and termination errors.

**Advantages of Black Box Testing**:
- It tests from a user’s perspective and helps in exposing discrepancies in the specifications.
- The tester does not need to know programming languages or how the software is implemented.

---

### White Box Testing
White-box testing examines the program structure and derives test data from the program’s internal logic. It is also known as glass-box, clear-box, or structural testing.

White-box testing involves:
- **Statement Coverage**: Ensuring all programming statements are exercised with minimal tests.
- **Branch Coverage**: Running tests to ensure that all branches are tested at least once.
- **Path Coverage**: Testing all possible paths, meaning all statements and branches are covered.

**Advantages of White Box Testing**:
- Encourages careful reasoning about the implementation.
- Reveals hidden code errors.
- Supports the identification of code issues regarding best programming practices.

---

### Gray Box Testing
Gray-box testing is performed with limited information about the internal workings of an application. Testers have access to detailed design documents but may not have full visibility of the entire system.

![bookstoretest](https://github.com/KRam0n/tesztek01/blob/main/kepek/graybox.png)

*(Figure 38: Gray Box Testing)*

---

## 4.2 Test Cases

### 4.2.1 Admin Login Detail

| Username | Password |
|----------|----------|
| Admin    | Admin    |

**Expected Result**:
- If fields are empty, an error message will prompt the user to fill in the fields.
- If the username or password is incorrect, an error message will notify the user to enter valid details.

---

### 4.2.2 Login Detail

| Username | Password |
|----------|----------|
| Dhaval   | Dhaval   |

**Expected Result**:
- If fields are empty, an error message will prompt the user to fill in the fields.
- If the username or password is incorrect, an error message will notify the user to enter valid details.

---

### 4.2.3 Registration Details

| Username | Password | Full Name | Security Answer |
|----------|----------|-----------|-----------------|
| EMPTY    | EMPTY    | EMPTY     | EMPTY           |

**Expected Result**:
- If fields are empty, an error message will prompt the user to fill in the fields.
- If the username or password does not exist, an error message will notify the user to enter valid details.
- If the password is less than 8 characters, an error message will prompt the user to enter a valid password.

---

### 4.2.4 Order Details

| Full Name | Address | Contact Number |
|-----------|---------|----------------|
| EMPTY     | EMPTY   | EMPTY          |

**Expected Result**:
- If fields are empty, an error message will prompt the user to fill in the fields.
- If the contact number is not numeric, an error message will notify the user to enter a valid number.

---

### Screen-Shots

**User Login**

![bookstoretest](https://github.com/KRam0n/tesztek01/blob/main/kepek/userlogin.png)

*(Figure 39: Test Cases 1)*

---

**Admin Login**

![bookstoretest](https://github.com/KRam0n/tesztek01/blob/main/kepek/loginadmin.png)
*(Figure 40: Test Cases 2)*

---

**Add Book**

![bookstoretest](https://github.com/KRam0n/tesztek01/blob/main/kepek/addbook.png)

*(Figure 41: Test Cases 3)*

---

**User Registration**

![bookstoretest](https://github.com/KRam0n/tesztek01/blob/main/kepek/registration.png)

*(Figure 42: Test Cases 4)*

---

## 4.3 Implementation Approaches

 Far the biggest challenge encountered was time constraints. Implementation takes an extraordinary amount of time and a large amount of coordination. Scheduling project meetings around every group member’s schedule has been nearly impossible. Many of the group members were unable to devote the amount of focus that the implementation stage required. Both the former and the latter problem may be more of an issue in the academic environment where priorities of the different group members are skewed in a variety of directions. Another issue that cropped up was knowledge of the PHP programming. At least two of the four group members were unfamiliar with PHP Swing API, which is php primary user interface package. Again, this may not be as much of an issue in software engineering outside the academic arena.

One of tools we found very useful, in situations where member responsibilities need to be hashed out, is the responsibility matrix. It has really been the only tool that has allowed us to continue making progress. Everyone is assigned a task, and everyone is held accountable for the completion of their assigned task. It also allows us to track tasks that need to be done. The responsibility matrix has proven to be an invaluable tool in the software engineering process.

---

# Chapter 5: Conclusion

## Conclusion

At first glance, the **Bookstore Management System** appears to be a comprehensive system, but it has several limitations. It is mainly used for listing book categories, managing customers, and handling book-related tasks. The system is designed to help customers view book information and manage their bookstore purchases.

We encountered challenges such as database creation, designing the system's front end and back end, and coding. Additionally, only one user can use the system at a time, and certain features, like a service module, are missing.

However, we gained valuable knowledge in various programming languages and tools such as **jQuery, PHP, Bootstrap, HTML, and CSS**.

---

## 5.1 Limitation of the System

- **Help**: Currently, the help feature is unavailable. Users cannot get help within the system.
- **Payment**: The online payment feature is not available. Users cannot pay online.
- **Multilingual Support**: The system does not support multiple languages.
- **Backup & Recovery**: Users cannot back up or recover their data.
- **Other Limitations**: Several additional features are not implemented.

---

## 5.2 Future Scope of the System

- **Help Module**: A help module will be added to guide users on how to navigate the system. All functionalities will be described, and users will be able to access it easily.
- **Online Payment Module**: Users will be able to make online payments, making the payment process easier and faster.
- **Multilingual Support**: The system will support multiple languages, allowing users to work in their preferred language.
- **Backup & Recovery**: A backup and recovery feature will be added, enabling users to secure their data.

---

## 5.3 Bibliography

- Websites:
  - [Google](https://www.google.com)
  - [W3Schools](https://www.w3schools.com)
  - [Stack Overflow](https://stackoverflow.com)
  - [Quora](https://www.quora.com)
  - [Scribd](https://www.scribd.com)

- Apps:
  - YouTube
  - SoloLearn
  - Udemy

---

**Prepared by**: Dhaval Makwana & Kumar Baraiya
