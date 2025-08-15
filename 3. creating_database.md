📌 Purpose:
    This script demonstrates how to create a database in MySQL.
    A database is a structured collection of data stored electronically.

💡 Notes:
    - Each database can contain multiple tables.
    - Use `CREATE DATABASE IF NOT EXISTS` to avoid errors if the DB already exists.
    - Always select your database before creating tables using `USE database_name;`

📂 Example Scenario:
    Suppose we are building a school management system.
    We'll create a database named `school` where we'll store all tables
    like students, teachers, courses, etc.

========================================

## Create a database named 'school'  
CREATE DATABASE school;

## (Optional) Create the database only if it doesn't already exist  
CREATE DATABASE IF NOT EXISTS school;  
  
