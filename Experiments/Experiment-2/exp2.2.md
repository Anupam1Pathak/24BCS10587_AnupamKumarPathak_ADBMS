# 2a3792b7-c73e-4313-a777-8a854e316a25.sql

``` sql
/* Write a query to find the list of fruits available in the supermarket.
(f_name column has the name of the fruits and inv_name has the name of inventories, you are suppose to output the name of the fruits.)*/

SELECT f_name FROM fruit
INTERSECT
SELECT inv_name FROM inventory;
```
