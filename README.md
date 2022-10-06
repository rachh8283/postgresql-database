# sql-create-insert-query in PostgreSQL
This is a project to create, insert data, and query the database in PostgreSQL.

# Project Description
Johnson Video Store owners are implementing their first relational database to replace paper files and scattered digital records. There are three files in this repository. Meta data was created and stored in a separate excel file. Database tables outlined in the metadata document were created using PostgreSQL to develop and execute a SQL script file. Data definition language (DDL) and data manipulation language (DML) include specific commands to create, modify, and update database object structures, including views, tables, indexes, and schemas. DDL scripts include statements such as CREATE TABLE and CREATE VIEW, while DML scripts include INSERT, DELETE, and UPDATE.  

## Business Requirements/Rules
Observation of operations and discussions with Johnson Video Store owners revealed several requirements and business rules for the new database. These rules include the following:

•	Each customer can rent multiple movies in DVD and VHS format.

•	Multiple distributors can provide the same movie at differing prices.

•	Each distributor can supply different types (genres) of movies.

•	A single distributor can supply several types of movies in either DVD or VHS format.

•	Each VHS and DVD has a unique ID number for the inventory created by Johnson Video Store.

•	Each VHS and DVD item has a unique distributor serial number.

•	Distributors supply movie catalogs with unique movie IDs.

•	Include dates of VHS or DVD rentals, returns, taxes, late fees, and other charges. 

•	Owners should have the ability to record discount prices.

•	Customers should be able to rent movies based on performers, runtime, genre, rating, release year, director, or Academy Award.

•	Customer accounts should track how many movies in which format were rented over specific periods such as a month, year, etc. 

•	Store only basic information on the customer in the database. This project includes the customer's first name, last name, email address, and phone number. The distributor address is provided for accounting. 

•	VHS/DVD ID numbers, movie ID numbers, and distributor ID numbers for videos, DVDs, and movies should be unique. 

•	Each movie should be able to have unlimited performers, directors, and Academy Awards. 

Metadata was created and stored in an excel file. 
