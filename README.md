# HR-Dashboard-MySQL-PowerBI

![Screenshot 2025-01-09 020435](https://github.com/user-attachments/assets/6fda7972-644c-4c64-b36c-f47ff6dfb4ed)

# Data Used

Data - HR Data with over 22000 rows from the year 2000 to 2020.

Data Cleaning & Analysis - MySQL

Data Visualization - PowerBI


# Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employement for employees who have bee terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?


 # Summary of Findings

 1. There are more male employees.
 2. White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
 3. The youngest employees is 20 years old and the oldest is 57 years old.
 4. 5 age groups were created (18-24, 25-34, 35-44, 45- 54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
 5. A lasrge number of employees work at the headquarters versus remotely.
 6. The average length of employement for terminated employees is around 7 years.
 7. The gender across departments is fairly balanced but there are generally more male than female employees.
 8. The Marketing department has the highest turnover rate followed by Training. The least turnover rate are in the Research snd development, Support and legal departments.
 9. A large number of employees com from the state of Ohio.
 10. The net change in the employees has increased over the years.
 11. The average tenure of each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.


# Limitations

1. Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
2. Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
