# SQL Interview Questions

## Fundamentals
- What is SQL? Difference between SQL and NoSQL.
- What is the difference between DDL, DML, DCL, and TCL?
- What are the main differences between OLTP and OLAP databases?
- What is normalization? What normal forms do you know (1NF, 2NF, 3NF, BCNF)?
- What is denormalization? When would you use it?
- What are schema-on-read and schema-on-write?

## Querying
- Difference between WHERE and HAVING.
- How can you remove duplicate rows from query results?
- What is the difference between UNION and UNION ALL?
- What are aggregate functions? (SUM, COUNT, AVG, MIN, MAX, GROUP_CONCAT, etc.)
- What is a subquery? Difference between correlated and non-correlated subqueries.
- What is the difference between EXISTS and IN?
- Difference between DELETE, TRUNCATE, and DROP.
- How does pagination of records work? (OFFSET, LIMIT, ROW_NUMBER()).

## Joins
- Types of joins: INNER, LEFT, RIGHT, FULL, CROSS.
- What is the difference between LEFT JOIN and LEFT OUTER JOIN?
- What is a self-join? Example use case.
- What is a Cartesian join (CROSS JOIN)? When could it be useful?

## Keys & Constraints
- What are: candidate key, primary key, composite key, foreign key, surrogate key?
- What is the difference between UNIQUE and PRIMARY KEY?
- What is a constraint? Types of constraints (CHECK, DEFAULT, NOT NULL, UNIQUE, FOREIGN KEY).
- What is a sequence? How is it different from AUTO_INCREMENT / IDENTITY?

## Views
- What are views? How to create them?
- Difference between a view and a materialized view.
- Is it possible to update or insert through a view?
- When to use a view vs a table?

## Indexing
- What is an index in a database?
- What data structures are commonly used for indexes (B-Tree, Hash, Bitmap, GiST, etc.)?
- Clustered vs non-clustered indexes.
- Composite index: what is it and when to use it?
- Covering index – what is it and why is it useful?
- What is an index-only scan?
- What are the downsides of too many indexes?

## Transactions & Concurrency
- What is ACID?
- What is a transaction? How do you start, commit, and rollback?
- What are transaction isolation levels? (READ UNCOMMITTED, READ COMMITTED, REPEATABLE READ, SERIALIZABLE).
- What transaction anomalies do you know (dirty read, non-repeatable read, phantom read)?
- What is the difference between READ_COMMITTED and READ_COMMITTED_SNAPSHOT in MS SQL Server?
- Difference between optimistic and pessimistic locking.
- How to implement distributed transactions? (Two-phase commit, XA transactions).

## Performance & Optimization
- What is more heavy for the database: reads or writes? What needs to be considered?
- What is an execution plan? How can we preview it?
- What algorithms are used to generate execution plans?
- Are execution plans cached in databases?
- What is a syntax tree in SQL parsing?
- How is a SQL statement processed (Parser → Optimizer → Executor)?
- What is a bulk insert? When is it useful?
- What is query hinting? When to use it?
- How would you improve performance of a DB that is write-heavy?
- How would you improve performance of a DB that is read-heavy?
- Difference between partitioning and sharding.

## Replication & Scaling
- Describe master-slave replication.
- Describe multi-master replication.
- What is sharding? Horizontal vs vertical partitioning.
- What algorithms can be used to distribute load between shards (hash-based, range-based, consistent hashing)?
- How can we add another shard and evenly distribute data without downtime?
- What is eventual consistency?

## Security
- What is SQL injection? How to prevent it?
- What are parameterized queries and prepared statements?
- What is least privilege principle in DB security?

## NoSQL
- What types of NoSQL databases do you know? (Document, Key-Value, Columnar, Graph).
- When to use NoSQL compared to relational databases?
- How does schema definition differ between NoSQL and relational databases?
- What is the CAP theorem? How does it apply to NoSQL DBs?
- BASE vs ACID – what’s the difference?

## Relational DB vs OOP
- How can you map objects with inheritance to tables?
- Pros/cons of each approach (compare with Hibernate inheritance strategies).
- What is a discriminator column?
