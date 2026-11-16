
link:https://www.hackerrank.com/challenges/weather-observation-station-14/problem?isFullScreen=true

medium 

intuation:

Query the greatest value of the Northern Latitudes (LAT_N) from STATION that is less than . Truncate your answer to  decimal places.

```sql
SELECT truncate(max(LAT_N),4) from station
where 
LAT_N<137.2345