# SQL-50-Leetcode

[584. Find Customer Referee](https://leetcode.com/problems/find-customer-referee/description/?envType=study-plan-v2&envId=top-sql-50)
``` sql
SELECT name
FROM Customer
WHERE referee_id != 2 OR referee_id IS NULL

```
