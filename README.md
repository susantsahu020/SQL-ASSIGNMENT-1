# SQL-ASSIGNMENT-1

Instructions

create a SQLITE database or use an existing database and create a table in the database called "Ages":
CREATE TABLE Ages (
  name VARCHAR(128),
  age INTEGER
)

Then make sure the table is empty by deleting any rows that you previously inserted, and insert these rows and only these rows with the following commands:

DELETE FROM Ages;
INSERT INTO Ages (name, age) VALUES ('Mara', 28);
INSERT INTO Ages (name, age) VALUES ('Otto', 33);
INSERT INTO Ages (name, age) VALUES ('Fyn', 31);
INSERT INTO Ages (name, age) VALUES ('Neshawn', 17);

Once the inserts are done, run the following SQL command:
SELECT hex( |name| age) AS X FROM Ages ORDER BY X

Find the first row in the resulting record set and enter the long string that looks like 53656C696E613333.
Answer ==> The first row in the resulting record set : 46796E3331



Evaluation Scheme:

1.	Creating a Data Base using SQLITE package - 30 marks
2.	Create a Table with the Name “Ages” - 20 marks
3.	Insert the atleast 5 rows into the table - 30 marks
4.	Returning the result in the output with the hex encoded value - 20 marks
