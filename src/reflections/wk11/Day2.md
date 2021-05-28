## Day 2: Daily Journal


## Daily Journal 

Read Dotnet WebAPI's > Relationships, and answer the following questions

1. What is the difference between a primary key and a foreign key

A primary key is how you define the unique marker of a table but a foreign key is how connect one table to another by placing a foreign key in the second table and defining how that foreign key references the first table.

2. What is an Alias?

An alias allows you to call to a table by defining it as something shorter and later refer back to it for example on a join statement. Primarily for helping condense code. 

3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

REVIEW 

SELECT * 
FROM 
d*,
p*,
JOIN doctors d ON d.id = p.id
WHERE p.id = @doctorId

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

