# Questions and Answers for interview prep
### Question 1: Tell me about yourself.

Hello, my name is Bethan and I am a mathematics graduate from the university of hertfordshire. Whilst at university I discovered my love for technology especially computer programming when I was taught Python as part of one of my modules. Also at university I had the opportunity to do a electronics workshop in which I learnt to design, build and program a small wearable electronic device with LEDs that flashed to the beat of music. For two years at university I was a Student Ambassador which enablede me to grow in confidence and improve my communication skills. Currrently I am a trainee junior DevOps consultant with Sparta Global. In my spare time I enjoy playing the piano and playing video games.

### Question 2: What is Agile and the benefit of implementing it?

Agile is an iterative approach to project management and software development that helps teams to deliver value to their customers faster and with fewer headaches.
Some Benefits of using Agile in the workplace are:
- flexible to change - if problems or new information comes to light the process can be adapted to include the new information or fix the issue that has occured.

### Question 3: What is SCRUM and the benefit of implementing it?

SCRUM is an example of Agile methodology. It is a framework that helps teams and organisations to generate values through adaptive solutions for complex problems. Benefits of implementing it in the workplace are:
- high visibility on tasks so all team members can keep on track.
- cost savings due to increased performance.
- quicker response to market demand.

### Question 4: What is DevOps and the benefit of implementing it?

DevOps is a set of practices that combine software development and IT operations which aim to shorten the systems development life cycle and participates in the entire life cycle of a project from design to development, and production support. Benefits of using DevOps are:
- minimises conflicts between teams and ensures a unified appproach to a project.
- improved time to market: quicker to get software products to market and produce new products, updates and software.
- more responsive to business needs and market demands.

### Question 5: Why did you chose Sparta Global?

They had the opportunity to use and improve my programming skills and they are part of the industry that I want a career in. Also I liked the fact that they are a fast growing company and they work with large well known companies that I had heard of.

### Question 6: Where do you see yourself in 2-5 years?

To have graduated from the training program and be working as a Junior DevOps Consultant and to be continuously learning and developing my skills.

## SQL Questions

### Question 1: What is a join?

Join is an SQL keyword used to combine matched rows from two or more tables. For data from more than one table use multiple join statements.
It allows you to create a table from more than one table.
ON defines primary and foreign key relationships

INNER JOIN – creates a table with only the matched rows from two or more tables

LEFT JOIN (LEFT OUTER JOIN) – creates a table with all the rows from the left table and any non-matched row will contain NULL in the place of the missing right table data.

RIGHT JOIN (RIGHT OUTER JOIN) – creates a table with all the row from the right table and any non-matched row will contain NULL in place of the left table data.

FULL JOIN – creates a table with all the rows from both right and left tables and any non-matching row data will contain NULL in place of the missing data.


### Question 2: What are primary keys and foreign keys and what are their functions?

- Primary key 
  - Must be unique 
  - Must always have ana entry – cannot be null or blank
  - The value must never change
  - Each table must have a maximum of one primary key

- Compound/Composite key
  - Type of primary key
  - Combines more than one field to make a unique value 

- Foreign key
  - Doesn’t need to be unique 
  - Used to create a solid relationship between tables 
  - A table can have any number of foreign keys


### Question 3: What are DML, DDL, DCL, TCL?

- DML- Data Manipulation Language 
  - Select, insert, update, alter

- DDL- Data Definition Language
  - Create, alter, drop, truncate 

- DCL- Data Control Language
  - Grant access, revoke access

- TCL- Transaction control Language
  - Commit, rollback, savepoint

### Question 4: What is Normalisation and normal form?

Normalisation – database design technique which organises tables in a manner that reduces redundancy and dependency of data. There are six forms but only have been taught the first three.

1st Normal Form 
- Make everything atomic (as small as possible)
- There should be no repeating groups
- Example:
  - A table of student id student name and courses they take with commas between course names is not in 1st normal form because there are commas which implies multiple groups. To put into 1st normal form, you would need to have multiple rows for students who have multiple courses. You could also split it into two tables one with student id and student name and another with student id and course.

2nd Normal Form 
- It is in 1st Normal Form 
- All non- key attributes are fully functionally dependent on the primary key
- Example:
  - A table with product id, store id and store location would not be in 2nd normal form because store location only depends on part of the composite key the store id so to put into 2nd normal form you need to split the table into two with product id and store id in one and store id and store location in another. 

