# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-6/problem?isFullScreen=true

Difficulty:med

INTUITION:

Query the list of CITY names starting with vowels (i.e., a, e, i, o, or u) from STATION. Your result cannot contain duplicates.


```sql
 SELECT DISTINCT city from STATION WHERE LEFT(CITY,1)IN ('a','e','i','o','u')
```