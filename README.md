# Java DataBase Connectivity (JDBC)
- Accodring to Wikipedia, Java Database Connectivity (JDBC) is an application programming interface (API) for the programming language Java, which defines how a client may access a database. It is a Java-based data access technology used for Java database connectivity.
- Java Package for JDBC API: `java.sql`
- Important Classes in java.sql
  - `java.sql.Connection`
  - `java.sql.DriverManager`
  - `java.sql.Statement`
  - `java.sql.ResultSet`

## CRUD Operation
- The acronym CRUD refers to the major operations which are implemented by databases. 
Each letter in the acronym can be mapped to a standard Structured Query Language (SQL) statement.
- Create(C) => CREATE
- Read(R)   => SELECT
- Update(U) => UPDATE
- Delete(D) => DELETE
- Java Method for 
  - SELECT Query: `statement.executeQuery(sql)`
  - CREATE, INSERT, UPDATE, DELETE: `statement.executeUpdate(sql)`

## H2 Database
- Very fast, open source, JDBC API
- Embedded and server modes; in-memory relational database
- Browser based Console application
- Small footprint: around 2.5 MB jar file size 

## Download H2
- <a href="https://www.h2database.com" target="_blank">H2 Database Website</a>

## H2 Hasing for Passwords
- <a href="https://h2database.com/html/functions.html#hash" target="_blank">H2 DB Hash Fucntion </a>