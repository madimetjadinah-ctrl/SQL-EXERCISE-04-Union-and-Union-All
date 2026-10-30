# SQL-EXERCISE-04  Union and Union All exercise
This SQL exercise is focused on mastering the use of UNION and UNION ALL through real-world banking scenarios.
 
 ## Overview

This project contains solutions for the  UNION & UNION ALL Exercise, which uses a single fictional African retail bank called NexBank to demonstrate how to combine result sets from multiple tables.

The exercise covers:
- Using UNION to combine datasets while removing duplicates.
- Using UNION ALL to combine datasets while keeping all records.
- Understanding when to use each operator.

## Learning Objectives
From completing this exercise, i am now able to:

- Understand the difference between UNION and UNION ALL.
- Combine data from multiple tables correctly.
- Eliminate duplicate records when required.

  ### UNION
SELECT column1, column2
FROM table_bank_a
UNION
SELECT column1, column2
FROM table_bank_b;

-Removes duplicate rows
-Returns a distinct result set
-Useful for unique lists and consolidated reports

 ### UNION ALL
SELECT column1, column2
FROM table_bank_a
UNION ALL
SELECT column1, column2
FROM table_bank_b;

- Keeps all rows
- Includes duplicates
-Faster because no duplicate removal is performed
-Useful for transaction logs, audits, and historical reporting
  
When using UNION or UNION ALL:
-Both queries must return the same number of columns.
-Corresponding columns must have compatible data types.

 ### Excercise Structure
Part 1: UNION (Questions 1–5)
Practice creating unique combined datasets:

Q1 -Branch Accounts 
Q2-Products
Q3-Banking Staff
Q4-Branch Cities
Q5-Targets

Part 2: UNION ALL (Questions 6–10)
Practice combining complete datasets with all records retained:
Q6-Transaction
Q7-Loan Application
Q8-Complaints
Q9-Payments
Q10-Entries


 ### Running Queries 
The SQL solutions was executed on:
Databricks
