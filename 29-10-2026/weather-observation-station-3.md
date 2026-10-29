# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true

Difficulty:easy

Intution:Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

DISTINCT-only displays unique names leaves out the duplicate 


```sql
SELECT DISTINCT CITY FROM STATION WHERE id % 2 = 0
```