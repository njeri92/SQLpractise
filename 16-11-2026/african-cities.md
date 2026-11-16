link:https://www.hackerrank.com/challenges/african-cities/problem?isFullScreen=true
easy 
intuation:	Submissions	Leaderboard	Discussions
Given the CITY and COUNTRY tables, query the names of all cities where the CONTINENT is 'Africa'.

Note: CITY.CountryCode and COUNTRY.Code are matching key columns.

```sql 
Select
city.name
from 
CITY 
inner JOIN country on CITY.CountryCode=COUNTRY.Code
where continent ='Africa'
```