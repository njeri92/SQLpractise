# Revising the select Query # 

Link:https:https://www.hackerrank.com/challenges/weather-observation-station-7/problem?isFullScreen=true

Difficulty:med

INTUITION:

Query the list of CITY names ending with vowels (a, e, i, o, u) from STATION. Your result cannot contain duplicates.


```sql
 SELECT DISTINCT city from STATION WHERE LEFT(CITY,1)IN ('a','e','i','o','u')
```