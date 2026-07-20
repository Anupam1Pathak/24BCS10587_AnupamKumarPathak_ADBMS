# e34aacbb-799a-4b7e-aff5-3d73de2bcdfc.sql

``` sql
/* Write a query to output the name of the fruits (f_name) from the table 'fruit' which are not present in the table  inventory(f_name column has the name of the fruits and inv_name has the name of the items in inventory). */

SELECT f_name from fruit
EXCEPT
SELECT inv_name from inventory;
```
