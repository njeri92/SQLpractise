Link:https://www.hackerrank.com/challenges/weather-observation-station-15/problem?isFullScreen=true

easy

intuation:
	Submissions	Leaderboard	Discussions
Query the Western Longitude (LONG_W) for the largest Northern Latitude (LAT_N) in STATION that is less than . Round your answer to  decimal places.

```sql
SELECT round(LONG_W,4) FROM STATION 
WHERE 
LAT_N<137.2345 
order by LAT_N DESC limit 1

```