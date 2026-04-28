# HR Schema (Oracle SQL)

This repository contains SQL scripts to create and populate the HR sample database schema in Oracle SQL.

## 📁 Project Structure


hr-schema/
│
├── 01_create_user.sql -- Creates HR user and permissions
├── 02_create_tables.sql -- Creates all tables, constraints, sequences, and views
├── 03_populate_tables.sql -- Inserts sample data into tables
└── README.md


## 🚀 How to Run

Run the scripts in the following order:

### 1. Create User
```sql
01_create_user.sql
2. Create Schema Objects
02_create_tables.sql
3. Populate Data
03_populate_tables.sql
⚠️ Important Notes
Scripts must be executed in the correct order.
Run them using an Oracle SQL environment (SQL*Plus, SQL Developer, etc.).
Ensure you are connected as a user with sufficient privileges.
DROP TABLE statements are included for clean re-runs.
🧠 What’s Included
Regions
Countries
Locations
Departments
Employees
Jobs
Job History
View: emp_details_view
Sequences for auto-increment IDs
📌 Purpose

This project is commonly used for:

Learning SQL and relational database design
Practice with Oracle constraints, joins, and views
Academic database assignments
