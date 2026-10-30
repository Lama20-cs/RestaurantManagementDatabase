# Restaurant Management Database (Najd Delights)

A university group project focused on designing and implementing a relational database for a restaurant, built with **SQL (MySQL)**. The database, `najd_delights`, stores customers, staff, menu dishes, and orders.

## Database Structure

| Table | Description |
|—|—|
| `Customer` | Customer ID, name, and phone number |
| `Staff` | Staff ID, name, phone, and role (Chef, Waiter, Cashier) |
| `Dish` | Dish ID, name, category, and price |
| `Orders` | Order date, type (Dine-in / Takeaway), payment method, total amount, and links to the customer and staff member |
| `Order_Details` | The dishes and quantities that make up each order |

## What the Project Covers

- **Schema design:** creating tables, and modifying them with `ALTER TABLE` (adding, renaming, modifying, and dropping columns).
- **Data manipulation:** `INSERT`, `UPDATE`, and `DELETE` operations with sample data.
- **Constraints:** `primary keys`, `foreign keys`, `NOT NULL`, `UNIQUE`, `CHECK`, and `DEFAULT` to keep the data valid.
- **Queries:** SELECT with filtering, plus aggregate functions (`COUNT`, `SUM`, `AVG`, `MIN`, `MAX`) and `GROUP BY`, for example the number of staff per role and the average order value.

## Technologies

- SQL
- MySQL

## My Contribution

This was a group project. I was responsible for the **Orders** part of the database, including the `Orders` table and everything related to it, such as its relationships with customers, staff, and order details.
