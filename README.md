# Pewlett-Hackard-Analysisewlett-Hackard-Analysis

## Overview

The purpose of this analysis was to determine the number of retiring emplyees per title and to identify the employees who are eligible for the mentorship program. Our client is concerned about the up coming "silver tusnami", a number of employees approching retirement age, signifying a massive change in personnel. We have created tables and charts with all the employee relevant emplyoee information, such as empoloyee number, first and last name, department and employement start and end date. 

A link to the SQL code found here: https://github.com/Mikeblanchard/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_challange.sql

## Results

![](https://github.com/Mikeblanchard/Pewlett-Hackard-Analysis/blob/main/retiring_departments.png)

We have included this chart becasuse it is the most relevant to determining the job department of personnel at retirement age. The major takeaways from this data are:

- Over 90,000 employees are of retirement age.  

This is the "silver tsunami" the comapny is looking into. The Pewlett-Hackard will have to hire and train many new people to account for this loss. Perhaps they could offer part time or contract work for the senior emplyees during this time of transition. 

- The mast majority of people leaving the company are in Senior Engineering and Senior Staff roles. 

These departments will be hardest hit during this retirement cycle. 

- 1549 employees  are eligible for the mentorship program. 

These postitions are a small percentage of the total body of employees retiring. Action must be taken to fill as many roles as possible. 

- An effort to determine when the employees will retire should be undertaken. 

Just because employees are a certain age, they might not be driven to retire. Some companies offer an age plus years worked magic number in order to recieve full retirement benefits, in order to get a better sense of retirement dates. 




## Summary
To determine how many roles will need to be filled as the "silver tsunami" begins to make an impact, we can create a graph to categorize the retirees into age groups. For each year, the company can hire (internally or externally) the amount of people that would be retiring, assuming that the retirement age is 65. Currently, we have a list of people who were born between 1952 and 1955. Therefore, we would have a different hiring quota for each of the following four years.

If we look at the current projection of potential mentors and the amount of people retiring, we do not have enough retirees to mentor the next generation of employees. Moving forward, we can create a query that gives us a list of people who are retiring at the end of the current year (and for each following year). From there, the company can prioritize how many younger employees need to be trained to fill up the retired positions. It would also be beneficial if we created a query that grouped mentor-eligible employees into position titles. With this table, the company can plan the mentorship program, specifically, how many mentees a mentor can take on to fulfill the retired roles.
