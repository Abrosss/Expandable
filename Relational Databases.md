# Relational Databases
Relational databases are a type of database management system (DBMS) that stores and organizes data in a structured manner using tables with rows and columns. </br>
Key characteristics of relational databases include:
1. Tabular Structure: Data in a relational database is organized into tables, which consist of rows (also known as records or tuples) and columns (also known as fields or attributes). Each row represents a single record, and each column represents a specific attribute of the data.
2. Primary Keys: Each table in a relational database has a primary key, which is a unique identifier for each record in the table. Primary keys ensure that each record can be uniquely identified and retrieved.
3. Foreign Keys: Foreign keys establish relationships between tables. A foreign key in one table references the primary key of another table, creating a link between the two tables.
4. Structured Query Language (SQL): Relational databases are typically accessed and manipulated using SQL, a standardized language for querying and managing relational data. SQL allows users to retrieve, insert, update, and delete data from the database.
Popular examples of relational database management systems (RDBMS) include:

- MySQL
- PostgreSQL
- Microsoft SQL Server
- Oracle Database
- SQLite
- </br>
Relational databases are widely used for various applications, including web applications, enterprise software, data analysis, and more.
However, for certain use cases involving unstructured or rapidly changing data, other types of databases like NoSQL databases might be more appropriate.
# Object-Relational Mapping (ORM) 
Object-Relational Mapping (ORM) is a programming technique that allows developers to interact with a relational database using object-oriented programming constructs. It bridges the gap between the object-oriented world of programming languages and the relational world of databases. The main goal of ORM is to eliminate the need for writing raw SQL queries and instead work with objects and classes in your programming language of choice.
</br>
In an ORM system, each table in the database is represented by a corresponding class, and each row in the table is represented by an instance of that class. Attributes of the class correspond to the columns in the table. This allows developers to manipulate and query the database using familiar object-oriented syntax.
</br>
Key features of ORM include:
1. Mapping: Mapping between database tables and object classes is established using annotations, configuration files, or code conventions.
2. CRUD Operations: ORM frameworks provide methods for performing CRUD (Create, Read, Update, Delete) operations on objects, which are then translated into corresponding SQL queries.
3. Lazy Loading: ORM systems often support lazy loading, which means that related data is only fetched from the database when it's actually needed.
4. Database Independence: ORM frameworks abstract the underlying database system, allowing developers to switch databases without changing the application code.
5. Data Validation: ORM often includes mechanisms for data validation and type conversions, ensuring data integrity.

ORM can simplify and accelerate the development process by reducing the amount of SQL code that needs to be written and providing a more intuitive way to work with databases. However, it's important to note that while ORM offers many benefits, there might be cases where writing custom SQL queries is still necessary for complex operations or optimizations.
