| customer_id  | customer_name  | city       | signup_date  |
| ------------ | -------------- | ---------- | ------------ |
| 101          | Aarav Sharma   | Delhi      | 2022-01-15   |
| 102          | Meera Iyer     | Mumbai     | 2022-02-20   |
| 103          | Raj Patel      | Ahmedabad  | 2021-12-01   |
| 104          | Ananya Reddy   | Hyderabad  | 2023-03-11   |
| 105          | Karan Singh    | Chandigarh | 2022-07-30   |
| 106          | Priya Desai    | Surat      | 2023-01-05   |
| 107          | Arjun Menon    | Kochi      | 2021-11-18   |
| 108          | Neha Agarwal   | Jaipur     | 2022-10-25   |
| 109          | Vikram Joshi   | Pune       | 2022-08-14   |
| 110          | Ishita Kapoor  | Lucknow    | 2023-06-01   |


| order_id  | customer_id  | order_date  | amount  | payment_mode  | status    |
| --------- | ------------ | ----------- | ------- | ------------- | --------- |
| 5001      | 101          | 2023-04-01  | 1500.00 | UPI           | Delivered |
| 5002      | 103          | 2023-04-03  | 2300.00 | Card          | Cancelled |
| 5003      | 101          | 2023-05-21  | 890.00  | Cash          | Delivered |
| 5004      | 104          | 2023-07-19  | 1200.00 | UPI           | Returned  |
| 5005      | 106          | 2023-08-12  | 640.00  | Card          | Delivered |
| 5006      | 105          | 2023-06-11  | 4500.00 | Netbanking    | Delivered |
| 5007      | 102          | 2023-09-02  | 3000.00 | UPI           | Delivered |
| 5008      | 109          | 2023-09-07  | 1750.00 | Cash          | Shipped   |
| 5009      | 110          | 2023-09-09  | 2200.00 | UPI           | Delivered |
| 5010      | 107          | 2023-05-13  | 999.00  | Card          | Returned  |
| 5011      | 108          | 2023-06-30  | 1350.00 | UPI           | Delivered |
| 5012      | 102          | 2023-08-15  | 2999.00 | Netbanking    | Delivered |


| customer_id  | customer_name  | payment_modes |
| ------------ | -------------- | --------------|
| 101          | Aarav Sharma   | UPI, Cash     |


| customer_id  | customer_name  | Delivered  | Cancelled  | Returned | Shipped | 
| ------------ | -------------- | ---------- | ---------- | -------- | ------- |
| 101          | Aarav Sharma   | 2          | 0          | 0        | 0       |

Find the total number of orders and total amount spent by each customer. Display customer name, total orders, and total amount spent, ordered by total amount descending.


List the customers who have never placed any orders.

Find the total number of orders and the total revenue generated in the last 3 months (relative to the latest order date in the dataset).

For each customer, rank their orders by amount spent in descending order. Show customer name, order_id, order_date, amount, and rank.

Find the count of orders grouped by order status.

Find the most popular payment mode based on the number of orders.

For each customer, find the number of orders placed before and after their signup anniversary date in the current year.

For each city, find the total number of customers, total number of orders, and average order amount.

Find customers who placed orders but none of their orders have been cancelled.

Find all customers who have placed more than 2 orders and their average order amount is greater than 1000.

Calculate the total amount spent by each customer and list the top 3 customers by total amount spent.

Find the most popular payment mode based on the number of orders.

Find the count of orders grouped by order status.

For each customer, rank their orders by amount spent in descending order. Show customer name, order_id, order_date, amount, and rank.