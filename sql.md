# General
- What is more heavy for the database? Reads or writes? What needs to be considered to answer such question?

# SQL
- What is a SQL injection? How to prevent?
- Types of joins (left, right, inner, full)
- What is the difference between LEFT INNER JOIN and LEFT OUTER JOIN?
- What is union? Union distinct
- What is index in database?
- What data structures a db index can be based on?
- What is "having" in SQL? When to use it?
- Where to use "having" and when "where"
- How can you display SQL query results so that they are not repeated (distinct)?
- What are views? How to create? Is it possible to update,insert?
- What are: candidate key, primary key, composite key, foreign key, surrogate key?
- ACID
- What is a bulk insert?
- Describe aggregate functions
- What is a pagination of records?
- What is a sequence?
- READ_COMMITED vs READ_COMMITED_SNAPSHOT in MS SQL Server

# NoSQL
- What types of NoSQL databases do you know?
- When to use NoSQL database comparing to relational one?
- How could you compare the schema definition in NoSQL comparing to relational databases?
- what is the CAP theorem in distributed system?

# Relational DB specific general questions:
- What is syntax tree?
- What is execution plan? How can we preview the execution plan?
- What algorithms are used to calculate execution plan?
- Describe master-slave replication.
- Describe multi-master replication.
- Describe what sharding is.
- How would you improve performance of db that is only used to store data and not retrieving.
- Describe how SQL statement is processed by database (Parser -> Optimizer -> Executor)
- How is SQL statement optimized?
- Are execution plans cached in databases?
- What data structures are used in indexes? (trees, hashes etc.)

# Relational DB vs OOO
- How can you map objects with inheritance to tables? What are the pros/cons of each approach? (Compare approaches from hibernate inheritance strategies). What is a discriminator column?

# Architecture
- What algorithms do you know that allow to evenly distribute load between shards? (i.e. hash-based)
- How can we add another shard and evenly distribute data over there? (without shutting down entire cluster)
