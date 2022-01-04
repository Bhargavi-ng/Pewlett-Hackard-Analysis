# Pewlett-Hackard-Analysis

## Overview of the analysis:
The purpose of this project is to prepare for Pewlett-Hackard's "silver tsunami" - current employees reaching retirement age. The two assignments that need to be completed as part of the challenge are: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. 

## Results:
Below is the ERD diagram used for this project.

![Employee Database ERD diagram](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/EmployeeDB.png)

### Deliverable 1: Determine the number of retiring employees per title
First, a table was created to with all the retiring employees. The data output from this table can be found here [Retiring Employee Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/retirement_info.csv)
#### Query and Sample output:

![Employees Eligible for Retirement](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Retirement_Titles_DB.PNG)
Then, the current title of these above employees was determined and saved in a table. The data output from this table can be found here [Current title of Retiring Employee](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/unique_titles.csv)
#### Query and Sample output:

![Employees Eligible for Retirement](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Unique_Titles_DB.PNG)
Finally, the count for each title was determined and saved to a table. The data output from this table can be found here [Count of Retiring employees by title](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/retiring_titles.csv)
#### Query and Output:

![Count of Retiring Employees by Title](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Retiring_Titles_DB.PNG)

### Deliverable 2: Identify employees who are eligible to participate in a mentorship program
The list of CURRENT employees with bithdate between Jan 1965 to Dec 1965 were identified as mentors and saved to a separate table. The data output from this table can be found here [Count of Retiring employees by title](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/mentorship_eligibility.csv)

#### Query and Sample output:
![Mentorship Eligible Employees Query](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Mentorship_Query.PNG)
![Mentorship Eligible Employees with their titles](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Mentorship_Eligible_Employees_DB.PNG)

## Summary:

- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are 90,398 employees eligible for retirement when "silver tsunami" begins. The number of roles that need to be filled depends on how many employees are willing to stay on mentor others. There are 57,668 employees in "Senior" position that are eligible for retirement. I would say atleast 60% of that positions need to be filled to keep the company operational.

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Np, there aren't enough mentors to train the next generation of Pewlett Hackard employees based on the below analysis.

Below is summary of Eligible Mentors, Retirement eligible title and count.
![Mentorship to Retiring Positions Ratio](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Mentorship_Ratio.PNG)

Query and Output for Mentors count by title:
![Mentors Count by Title](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Resources/Mentorship_count_title.PNG)



## Resources:
#### Data sources: 
1. [Employee Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/employees.csv)
2. [Departments Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/.csv)
3. [Departments Manager Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/dept_manager.csv) 
4. [Departments Employees Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/dept_emp.csv) 
5. [Employee Titles Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/titles.csv) 
6. [Employees Salaries Data](https://github.com/Bhargavi-ng/Pewlett-Hackard-Analysis/blob/main/Pewlett-Hackard%20Analysis%20Folder/Data/salaries.csv) 

#### Data Tools: PostgreSQL, pgAdmin
