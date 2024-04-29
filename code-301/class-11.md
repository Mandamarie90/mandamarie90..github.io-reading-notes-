#### Fill in the chart below with five differences between SQL and NoSQL databases:

| SQL                         | NoSQL                                   |
|-----------------------------|-----------------------------------------|
| Structured Query Language   | Not Only SQL                           |
| Relational databases        | Non-relational databases                |
| Uses tables to store data   | Uses various data models like document, key-value, graph, etc. |
| Follows ACID properties     | Follows BASE properties (Basically Available, Soft state, Eventually Consistent) |
| Suitable for complex queries| Suitable for hierarchical data storage and large-scale applications|

#### What kind of data is a good fit for an SQL database?
SQL databases are best for structured data with clear relationships, like customer info or financial transactions. They're great for complex queries and ensuring data integrity, making them ideal for applications needing strong consistency and reliability.

#### Give a real world example.
An online retail store's product catalog, including item names, descriptions, prices, and inventory levels, is a good fit for an SQL database.

#### What kind of data is a good fit a NoSQL database?
Unstructured or semi-structured data, such as social media posts, user comments, sensor data, or product recommendations, is a good fit for a NoSQL database.

#### Give a real world example.
A real-world example of data that is a good fit for a NoSQL database is a social media platform like Instagram. It stores various types of data such as user profiles, images, comments, likes, and followers, which can be highly unstructured and variable in nature. A NoSQL database provides the flexibility and scalability needed to efficiently manage and query this diverse set of data.

#### Which type of database is best for hierarchical data storage?
For hierarchical data storage, a NoSQL database is often the best choice. This is because NoSQL databases, particularly document-based or graph databases, are designed to handle complex and nested data structures more efficiently than traditional SQL databases. They allow for flexible schema designs and provide native support for nested data, making them well-suited for storing hierarchical data such as organizational structures, file systems, or network topologies.

#### Which type of database is best for scalability?
For scalability, NoSQL databases are generally considered the best choice. NoSQL databases are designed to scale horizontally, meaning they can easily distribute data across multiple servers or nodes to handle increased load and accommodate growing amounts of data. This distributed architecture allows NoSQL databases to achieve high levels of scalability and performance compared to traditional SQL databases, especially in scenarios with large volumes of data or high read and write throughput requirements.

#### What does SQL stand for?
SQL stands for Structured Query Language.

#### What is a relational database?
A relational database is a type of database that organizes data into tables with rows and columns. It establishes relationships between tables using keys, allowing for efficient storage and retrieval of data.

#### What type of structure does a relational database work with?
A relational database works with a tabular structure, organizing data into tables with rows and columns.

#### What is a ‘schema’?
A "schema" in the context of databases refers to the structure that defines the organization of data in a database system. It outlines the layout of tables, their fields, data types, relationships, and constraints. Essentially, it serves as a blueprint for how data is stored, organized, and accessed within the database.

#### What is a NoSQL database?
A NoSQL (Not Only SQL) database is a type of database that provides a mechanism for storage and retrieval of data that is modeled in a non-tabular format. Unlike traditional SQL databases, which are primarily relational and store data in tables with predefined schemas, NoSQL databases are more flexible and can handle unstructured, semi-structured, or polymorphic data. They are designed to handle large volumes of data, distributed across multiple servers, and are often used for real-time web applications, big data, and cloud computing environments.

#### How does it work?
NoSQL databases work by using various data models, such as key-value pairs, document stores, column-family stores, and graph databases, to organize and retrieve data. These databases typically offer horizontal scalability, meaning they can easily scale out across multiple servers to handle large amounts of data and high transaction loads. They often sacrifice some of the consistency and ACID properties of traditional SQL databases in favor of scalability, flexibility, and high availability. NoSQL databases are commonly used in scenarios where rapid development, flexible schemas, and horizontal scaling are more important than strict data consistency and transaction support.

####  What is inside of a MongoDB database?
Inside a MongoDB database, you'll find collections of documents. Each document is a JSON-like data structure consisting of field-value pairs. These documents are stored in BSON (Binary JSON) format, which allows for efficient storage and retrieval. Collections are analogous to tables in relational databases, while documents can be compared to rows or records. MongoDB databases can contain multiple collections, each tailored to store related documents. Overall, MongoDB databases provide a flexible and scalable structure for storing and managing data.

#### Which is more flexible - SQL or MongoDB? and why.
MongoDB is generally considered more flexible than SQL databases. This flexibility stems from its schema-less design, which allows for dynamic and evolving data models. In MongoDB, documents within a collection do not need to have a uniform structure, meaning each document can have different fields and data types. This flexibility enables developers to easily adapt their data models as application requirements change without needing to modify existing data. Additionally, MongoDB's support for nested data structures and arrays provides further flexibility in representing complex relationships between entities. On the other hand, SQL databases typically require a predefined schema, where tables must adhere to a fixed structure defined by columns and data types. Any changes to the schema often require altering existing tables, which can be more rigid and less adaptable compared to MongoDB's schema-less approach.

#### What is the disadvantage of a NoSQL database?
One disadvantage of NoSQL databases is the lack of standardized query language and transaction support compared to SQL databases. Since NoSQL databases come in various types, such as document-oriented, key-value, or wide-column stores, each may have its own query language and operational characteristics. This can lead to a steeper learning curve for developers and administrators who are accustomed to SQL. Additionally, the lack of ACID (Atomicity, Consistency, Isolation, Durability) transactions in some NoSQL databases may pose challenges in maintaining data integrity and ensuring consistent transactions across the database. Furthermore, while NoSQL databases offer flexibility and scalability, they may not be suitable for all use cases, particularly those requiring complex relational queries or strict consistency guarantees.