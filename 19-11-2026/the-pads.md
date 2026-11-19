link:https://www.hackerrank.com/challenges/the-pads/problem?isFullScreen=true

intuition:
first select statement-select name and left(,1)-displays the first character in occupation



```sql 
SELECT CONCAT(name, '(', LEFT(OCCUPATION, 1), ')')

FROM OCCUPATIONS
  ORDER BY NAME ASC;
     SELECT CONCAT('There are a total of ', COUNT(*), ' ', LOWER(OCCUPATION), 's.')
       FROM OCCUPATIONS GROUP BY OCCUPATION
          ORDER BY COUNT(*), OCCUPATION ASC

          ```