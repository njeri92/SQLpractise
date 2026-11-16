link:https://www.hackerrank.com/challenges/average-population/problem?isFullScreen=true

easy

intuation:Query the average population for all cities in CITY, rounded down to the nearest integer.


```sql
SELECT floor(AVG(population)) AS Average
FROM city;
```