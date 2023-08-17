# SQL-Challenge

## Background 
In this assignment, I utilized 6 CSV files to create and analyze tables within SQL. Utilizing the tables, we were able to also create an ERD based on the relationships between the different columns of our tables. Included in this repository are an image of the ERD, the schema used to create the ERD, the query used to create the tables and filter them to the desired outcomes. 

## Part 1: Data Modeling
Below is a picture of the ERD that was created to show the relationships between the tables and columns. 

![Alt text](employee_ERD-1.png)

## Part 2: Data Engineering 
In this section of the assignment, we were tasked with created a table schema for the 6 CSV files provided. This is where I created the tables for each csv, and applied primary, foreign,and composite keys to the necessary columns. For both the department employee table, and the department manager table a composite key was necessary to use as these tables each required multiple primary keys to function. 

## Part 3: Data Analysis
The final section of this assignment was utilizing the above schema to query our tables and find the desired outcomes based on what was asked of us. By using the schema created above, the tables were able to be created in PgAdmin and our CSV data was imported into each respective table. After that, I used JOIN to properly look at the desired columns of each table with the respective references to the other tables needed. In the case of questions 6 and 7, it was also necessary to first look at the entire department table to find the numbers associated with the individual departments being used to filter the query. All the code is included in a single document, but by running each segment individually, it will show the desired results. 

All CSV files provided by UO Data Analytics Bootcamp. Code was written by following examples provided by during in-class activities. Composite Key was used after following the provided documentation in the assignment pre-work, and by looking at examples on Stack Overflow to properly know how to do it. 