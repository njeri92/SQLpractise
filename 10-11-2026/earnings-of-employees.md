Link:https://www.hackerrank.com/challenges/earnings-of-employees/problem?isFullScreen=true

medium 

Intuation:
The maximum total earnings of an employee.
The number of employees who have that maximum total earnings.
total earnings=sal*months



```sql
SELECT MAX(salary * months), COUNT(*)
FROM Employee
GROUP BY salary * months
ORDER BY salary * months DESC
LIMIT 1;
```