# Pewlett_Hackard_Analysis
Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database—for example, due to promotions—you’ll need to use the DISTINCT ON statement to create a table that contains the most recent title of each employee. Then, use the COUNT() function to create a final table that has the number of retirement-age employees by most recent job title.

* A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955
* The Retirement Titles table is exported as retirement_titles.csv
 
* A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title.
* The Unique Titles table is exported as unique_titles.csv
 
* A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring.
* The Retiring Titles table is exported as retiring_titles.csv
 
# Project Overview
Wee were tasked with tracking the number of employees who can retire based on birth date by using data bases and SQL. As another objective we were meant to make a table that shoes all employees who are eligable of the Mentorship Program at Pewlett Hackard.
## Deliverable 1
<img width="1045" alt="Retirement_by_titles" src="https://user-images.githubusercontent.com/91299736/141662369-85300524-4d8b-4b8d-9633-238b363325a1.PNG">
<img width="1147" alt="Retirement_by_titles_Distinct" src="https://user-images.githubusercontent.com/91299736/141662374-af80acbd-89ad-4ed5-a2c9-6e7e298be330.PNG">
<img width="176" alt="retiring_titles table" src="https://user-images.githubusercontent.com/91299736/141662378-b2ee9cdc-cf47-40cc-988a-7b82b83e6123.PNG">
<img width="242" alt="All_Tables_Created" src="https://user-images.githubusercontent.com/91299736/141662381-f8c39aba-d2f0-477f-bdd1-3bb20ea4e249.PNG">

I created tables for the people retiring by title and also preformed a Distinct on to save a new table as unique titles. All csv's contain the information needed for each individual step. 

### Deliverable 2
<img width="986" alt="Mentor_Eligiablity" src="https://user-images.githubusercontent.com/91299736/141662384-94d2c119-1e00-4e84-bda2-f0125209fcb7.PNG">

With this deliverable we were asked to make a csv with the canidates who were eligable for the Mentorship Program. It must hold current employees born between January 1st, 1965 and December 31st, 1965.
