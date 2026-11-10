link:https://www.hackerrank.com/challenges/weather-observation-station-2/problem?isFullScreen=true

intuation:

Query the following two values from the STATION table:

The sum of all values in LAT_N rounded to a scale of  decimal places.
The sum of all values in LONG_W rounded to a scale of  decimal places.

SUM(LAT_N) – calculates the total of all latitude values.
SUM(LONG_W) – calculates the total of all longitude values.
ROUND(value, 2) – rounds the result to 2 decimal places.

```sql
SELECT
    ROUND(SUM(LAT_N), 2),
    ROUND(SUM(LONG_W), 2)
FROM STATION;
```