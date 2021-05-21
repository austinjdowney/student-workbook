## Day3: Connecting to MySQL DataBase

## Daily Journal
Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

1. In a SQL table, what is the difference between information in a row and information in a column?

2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters(
   id INT NOT NULL AUTO_INCREMENT... if not given a numerical id
   name VARCHAR(255) NOT NULL,
   age VARCHAR(255) NOT NULL,
   description VARCHAR(255) NOT NULL,
   PRIMARY KEY (id)
)


3. What is the difference between the following statements:

REVIEW- Is my understanding right?

DELETE FROM table_name; 

May delete all of the information from the table how it is writtin but not the table itself necessarily

DROP TABLE table_name;

will not just delete the information but the table and free all of the memory space