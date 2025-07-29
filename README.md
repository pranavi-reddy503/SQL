
# SQL: BASIC QUESTIONS...

Q1. Create a FACULTY table.

![FACULTY TABLE CREATION](https://github.com/user-attachments/assets/590e707a-3edf-4134-baa2-e452120b1440)

Q2. Adding a new column in faculty table.

![faculty adding a new column name](https://github.com/user-attachments/assets/92b42cce-5358-49a9-b37e-6f5069bf6403)

Q3.Modifying an exsisting column in Faculty.

![faculty modifying an exsisting column](https://github.com/user-attachments/assets/50a3516a-430f-404f-9e95-8e50e8591801)

Q4.Dropping a column name in faculty.

![FACULTY dropping a column  name](https://github.com/user-attachments/assets/16f741ce-6548-407b-a5d3-527a74c8c400)

Q5.Adding a new constraint to faculty table.

![FACULTY adding a new constraint to the column](https://github.com/user-attachments/assets/82ea2208-48c8-46e1-8196-15add4e462da)

Q6.Dropping a constraint in faculty table

![FACULTY dropping a constraint](https://github.com/user-attachments/assets/67e33f61-d24f-4e8c-99f1-73753926f380)

Q7.Insert values into faculty table.

![FACULTY INSERTING VALUES INTO THE TABLE](https://github.com/user-attachments/assets/3dfea37c-35c1-4dd8-9451-665afaed2b13)

Q8.Using default function in table.

![using default sql;](https://github.com/user-attachments/assets/9430cf67-96b3-45c4-8de1-a6dc80683ae6)

Q9.Using count function in a table.

![COUNT FUNCTION SQL](https://github.com/user-attachments/assets/b16fa7f3-4ef0-44f3-bd69-bad7744feac3)

Q10.Using sum command in a table.

![COUNT FUNCTION SQL](https://github.com/user-attachments/assets/bac5e750-e564-4587-a362-8ccf66a79913)

Q11.Using average ccommand.

![AVG COMMAND SQL](https://github.com/user-attachments/assets/f01e31ef-18b8-492b-9409-5a59b34bf267)

Q12.Using maximum command.

![MAX COMMAND SQL](https://github.com/user-attachments/assets/92d1536b-185b-4fc6-8ef4-01fc5e90659a)

Q13.Using DCL and DML Commands.

![SQL DCL AND DML COMMANDS](https://github.com/user-attachments/assets/2e2ca6dc-b4ed-4e00-8b68-c6c44d92d36d)

Q14.Commands which help in changing strusture and the data in the queries.

![dbms modified](https://github.com/user-attachments/assets/2a8c5134-8cd4-401a-bdf6-6d9547a4e0a0)

Creating a table.

Q15.Create an Employee table with ID,Name,Dept_name,Salary as it's columns.

CREATE TABLE Employee

(ID int,Name Varchar(10),Dept_Name Varchar(10),Salary int);

desc Employee;

Q16.Create a Student table with it's relevant columns.

CREATE TABLE Student

(Roll_Number Int,Student_Name varchar(20), DOB date, Percentage float(10,2));

desc Student;

Q17.Create a movies table with it's relevant information.

CREATE TABLE Movies

(S_No Int, Name varchar(20) , rating float(10,2));

desc Movies;

Constraints

Q18.Create an Employee table with ID,Name,Dept_name,Salary as it's columns with constraints.

CREATE TABLE Employee

(ID int PRIMARY kEY,Name Varchar(10) NOT NULL,Dept_Name Varchar(10),Salary int);

desc Employee;

Q19.Create a Student table with it's relevant columns with constraints.

CREATE TABLE Student

(Roll_Number Int PRIMARY KEY,Student_Name varchar(20) NOT NULL, DOB date NOT NULL, Percentage float(10,2), Age int Default 18);

desc Student;

Q20.Create a movies table with it's relevant information.

CREATE TABLE Movies

(S_No Int NOT NULL, Name varchar(20) NOT NULL , rating float(10,2) CHECK(rating >9.0));

desc Movies;

Alter Command.

Q21.Create an Employee table with ID,Name,Dept_name,Salary as it's columns with constraints.

CREATE TABLE Employee

(ID int PRIMARY kEY,Name Varchar(10) NOT NULL,Dept_Name Varchar(10),Salary int);

ALTER TABLE Employee ADD Experience int not null;

ALTER TABLE Employee MODIFY COLUMN Name varchar(20);

ALTER TABLE Employee DROP COLUMN Salary;

desc Employee;

Q22.Create a Student table with it's relevant columns with constraints.


CREATE TABLE Student 

(Roll_Number Int PRIMARY KEY,Student_Name varchar(20) NOT NULL, DOB date NOT NULL, Percentage float(10,2), Age int Default 18);

ALTER TABLE Student ADD Fathers_Name Varchar(20);

ALTER TABLE Student MODIFY COLUMN Percentage double(10,2);

ALTER TABLE Student DROP COLUMN Age;

desc Student;

Q23.Create a movies table with it's relevant information.

CREATE TABLE Movies 

(S_No Int NOT NULL, Name varchar(20) NOT NULL , rating float(10,2) CHECK(rating >9.0));

ALTER TABLE Movies ADD Ranking int;

ALTER TABLE Movies MODIFY COLUMN Ranking double(10,3);

ALTER TABLE Movies DROP rating;

desc Movies;

Truncate Command.

Q24.Create an Employee table with ID,Name,Dept_name,Salary.

CREATE TABLE Employee (ID int PRIMARY kEY,Name Varchar(10) NOT NULL,Dept_Name Varchar(10),Salary int);

TRUNCATE TABLE Employee;

SELECT * FROM Movies;

Q25.Create a Student table with it's relevant columns.

CREATE TABLE Student (Roll_Number Int ,Student_Name varchar(20) , DOB date, Percentage float(10,2), Age int );

TRUNCATE TABLE Student;

SELECT *  FROM Student;

Q26.All commands in Movies table

![movies table](https://github.com/user-attachments/assets/2fe37a44-2bfc-441a-a91f-0113b3223072)






