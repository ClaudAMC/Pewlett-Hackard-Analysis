# Pewlett-Hackard-Analysis
---
## Overview of Project

Pewlett-Hackard wants to get ahead of the incoming 'silver tsunami' and determine the number of retiring employees in different departments. They want to be prepared to train, recruit and mentor an incoming group of employees to replace the retiring employees. With this in mind my and Bobby's manager has given us more assignments regarding this retiring populations data. They want us to determine the number of retiring employees per job title and identify the employees who would be eligible to participate in a mentorship program.

## Results

The file containing the Queries used to generate the data below can be found in:

[Employee_Database_Challenge.sql](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Employee_Database_Challenge.sql)

### Number of Retiring Employees by Title

The file below contains the data for employees that are eligible for retirement:

[retirement_titles.csv](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv)

The file below contains the data containg the unique job titles for employees

[unique_titles.csv](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv)

The table containing the count of retiring employees by job title can be found in the file and image below:

[retiring_titles.csv](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv)

![retiring_titles.PNG](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/retiring_titles.PNG)

1. From this we can see that a large majority of the retiring population holds the title of Senior Engineer or Senior Staff. This means that the majority of the retiring employees are senior employees. The company should look to see it there are employees who currently hold the junior positions that could be transitioned into a senior role as the need arises. This way it can ease the gradual loss of senior employees. At the same time they need to look to hire more junior employees.

2. Secondly, we can see that there are only 2 retiring Managers. This means that the company can rest alittle easier where they won't need to worry too much about replacing the retiring management team.

### Employees Eligible for the Mentorship Program

The file below contains the employee information for employees who are eligible for the mentorship program.

[mentorship_eligibility.csv](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)

The image below show the tail of the mentorship eligibility table:

![Tail of Mentorship Eligibility Table.PNG](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Tail%20of%20Mentorship%20Eligibility%20Table.PNG)

3. From this table we can see that there are 1549 eligible employees for the mentorship program. Of these further analysis could be done to see who is and is not a senior staff member by title. This could further help managment decided who will or won't be in the mentorship program - this may not have any impact either if the years of experience suffice

4. The table above also only takes into account those who were born in the year of 1965. It it possible that there are more eligible employees at the company born outside those years. This would be a good analysis to continue so that they company gets a good sense of the totality of employees eligible for the mentorship program.

## Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

![Sum of retiring employees.PNG](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Sum%20of%20retiring%20employees.PNG)

The image above shows the sum of the retiring employees. We can see from this that there are going to be 72,458 possible open positions after the 'silver tsunami' in 7 different roles. The roles we can see from the image further above under the Number of Retiring Employees by Title subheading.

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

From the Mentorship Eligibility Table we can see that there are 1549 eligible employees. This would not cover the needs of their mentorship program as we saw above there are potentially 72,458 positions opening and in need of being filled by 'junior employees'.
With this in mind I created a new table with the birth date for the employees being expanded + & - 2 years on the year 1965 which represents the above mentorship eligibility table.

The query used to create the updated mentorship eligibility table is in the image below:

![Updated Mentorship Eligibility Query.PNG](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Updated%20Mentorship%20Eligibility%20Query.PNG)

The tail of this table can be found below:

![Tail of Updated Mentorship Eligibility Table.PNG](https://github.com/ClaudAMC/Pewlett-Hackard-Analysis/blob/main/Tail%20of%20Updated%20Mentorship%20Eligibility%20Table.PNG)

As we can see with this update table there are now 38,401 eligible employees for the mentorship program. This means that we may feasably be able to have 2 or even 3 mentees per mentor and be able to have enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. The next steps would be to look at the number of these mentors per role in the company. As we know the majority of positions that will need to be filled are in the Senior Staff and Senior Engineer positions so figuring out whether the majority of the eligible mentors fall within these roles as well would be of interest to the company.







