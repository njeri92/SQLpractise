link:https://www.hackerrank.com/challenges/draw-the-triangle-1/problem?isFullScreen=true

intuation:
set a variable to 5 

```sql
SET @star = 21;
SELECT REPEAT('* ', @star := @star - 1)
FROM information_schema.tables
LIMIT 20;

```