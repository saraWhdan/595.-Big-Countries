# 595.-Big-Countries
Problem Link: https://leetcode.com/problems/big-countries/description/?envType=study-plan-v2&envId=top-sql-50
## Solution

```sql
select name ,population,area 
from world
where area >= 3000000
OR population >= 25000000
```
