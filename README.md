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
