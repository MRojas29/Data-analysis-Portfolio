# Data-analysis-Portfolio
Portfolio of Excel, Tableau, Power Bi, SQL, R 

## SQL query Practice 1
Number of Comments Per User in 30 days before 2020-02-10
Return the total number of comments received for each user in the 30 or less days before 2020-02-10. Don't output users who haven't received any comment in the defined time period.
fb_comments_count
Preview
| fb_comments_count  |          |   |   |   |
|--------------------|----------|---|---|---|
| user_id            | int      |   |   |   |
| created_at         | datetime |   |   |   |
| number_of_comments | int      |   |   |   |



## SQL query Practice 2
Count the number of users who made more than 5 searches in August 2021.

| fb_searches  |          |   |   |   |
|--------------|----------|---|---|---|
| date         | datetime |   |   |   |
| search_id    | int      |   |   |   |
| user_id      | int      |   |   |   |
| age_group    | varchar  |   |   |   |
| search_query | varchar  |   |   |   |

## SQL query Practice 3
Top Two Media Types
What are the top two (ranked in decreasing order) single-channel media types that correspond to the most money the grocery chain had spent on its promotional campaigns?
| fb_searches  |          |   |   |   |
|--------------|----------|---|---|---|
| date         | datetime |   |   |   |
| search_id    | int      |   |   |   |
| user_id      | int      |   |   |   |
| age_group    | varchar  |   |   |   |
| search_query | varchar  |

## SQL query Practice 4
### Workers With The Highest Salaries
Find the titles of workers that earn the highest salary. Output the highest-paid title or multiple titles that share the highest salary.


## SQL query Practice 5
### Finding User Purchases
Write a query that'll identify returning active users. A returning active user is a user that has made a second purchase within 7 days of any other of their purchases. Output a list of user_ids of these returning active users.

## SQL query Practice 6
###Average Salaries
Compare each employee's salary with the average salary of the corresponding department.
Output the department, first name, and salary of employees along with the average salary of that department.

## SQL query Practice 7
###Salaries Differences
Write a query that calculates the difference between the highest salaries found in the marketing and engineering departments. Output just the absolute difference in salaries.

db_employee
id:int
first_name:varchar
last_name:varchar
salary:int
department_id:int

db_dept
id:int
department:varchar
