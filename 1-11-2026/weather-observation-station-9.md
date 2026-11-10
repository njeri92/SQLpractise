# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-9/problem?isFullScreen=true

Difficulty:med

INTUITION:

Query the list of CITY names from STATION that do not start with vowels. Your result cannot contain duplicates.


```sql
 SELECT DISTINCT city from STATION
 WHERE 
 CITY NOT LIKE 'A%'
AND CITY NOT LIKE 'E%'
AND CITY NOT LIKE 'I%'
AND CITY NOT LIKE 'O%'
AND CITY NOT LIKE 'U%';
```