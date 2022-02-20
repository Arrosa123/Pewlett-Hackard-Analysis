# Pewlett-Hackard-Analysis
## Overview of the analysis:
With postgreSQL's the ability to merge tables, and select distinct employee numbers, and did some analysis on tables that contain informative knowledge to the company regarding strategic employees retirement campaign. And determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Results:

- Image below indicate that the table to retrieve the employees who were born between 1952 and 1955 and their titles.

![2022-02-19 (2)](https://user-images.githubusercontent.com/96403349/154823874-f0878a2e-4822-41f9-9860-488d9e581bf2.png)

Note: There are duplicate entries for some employees because they have switched titles over the years. 


- Image below indicate that retrieve the employee number, first and last name, and title columns from the previous retirement Titles table by using (DISTINCT ON) statement to get the each employees name and their titles.

![2022-02-19 (3)](https://user-images.githubusercontent.com/96403349/154824036-6fc14c32-ec52-44a7-9855-54844153ccde.png)


- Image below indicate the number of titles that are retiring.
 
 ![2022-02-19](https://user-images.githubusercontent.com/96403349/154823884-7f2be165-dce9-4f6c-a77a-fd29ed2d490a.png)
 
 
 - Image below indicate the mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.
 
 ![2022-02-19 (4)](https://user-images.githubusercontent.com/96403349/154824190-5dfa121b-67a2-4ff9-8592-ceff0fb5389b.png)
 
 ## Summary:
 
 - How many roles will need to be filled as the "silver tsunami" begins to make an impact?

90,398 roles are need to be filled as the "silver tsunami" begins to make an impact.

![2022-02-19 (5)](https://user-images.githubusercontent.com/96403349/154824400-15aa1386-8915-4b6f-9ec8-1ebf13e1ceba.png)

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
NO, we have 1,940 employees who qualified to participate in the departments to mentorship the next generation of Pewlett Hackard employees.

![2022-02-19 (6)](https://user-images.githubusercontent.com/96403349/154824489-928f532a-3bd3-46fb-a5ec-ec2f8bc5e4a9.png)

 
