# -SQLQuery
## SQL Data Mining – Module 18 Task 2

## Purpose:
This SQL query retrieves all records from the OrderDetails table where the quantity ordered exceeds 20. The results are sorted by ProductID to present the data in an organized manner.

## SQL Code Used:
```sql
SELECT * FROM OrderDetails
WHERE Quantity > 20
ORDER BY ProductID;
