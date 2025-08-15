```
CREATE TABLE students (  
    id   INT,           
    name VARCHAR(50),     
    age  INT              
);

#insert values into table that we've created:  
insert into students values  
(101,"Sam", 21),  
(101,"Alex", 22),  
(101,"Bob", 20)

NOTE: Values should be entered at same position as there column
e.g
id   name  age
 |     |    |
101  Alex  21
if not entered as same position it will give error.
