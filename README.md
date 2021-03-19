# Questions and Answers for interview prep
### Question 1: Tell me about yourself.

Hello, my name is Bethan and I am a mathematics graduate from the university of hertfordshire. Currrently I am a trainee junior DevOps consultant with Sparta Global. Whilst at university I discovered my love for technology especially computer programming when I was taught Python as part of one of my modules. Also at university I had the opportunity to do a electronics workshop in which I learnt to design, build and program a small wearable electronic device with LEDs that flashed to the beat of music.

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
- improved time to market - quicker to get software products to market and produce new products, updates and software.
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

Primary key 
Must be unique 
Must always have ana entry – cannot be null or blank
The value must never change
Each table must have a maximum of one primary key

Compound/Composite key
Type of primary key
Combines more than one field to make a unique value 

Foreign key
Doesn’t need to be unique 
Used to create a solid relationship between tables 
A table can have any number of foreign keys


### Question 3: What are DML, DDL, DCL, TCL?

DML- Data Manipulation Language 
Select, insert, update, alter

DDL- Data Definition Language
Create, alter, drop, truncate 

DCL- Data Control Language
Grant access, revoke access

TCL- Transaction control Language
Commit, rollback, savepoint

### Question 4: What is Normalisation and normal form?

Normalisation – database design technique which organises tables in a manner that reduces redundancy and dependency of data. There are six forms but only have been taught the first three.

1st Normal Form 
Make everything atomic (as small as possible)
There should be no repeating groups
Example:
A table of student id student name and courses they take with commas between course names is not in 1st normal form because there are commas which implies multiple groups. To put into 1st normal form, you would need to have multiple rows for students who have multiple courses. You could also split it into two tables one with student id and student name and another with student id and course.

2nd Normal Form 
It is in 1st Normal Form 
All non- key attributes are fully functionally dependent on the primary key
Example:
A table with product id, store id and store location would not be in 2nd normal form because store location only depends on part of the composite key the store id so to put into 2nd normal form you need to split the table into two with product id and store id in one and store id and store location in another. 

3rd Normal Form 
It is in 2nd Normal Form
There is no transitive functional dependency
Example:
A table of Book IDs, Genre Id and genre type is not in 3rd Normal form due to genre type being dependent on genre id and genre id is dependent on book id. To make it in 3rd normal form split into two tables one with book id and genre id and another with genre id and genre type.

### Question 5: Entity relationship diagram?
An entity relationship diagram shows the relationships of data sets stored in a database.
