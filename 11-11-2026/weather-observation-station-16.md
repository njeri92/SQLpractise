link:https://www.hackerrank.com/challenges/weather-observation-station-16/problem?isFullScreen=true

easy 

intuition :
Query the smallest Northern Latitude (LAT_N) from STATION that is greater than . Round your answer to  decimal places.


```sql 
select round(LAT_N,4) from station 
where 
LAT_N>38.7780 ORDER BY LAT_N ASC LIMIT 1