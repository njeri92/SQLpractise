link:https://www.hackerrank.com/challenges/binary-search-tree-1/problem?isFullScreen=true

intuation:


```sql 
SELECT
    N,
    CASE
        WHEN P IS NULL THEN 'Root'
        WHEN N NOT IN (SELECT P FROM BST WHERE P IS NOT NULL) THEN 'Leaf'
        ELSE 'Inner'
    END AS Node_Type
FROM BST
ORDER BY N;

```average-population