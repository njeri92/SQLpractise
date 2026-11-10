# Revising the select Query # 

Link:https:https://www.hackerrank.com/challenges/weather-observation-station-8/problem?isFullScreen=true
Difficulty:med

INTUITION:

Query the list of CITY names from STATION which have vowels (i.e., a, e, i, o, and u) as both their first and last characters. Your result cannot contain duplicates.


```sql
SELECT DISTINCT CITY FROM STATION
WHERE 
LEFT(CITY,1) IN ('a','e','i','o','u')
AND
RIGHT(CITY,1) IN ('a','e','i','o','u')
```