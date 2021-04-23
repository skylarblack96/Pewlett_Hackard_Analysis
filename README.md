# Pewlett_Hackard_Analysis

## Overview
The purpose of this analysis was to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. Employees who are retiring were born between January 1, 1952 and December 31, 1955 and may have one or more titles. We conducted our analysis using the employees birth date and their most recent title to determine the number of retiring employees per title. Employees who were born between January 1, 1965 and December 31, 1965 are eligible for a mentorship program. We conducted our analysis using the employees birth date to determine mentorship program eligibility.

## Results 
- The title with the most employees retiring is Senior Staff with 28,254 and Senior Engineer with 29,414.
- The title with the least employees reitiring is Manager with 2.
https://github.com/skylarblack96/Pewlett_Hackard_Analysis/blob/main/Data/mentorship_eligibility.csv

- The title that has the most eligible employees for mentorship is Senior Staff with 568.
- The title that has the least eligible employees for mentorship is Technique Leader with 76 and Assitant Engineer with 78.

## Summary
Overall there are 90,398 roles that need to be filled as these employees retire and 1,549 employees eligible for mentorship. There are enough qualified, retirement-ready employees to mentor the next generation of Pewlett Hackard employees. There are many roles that need to be filled and so few eligible for mentorship. 
### Additional Tables
An additional table was created to visualize how many employees were eligible for mentorship by title so we could see if there would be enough retiring employees to help mentor. 
https://github.com/skylarblack96/Pewlett_Hackard_Analysis/blob/main/Data/title_count.csv

I wanted to see how many employees were retiring from each department and what their title was. I had to create two tables to obtain this information. The first one I selected emp_no, first name, last name, title, and department name and joined on the departments, employees, and unique titles tables. I then created one final table and selected a count on department name, department name, and title and grouped by department name and title and ordered by department name. In this final table it is easy to see how many employees are retiring with a certain title from a certain department.
https://github.com/skylarblack96/Pewlett_Hackard_Analysis/blob/main/Data/retire_count_by_dept_title.csv


