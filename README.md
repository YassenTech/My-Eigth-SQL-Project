# My-Eigth-SQL-Project

MyEigthSQLProject (Portfolio Project)
Repository Name: MyEigthSQLProject
Description: Demonstrating SQL data cleaning, transformation, and the use of the BIT datatype to handle Boolean values in the heart_disease_uci dataset.

About This Project
In this project, I focused on transforming and cleaning the heart_disease_uci dataset to showcase my ability to work with different SQL datatypes, specifically the BIT datatype. I analyzed and fixed data issues, applied conditional updates, and ensured the dataset was ready for further analysis or integration into larger systems.

Key Fixes and Improvements
Datatype Transformation
Converted the SEX column to a BIT datatype:
1 = Male, 0 = Female.
Converted the FBS (Fasting Blood Sugar) column to BIT:
1 = Yes, 0 = No.
Why this matters: Boolean columns simplify analysis, improve storage efficiency, and enforce consistent data representation.
Null Handling
Replaced all NULL values in important columns with meaningful defaults:
thal, ca → 3 (indicating absence of a feature)
fbs, restecg, trestbps, slope, exang, oldpeak → 0
Why this matters: Eliminates errors in calculations or filters caused by missing data and ensures dataset consistency.

Data Cleaning
Updated specific rows using conditional logic (CASE) to handle edge cases.
Fixed inconsistencies in values (SEX and FBS) across the dataset.
Demonstrated flipping bit values using mathematical and bitwise operations:
FBS = ~FBS
FBS = 1 - FBS
Why this matters: Shows mastery of advanced SQL techniques and conditional logic.
Temporary Variables and Advanced SQL
Declared temporary BIT variables to store and manipulate single values.
Used SET ANSI_NULLS ON and SET QUOTED_IDENTIFIER ON to ensure proper handling of NULLs and string identifiers.
Why this matters: Demonstrates understanding of SQL standards, safety, and best practices for production-ready queries.

Project Outcome

A fully cleaned and standardized dataset.
Proper use of BIT datatype to represent Boolean values efficiently.
Ready-to-use dataset for further analysis or machine learning tasks.
Highlights core SQL skills: data cleaning, transformation, and type handling.
