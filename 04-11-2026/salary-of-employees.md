LINK:https://www.hackerrank.com/challenges/salary-of-employees/problem?isFullScreen=true

EASY 

INTUITION:Write a query that prints a list of employee names (i.e.: the name attribute) for employees in Employee having a salary greater than  per month who have been employees for less than  months. Sort your result by ascending employee_id.

CONDITION:SALARY MORE THAN 2000 AND MONTHS LESS THAN 10 

```sql 
SELECT name from employee 
where 
salary >2000 and months <10 
order by employee_id asc
