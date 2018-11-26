Cascade types in JPA:
- ALL
- DETACH
- MERGE
- PERSIST
- REMOVE
- REFRESH

Good practies:
- There is no cascading by default
- Avoid using ALL - it contains i.e. MERGE type.
- Be careful with REMOVE type - it can remove too much if wrongly used
- Use cascading for parent-child relation, not child-parent (i.e. @ManyToOne)
- Hibernate has also orphan removal - it can substitute the REMOVE type for some cases
