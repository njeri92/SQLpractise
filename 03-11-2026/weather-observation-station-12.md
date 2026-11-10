# Revising the select Query # 

Link:https://www.hackerrank.com/challenges/weather-observation-station-12/problem?isFullScreen=true
Difficulty:med

INTUITION:

	Submissions	Leaderboard	Discussions
Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.

RLIKE function-
```sql
SELECT distinct CITY
FROM STATION
WHERE CITY NOT RLIKE '^[AEIOU]'
   AND CITY NOT RLIKE '[AEIOU]$';

```