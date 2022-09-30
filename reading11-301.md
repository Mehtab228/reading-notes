# Readings: Mongo and Mongoose

## -

### *What kind of data is a good fit for an SQL database?

- For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries. On a high-level, NoSQL don’t have standard interfaces to perform complex queries, and the queries themselves in NoSQL are not as powerful as SQL query language

### *Give a real world example

- It would be good for complex query's such as cross logins across different sites such as logging into a site using google

### *Which type of database is best for hierarchical data storage?

- SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores. This means that SQL databases represent data in form of tables which consists of n number of rows of data whereas NoSQL databases are the collection of key-value pair, documents, graph databases or wide-column stores which do not have standard schema definitions which it needs to adhered to

- SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data

### *Which type of database is best for scalability?

- SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable. SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load

### *What does SQL stand for?

- Structured Query Language

### *What is a relational database?

- A relational database includes tables containing rows and columns. For example, a typical business order entry database would include a table that describes a customer with columns for name, address, phone number and so forth

### *What type of structure does a relational database work with?

- A relational database (RDB) is a way of structuring information in tables, rows, and columns. An RDB has the ability to establish links—or relationships–between information by joining tables, which makes it easy to understand and gain insights about the relationship between various data points

### *What is a ‘schema’?

- schema is a cognitive framework or concept that helps organize and interpret information. We use schemas because they allow us to take shortcuts in interpreting the vast amount of information that is available in our environment

### *What is a NoSQL database?

- NoSQL, also referred to as “not only SQL”, “non-SQL”, is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases

### *How does it work?

- NoSQL databases store data in documents rather than relational tables. Accordingly, we classify them as "not only SQL" and subdivide them by a variety of flexible data models. Types of NoSQL databases include pure document databases, key-value stores, wide-column databases, and graph databases

### *What is inside of a Mongo database?

- MongoDB makes use of records which are made up of documents that contain a data structure composed of field and value pairs. Documents are the basic unit of data in MongoDB. The documents are similar to JavaScript Object Notation, but use a variant called Binary JSON (BSON)

### *Which is more flexible - SQL or MongoDB? and why

- MongoDB is more flexible because it is a database that is more advanced and capable of handling big data with dynamic schema features. SQL Server is an RDBMS that is used to manage the relational database system and offers end-to-end business data solutions. In the case of unstructured data MongoDB is a good choice

### *What is the disadvantage of a NoSQL database?

- The top advantages of NoSQL include its scalability, simplicity, less code, and easy maintenance. Disadvantages of NoSQL; less mature, less flexible queries. Queries are less flexible. NoSQL isn't designed to scale by itself
