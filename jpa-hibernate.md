# JPA / Hibernate Interview Questions

## Basics
- What is JPA? How does it differ from Hibernate?
- What are the main advantages of using an ORM (like Hibernate) instead of plain JDBC?
- Can we use Hibernate without JPA? Can we use JPA without Hibernate?

## Caching
- Difference between L1 cache, L2 cache, and query cache.
- Eviction policies in Hibernate cache.
- Cache strategies (read-only, read-write, transactional, etc.).

## Entities & Relationships
- Types of relationships between entities.
- Differences between uni-directional and bi-directional relations.
- Which relations require a linking table? In which cases can it be avoided?
- What is a linking table? When is it created?
- List vs Set in entity relationships.
- Lazy fetching of collections – how it works and how it relates to session.
- Cascade types – what are they? Why should we be careful with cascading?
- How to define a primary key in JPA/Hibernate.
- How to design a good hashCode() for entities.
- What is orphan removal? How does it differ from cascading remove?
- Can we map a Map<K,V> as an entity relationship in JPA?

## Inheritance Strategies
- Types of inheritance:
    - Table per class
    - Single table with discriminator column
    - Joined tables
- Performance and data consistency implications of each.

## Annotations
- Difference between @Entity, @Table, and @MappedSuperclass.
- What is the purpose of @Embeddable and @Embedded?
- Difference between @OneToOne, @OneToMany, @ManyToOne, and @ManyToMany.
- What is @Id vs @GeneratedValue? What strategies exist for ID generation (AUTO, IDENTITY, SEQUENCE, TABLE)?
- What are entity graphs (@NamedEntityGraph)? Why and when to use them?

## Queries
- What is JPQL? What is the Criteria API?
- What is HQL? Pros and cons of HQL.
- What aggregation functions are available?
- What is a FetchStrategy? Which one is default?
- N+1 problem – what is it and how to solve it (batch, fetch join)?
- Difference between JOIN FETCH and normal JOIN.
- What is batch fetching and how does it differ from fetch join?
- How does Hibernate’s @Fetch(FetchMode.SUBSELECT) work?
- What tools or approaches can you use to detect and fix the N+1 problem?

## Transactions & Locking
- Difference between optimistic and pessimistic locking.
- ACID principles. Transaction isolation and propagation in JEE/Spring.
- Transaction anomalies (phenomena) – what are they? How do isolation levels prevent them?
- What is locked at each type of isolation level?
- What happens if two transactions update the same entity simultaneously?
- What is the difference between EntityManager and Session?

## Entity Lifecycle
- Entity lifecycle phases (transient, persistent, detached, removed).
- When to use detach and merge.
- Why a default constructor is required for entities.
- Difference between load() and get() methods.
- Difference between merge() and update() methods.
- What is the difference between detached and removed states?
- What is dirty checking? How does Hibernate detect changes in an entity?

## Advanced
- What is a proxy object in Hibernate? How does it work?
- What happens if you call flush()? Difference between flush() and commit().
- What is the purpose of clear()?
- Can we extend an existing entity (e.g., add lastLoginTime to User)? Which Java and DB types to use? Possible variants.

## Schema & Updates
- How to mark a class as persistable (JPA annotations).
- How to update the database schema after changing the Java code.
- Difference between INSERT and UPDATE.

## Integration
- How does Hibernate integrate with Spring?
- How do you configure Hibernate in Spring Boot?
- What is the difference between JTA and RESOURCE_LOCAL transactions?