3rd Normal Form 
- It is in 2nd Normal Form
- There is no transitive functional dependency
- Example:
  - A table of Book IDs, Genre Id and genre type is not in 3rd Normal form due to genre type being dependent on genre id and genre id is dependent on book id. To make it in 3rd normal form split into two tables one with book id and genre id and another with genre id and genre type.

### Question 5: Entity relationship diagram?
An entity relationship diagram shows the relationships of data sets stored in a database.

### Git and Github Questions
### Question 1: What is Git?
Git is a version control system.

### Question 2: What is Github?
Github is an online repository saved on a cloud.


### Python and OOP Questions
### Question 1: What is OOP and why should we use it?
- Method of structuring a software program into bundles of related attributes and behaviours
- It is designed to create simple and reusable pieces of code that any programmer or program can use it
- It makes your code reusable and logical and it makes inheritance easier to implement. It follows the DRY principle which makes programs more efficient.

### Question 2: Benefits and use cases of OOP.
- It allows you to break down your software into bite-sized problems that can then be solved one object at a time.
- Having smaller problems to deal with makes it easier for troubleshooting when something goes wrong.
- Allows an IT team to work on multiple objects of the software at the same.
-  Can be used to represent real-world objects like cars, animals and people. For example animals have set functions(methods) like eat, sleep and move and set characteristics(attributes) like spine, alive and lungs.

### Question 3: What is an API and Why should we use it?
- API(Application Programming Interface) is a set of programming instructions and standards for accessing web based software applications.
- Allows two applications to talk to each other.
- API runs between applictions, databases and devices to deliver data and create the connectivity that puts the world at our fingertips.
- Acts as a door or window into a software program, allowing other programs to interact with it without the need for a developer to share its entire code.

### Question 4: Python packages and modules - requests module use case with API.
- A package is a collection of Python modules.
- Modules are Python files which contain a set of functions, classes and variables that can be used within other files.
- requests module can be used to connect to a website and check if the website is live using an API.

### Question 5: What is pip?
- pip is a package manager in Python that is used to install packages.

### Question 6: What are the four pillars of OOP and why should we use them? Benefits and use cases of the OOP pillars.
##### Inheritance
- Inheritance is a way of creating a new class for using details of a class without modifying it. The existing class is known as the parent class, and the derived class is known as the child class.
- Benefit: Code can be reused without repeating yourself
- Use case: children inherit some of their features from their parents.

##### Abstraction
- Abstraction is the method of hiding some information from the user that the user does not require in order to run the program.
- Benefit: reduces the complexity for the user.
- Use case: you can drive a car without knowing how and why it works.

##### Encapsulation
- Encapsulation prevents data from direct modification by restricting access to methods and variables.Private attributes are denoted by an underscore either single or double.
- Benefit: It allows us to control the way in which the internal data of our object is going to be altered.
- Use case: A capsule binds all chemical contents required for curing specific disease together.

##### Polymorphism
- Polymorphism is an ability to use a common interface for multiple data types. You can inherit from the parent class as well as override the data.
- Benefit: Creates flexibility, and makes things easier for the end user.
- Use case: mobile phones can be used for many tasks such as making calls listening to music and taking pictures etc.


### DevOps Questions
### Question 1: What is DevOps?

DevOps is a set of practices that combine software development and IT operations in an aim to shorten the systems development life cycle and participate in the entire life cycle of a project from design to development and production support.

### Question 2: Why do you want become a DevOps Engineer/Consultant?


### Question 3: Explain the role of a DevOps Engineer/consultant.


### Question 4: What is cloud computing and why should we use it?
Cloud computing is the practice of using a network of remote servers hosted on the internet to store, manage, and process data, rather than a local server or a personal computer.
- Why should we use it?
  - Data protection: ability to move sensitive information into and throughout the cloud is essential for businesses to function and collaborate efficiently, quickly and freely - but this ability must be supported by a comprehensive data protection strategy
  - Scalability and flexibility: information immediately available wherever you are
  - Access to data anytime, anywhere
  - Cost efficiencies: powerful cost savings by only paying for what you use

### Question 5: Explain how you implemented DRY -  OOP - MVC - MVT - use STAR to answer this.
- DRY: Don't repeat yourself
  - DRY is a principle of software development aimed at reducing repetition of code.
  - In Python Airport Project used OOP and class structures to implement DRY so did not repeat ourselves.

- OOP: Object Oriented Programming
  - Method of structuring a software program into bundles of related attributes and behaviours.
  - In Python Airport Project used class structure layout to implement inheritance a pillar of OOP.

- MVC: Model View Controller
  - Software design pattern used for developing user interfaces.
  - In Python Airport Project used Django as MVC to create the app user interface. Flask could also be used.
