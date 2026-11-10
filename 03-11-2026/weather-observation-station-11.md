# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-11/problem?isFullScreen=true

Difficulty:med

INTUITION:

	Submissions	Leaderboard	Discussions
Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.


```sql
 SELECT DISTINCT city from STATION
WHERE CITY NOT LIKE '%a'
    and CITY NOT LIKE '%e'
    and CITY NOT LIKE '%i'
    and CITY NOT LIKE '%o'
    and CITY NOT LIKE '%u'

or CITY NOT LIKE 'a%'
    and CITY NOT LIKE 'e%'
    and CITY NOT LIKE 'i%'
    and CITY NOT LIKE 'o%'
    and CITY NOT LIKE 'u%';
```