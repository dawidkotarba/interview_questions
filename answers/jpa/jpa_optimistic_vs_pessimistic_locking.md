Optimistic locking:
- @Version annotation
- throws concurrent modification exception if the entity is modified by other transaction

Lock modes in JPA:
- NONE -> app will use implicit locking (either optimistic or pessimistic)
- OPTIMISTIC -> checks @Version
- OPTIMISTIC_FORCE_INCREMENT -> always increases the @Version (even if the entity does not change!). For optimistic locking of repeatable reads
- PESSIMISTIC_READ -> a shared lock is acquired. It prevents other transactions from acquiring PESSIMISTIC_WRITE
- PESSIMISTIC_WRITE -> an exclusive lock is acquired to prevent any other transaction from acquiring a PESSIMISTIC_READ or a PESSIMISTIC_WRITE lock
- PESSIMISTIC_FORCE_INCREMENT -> a database lock is acquired to prevent any other transaction from acquiring a PESSIMISTIC_READ or a PESSIMISTIC_WRITE lock and the entity version is incremented upon transaction commit.

```java
em.lock(employee, LockModeType.PESSIMISTIC_WRITE);
```

References:
- https://vladmihalcea.com/a-beginners-guide-to-java-persistence-locking/
