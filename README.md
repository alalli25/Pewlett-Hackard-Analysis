# Pewlett Hackard Analysis
Using SQL to create tables and execute queries containing HR data.

## Overview of Pewlett Hackard Analysis
The purpose of this project was to use SQL (pgAdmin and Postgres) to import a series of employee, department, and salary data, determine primary and foreign keys, build ERDs, and execute queries and export additional tables to help leadership understand the impact of the upcoming "silver tsunami". Specifically, we are being asked to help determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Our current parameters for the mentorship program are as follows:
- Active Employees
- Born between 1/1/1965 and 12/31/1965

## Pewlett Hackard Results & Summary
### Analyzing the Number of Retiring Employees by Title
***Employees Retiring by Title***

![](/Screenshots/retiring_titles.png)
- As we can see in the above screenshot, there are >90K employees retiring in the next few years which could put Pewlett Hackard in a situation where there are a tremendous amount of open roles if there retirements occur in bulk.
- A majority of the roles set to retire are Sr. Engineers and Senior Staff, which could trigger a knowledge transfer gap if retirement packages with planned phasing are not offered and implemented.

***Mentor Program by Title***

![](/Screenshots/mentorship_titles.png)
- As we can see in the above screenshot, there are roughly 1.5K potential mentors identified within Pewlett Hackard. Assigning these employees as internal mentors would help ease the pain of mass retiring.
- Given the active parameters, there are no managers that would act as potential mentors. This could prove problematic unless we source a mentor from outside the current parameters.

### Key Questions
#### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are currently, 240K active employees at Peewlett Hackard. If 90K employees were to retire tomorrow, that would be a 37% reduction in the active employee workforce. I would stagger retirement packages in waves to encourage certain essential employees to remain on board for a longer duration. My recommendation is to have no more than 3:1 retiree to new hire ratio.
#### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Looking at the screenshot below, you can see there are approximately 380 mentors per retiring employee. I believe that ratio is too low and I would encourage broader parameters of mentors to decrease the ratio.

***Employees Retiring vs Mentors***

![](/Screenshots/ratio.png)
