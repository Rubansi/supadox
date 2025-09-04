# INTRODUCTION
## What is a database?
A database is an organized collection of data stored electronically for easy access, management, and retrieval.

---
# Key Database Terms and Definitions

### Data
Raw facts, figures, or information in a form suitable for processing and analysis.

### Database
An organized collection of data stored electronically to facilitate easy access, management, and retrieval.

### Table
A structured arrangement of data in rows and columns within a database, representing an entity or object.

### Row
A single record or entry in a table. Also called a tuple, it contains data for each column in the table.

### Column
A vertical entity in a table representing a specific attribute or field of the data stored in rows.

### Field
The intersection of a row and a column in a table; it contains a single piece of data.

### Relational Databases
A relational database is a type of database that stores data in structured tables composed of rows and columns

### SQL
SQL (Structured Query Language) is a programming language used to manage and manipulate data in relational databases.

### RDBMS (Relational Database Management System)
Software that manages relational databases by storing data in tables with defined relationships, enforcing data integrity and enabling querying using SQL.

---

## Examples of RDBMS

- MySQL
- PostgreSQL
- Microsoft SQL Server
- Oracle Database
- SQLite

--- 
# Non-Relational Databases (NoSQL)

### Definition  
Non-relational databases, commonly known as NoSQL databases, store and manage data differently from traditional relational (SQL) databases. They do not use fixed tables with rows and columns but instead support flexible data models suited for unstructured or semi-structured data.

### How They Work  
NoSQL databases organize data using various models such as key-value pairs, documents, wide-columns, or graphs. They often provide horizontal scalability, high performance, and flexible schema design to handle large volumes of diverse data types.

### Common Types and Examples  
- **Document Databases:** Store data as documents (e.g., JSON, BSON) with flexible schema.  
  Examples: MongoDB, CouchDB  
- **Key-Value Stores:** Store data as unique key-value pairs for fast lookups.  
  Examples: Redis, Amazon DynamoDB  
- **Wide-Column Stores:** Use tables with dynamic columns that can differ per row.  
  Examples: Apache Cassandra, HBase  
- **Graph Databases:** Store data as nodes and edges to represent relationships.  
  Examples: Neo4j, Amazon Neptune  

### Use Cases  
- Content management and catalogs  
- Real-time analytics and caching  
- Social networks and recommendation engines  
- Internet of Things (IoT) applications  
- Big data and distributed systems  

---

# Examples of Data Stored in Databases
- Textual data: names, addresses, emails  
- Numeric data: prices, quantities, counts  
- Dates and timestamps: order dates, events  
- Boolean values: true/false flags  
- Binary data: images, audio, video files  

---

### How Images and Videos Are Stored in Databases  
Images and videos are typically stored as binary large objects (**BLOBs**) in databases. These BLOBs hold the raw binary data of multimedia files. Alternatively, databases may store file paths or URLs that point to the actual files stored on external storage systems or content delivery networks (CDNs). This approach helps manage storage efficiently while allowing easy retrieval and streaming of media content.
