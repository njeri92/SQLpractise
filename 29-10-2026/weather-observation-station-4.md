# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-4/problem?isFullScreen=true

Difficulty:easy

Intution:
Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.

DISTINCT-only displays unique names leaves out the duplicate 
count the number of cities -number of unique cities


```sql
SELECT COUNT(CITY)-COUNT(DISTINCT CITY) FROM STATION

```