## -- Step 1: Select the database where the table will be created
USE school;

## -- Step 2: Create a simple table named 'students'
CREATE TABLE students (  
    id   INT,           -- Student ID (integer number)  
    name VARCHAR(50),   -- Student's name (up to 50 characters)  
    age  INT            -- Student's age  
);


-- 1. INT is used for storing whole numbers like ID or age.  
-- 2. VARCHAR(50) is used for storing text up to 50 characters.  
-- 3. This table does not have any primary key or constraints.  
