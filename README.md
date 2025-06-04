# SQL: BASIC QUESTIONS...
Creating a table.

Q1.Create an Employee table with ID,Name,Dept_name,Salary as it's columns.
CREATE TABLE Employee (ID int,Name Varchar(10),Dept_Name Varchar(10),Salary int);
desc Employee;

Q2.Create a Student table with it's relevant columns.
CREATE TABLE Student (Roll_Number Int,Student_Name varchar(20), DOB date, Percentage float(10,2));
desc Student;

Q3.Create a movies table with it's relevant information.
CREATE TABLE Movies (S_No Int, Name varchar(20) , rating float(10,2));
desc Movies;

Constraints

Q4.Create an Employee table with ID,Name,Dept_name,Salary as it's columns with constraints.
CREATE TABLE Employee (ID int PRIMARY kEY,Name Varchar(10) NOT NULL,Dept_Name Varchar(10),Salary int);
desc Employee;

Q5.Create a Student table with it's relevant columns with constraints.
CREATE TABLE Student (Roll_Number Int PRIMARY KEY,Student_Name varchar(20) NOT NULL, DOB date NOT NULL, Percentage float(10,2), Age int Default 18);
desc Student;

Q6.Create a movies table with it's relevant information.
CREATE TABLE Movies (S_No Int NOT NULL, Name varchar(20) NOT NULL , rating float(10,2) CHECK(rating >9.0));
desc Movies;

Alter Command.

Q7.Create an Employee table with ID,Name,Dept_name,Salary as it's columns with constraints.
CREATE TABLE Employee (ID int PRIMARY kEY,Name Varchar(10) NOT NULL,Dept_Name Varchar(10),Salary int);
ALTER TABLE Employee ADD Experience int not null;
ALTER TABLE Employee MODIFY COLUMN Name varchar(20); 
ALTER TABLE Employee DROP COLUMN Salary;
desc Employee;

Q8.Q5.Create a Student table with it's relevant columns with constraints.
CREATE TABLE Student (Roll_Number Int PRIMARY KEY,Student_Name varchar(20) NOT NULL, DOB date NOT NULL, Percentage float(10,2), Age int Default 18);
ALTER TABLE Student ADD Fathers_Name Varchar(20);
ALTER TABLE Student MODIFY COLUMN Percentage double(10,2);
ALTER TABLE Student DROP COLUMN Age;
desc Student;

Q9.Create a movies table with it's relevant information.
CREATE TABLE Movies (S_No Int NOT NULL, Name varchar(20) NOT NULL , rating float(10,2) CHECK(rating >9.0));
ALTER TABLE Movies ADD Ranking int;
ALTER TABLE Movies MODIFY COLUMN Ranking double(10,3);
ALTER TABLE Movies DROP rating;
desc Movies;

Truncate Command.
Q10.Create an Employee table with ID,Name,Dept_name,Salary.
CREATE TABLE Employee (ID int PRIMARY kEY,Name Varchar(10) NOT NULL,Dept_Name Varchar(10),Salary int);
TRUNCATE TABLE Employee;
SELECT * FROM Movies;

Q11.Create a Student table with it's relevant columns.
CREATE TABLE Student (Roll_Number Int ,Student_Name varchar(20) , DOB date, Percentage float(10,2), Age int );
TRUNCATE TABLE Student;
SELECT *  FROM Student;

Q12. Create a FACULTY table.

![FACULTY TABLE CREATION](https://github.com/user-attachments/assets/590e707a-3edf-4134-baa2-e452120b1440)

Q13. Adding a new column in faculty table.

![faculty adding a new column name](https://github.com/user-attachments/assets/92b42cce-5358-49a9-b37e-6f5069bf6403)

Q14.Modifying an exsisting column in Faculty.

![faculty modifying an exsisting column](https://github.com/user-attachments/assets/50a3516a-430f-404f-9e95-8e50e8591801)

