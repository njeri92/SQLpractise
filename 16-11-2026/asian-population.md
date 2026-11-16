link:https://www.hackerrank.com/challenges/asian-population/problem?isFullScreen=true

Given the CITY and COUNTRY tables, query the sum of the populations of all cities where the CONTINENT is 'Asia'.

```sql
Select 
sum(city.population)
from 
city INNER JOIN
country ON city.countrycode=country.code
where country.continent='asia'
```