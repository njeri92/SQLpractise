
LINK:https://www.hackerrank.com/challenges/more-than-75-marks/problem?isFullScreen=true

Intuition:

Query the Name of any student in STUDENTS who scored higher than  Marks. Order your output by the last three characters of each name. If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending ID.


FOR LEFT():
LEFT ( expression, no_of_chars needed to the left)

FOR RIGHT():
RIGHT ( expression, no_of_chars needed to the right)



``` sql
SELECT NAME FROM STUDENTS
WHERE 
  marks >75
  ORDER BY RIGHT(Name, 3), ID;
```