# SQL-TASK 1-3
## Introduction

This repository contains three diffrent tasks using SQL, I undertook three tasks that involved working with relational databases. These tasks required me to make modifications to tables, including creating, altering, and dropping tables etc. I also applied constraints to specific tables. Throughout these tasks, I utilized a range of SQL syntax elements such as SELECT, CREATE, DROP, ORDER BY, HAVING, and WHERE, among others.

### Data Set
We were provided with 3 datasets to use for this tasks, these dataset consist of files in a comma-separated values (CSV) format. Each row represents a unique employee, and the columns contain different attributes of the employee. 
- Employee
- Salary
- Department

## Tasks 

### Task 1
- Create a Database named “Students Record”
- Create the following tables in the database create
  Students Info  (Student ID, Gender, Name, Age, Subject)
  Health records (Student ID, Blood Group, Height, Weight)
  Performance (Student ID, Score, Grade)
- The ID has to be unique
- Where a student has no score, it should be ‘0’ by default
- Add a constraint that prevents the ID and Subject from taking null values
- Apply the following modifications to the table
    Change column name ‘’Subject” to ‘’Course” 
    Drop the “Age” column from the ‘Students Info’ table

  To create a Database, i used the syntax CREATE DATABASE STUDENT_RECORD below is a screenshot 

  ![](studentDatabase.jpg)

