
DB:  `Store`

Table: `customers`

** Question: adjust the following query to display the null values as "No Address"**

```sql
SELECT COALESCE(address2, 'No Address')
FROM customers
```


DB: Store
Table: customers
 **Question: Fix the following query to apply proper 3VL**


```sql
SELECT *
FROM customers
WHERE address2 IS NOT null;
```


 DB: Store
Table: customers
**Question: Fix the following query to apply proper 3VL**


```sql
SELECT coalesce(lastName, 'Empty'), *  from customers
where (age IS NULL);
```
