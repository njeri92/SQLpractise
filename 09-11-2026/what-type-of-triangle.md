link:https://www.hackerrank.com/challenges/what-type-of-triangle/problem?isFullScreen=true

intuation:
Write a query identifying the type of each record in the TRIANGLES table using its three side lengths. Output one of the following statements for each record in the table:

Equilateral: It's a triangle with  sides of equal length.
Isosceles: It's a triangle with  sides of equal length.
Scalene: It's a triangle with  sides of differing lengths.
Not A Triangle: The given values of A, B, and C don't form a triangle.


``` sql 
SELECT
    CASE
        -- Check if it's a valid triangle first
        WHEN A + B > C AND A + C > B AND B + C > A THEN
            CASE
                WHEN A = B AND B = C THEN 'Equilateral'
                WHEN A = B OR B = C OR A = C THEN 'Isosceles'
                ELSE 'Scalene'
            END
        ELSE 'Not A Triangle'
    END AS TriangleType
FROM TRIANGLES;

```