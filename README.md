# Task 5 – SQL Joins

## 📌 Overview
This task demonstrates different types of **SQL JOIN operations** using a sample `EcommerceDB` database with two tables: `Customers` and `Orders`.

- **Customers**: Stores customer information  
- **Orders**: Stores order details linked to customers  

---

## 🗂️ Files in this Task
- `Task5.sql` → Contains schema, insert statements, and join queries  
- `Screenshots/` → Contains screenshots of query execution results  

---

## ⚡ Steps to Run

1. Open **MySQL Workbench** or any SQL client  
2. Run `Task5.sql` to:
   - Create the database `EcommerceDB`
   - Create tables `Customers` and `Orders`
   - Insert sample records
   - Execute join queries
3. Verify query results (see screenshots for reference)

---

## 🔍 Queries Included

1. **Inner Join** – Returns only customers who have orders  
   [Inner_Join Screenshot](./Screenshots/Inner_Join.PNG)

2. **Left Join** – Returns all customers, even if they don’t have orders  
   [Left_Join Screenshot](./Screenshots/Left_Join.PNG)

3. **Right Join** – Returns all orders, even if the customer record is missing  
   [Right_Join Screenshot](./Screenshots/Right_Join.PNG)

4. **Full Outer Join** (simulated using `UNION`) – Returns all customers and all orders  
   [Full_Join Screenshot](./Screenshots/Full_Join.PNG)

---

## ✅ Expected Outputs

- **Inner Join**: Shows only matching customer–order pairs  
- **Left Join**: Shows all customers with their orders (NULL where no order)  
- **Right Join**: Shows all orders with customer info (NULL where no customer)  
- **Full Outer Join**: Combines both left and right join results  

---


