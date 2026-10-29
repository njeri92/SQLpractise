# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-5/problem?isFullScreen=true

Difficulty:easy

Intution:
Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.

selecting two things-city and length of characters 
order by length of characters asc and limit 1 will only display the bottom most 



```sql
(SELECT CITY, LENGTH(CITY) 
FROM STATION
ORDER BY LENGTH(CITY) ASC, CITY ASC
LIMIT 1
)
UNION ALL
(
SELECT CITY, LENGTH(CITY) 
FROM STATION
ORDER BY LENGTH(CITY) DESC, CITY ASC
LIMIT 1
);

```