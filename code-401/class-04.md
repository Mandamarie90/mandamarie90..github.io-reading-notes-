
#### nosql vs sql

1. **What type of database is the best fit for the complex query intensive environment?**  
   A relational database (RDBMS) is typically best for environments that require complex querying because it supports advanced query capabilities and transaction consistency.

2. **What type of database is the best fit for hierarchical data storage?**  
   A document-based NoSQL database, such as MongoDB, is well-suited for hierarchical data storage due to its flexible schema that can store nested data structures like JSON.

3. **Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.**  
   Imagine you have a closet where you neatly keep all your clothes sorted (SQL database). It's great for finding things quickly but adding more shelves or another closet can be tricky. Now imagine a big room where you can just keep throwing in clothes (NoSQL database). It’s easier to expand by just adding more rooms, but finding something specific might take a bit longer.

#### sql modeling techniques

1. **Among data tables, what is a one-to-many relationship and how do we “relate” them?**  
   A one-to-many relationship occurs when a record in one table can correspond to multiple records in another table. We relate them using a foreign key in the 'many' table that references the primary key of the 'one' table.

2. **Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**  
   Prior to designing your relational database, it might be useful to **create** a **diagram** of the database tables and their relationships.

3. **Explain the difference between a primary and foreign key.**  
   A primary key is a unique identifier for each record in a table, while a foreign key is a field in one table that uniquely identifies a row of another table, thereby linking the two tables.

#### sql vs nosql

1. **How do we treat keywords and parameters differently in SQL syntax?**  
   In SQL, keywords are predefined words used to perform operations, like `SELECT` or `UPDATE`, while parameters are placeholders used in SQL statements to substitute actual data values securely.

2. **Define normalization within the context of schemas and data.**  
   Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity by dividing large tables into smaller, more manageable ones and establishing relationships between them.

3. **Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**  
   Think of one-to-one as a married couple—each person is paired with just one other. One-to-many is like a teacher to students—each teacher can have multiple students, but students have just one classroom teacher. Many-to-many is like social media friends—everyone can connect with many others, and those others can connect with many more.


Master CRUD Operations: I aim to become proficient at creating, reading, updating, and deleting data within SQL databases using tools like Sequelize.
Implement the Collection Design Pattern: I plan to understand and apply this design pattern to efficiently manage data models and database interactions.
Use SQL and Sequelize Associations Effectively: I need to master SQL commands and learn to effectively use Sequelize's methods for linking data models, such as HasOne and BelongsTo.

