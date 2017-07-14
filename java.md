# Java

## Good practices
- What are the rules/good practises for creating well designed class from Object Oriented programming perspective?

## Core
- Describe what is the meaning of following keywords : protected,  private, public, no keyword.
- What is the difference between override and overload?
- How can you prevent class from being subclassed?
- Transient keyword, what is it used for
- Sax vs DOM XMl parsing
- Some basics about jaxb
- How to make an object immutable?
- What is defensive copying
- Soft, weak, phantom references. How to make a cache from weak references?
- How to make a memory leak in Java?
- What is new in JDK7/8?
- Checked vs unchecked exceptions. Can we catch Error? How to make a good API?
- Exceptions translation
- Overloading vs overriding vs hiding
- Rules of overloading
- Difference between object and primitive?
- How to observe polymorphism in Java? Provide an example
- Can interface have methods implemented?
- final, finalize, finally
- When final is not going to be executed?
- Boxing, Unboxing, Autoboxing - performance implications
- Try-with-resources in Java7
- What does it mean that a stream is lazy?
- Clone in Java (Cloneable interface, clone() method)
- How to serialize object in Java? What is versionUID?
- What is "transient" keyword?

## Generics
- What is type erasure?
- PECS - when to use super, extends. What limitations they have? (i.e. putting/getting from collections, cast required etc.)
- invariance vs covariance vs contravariance
- Are arrays covariant?

## Multithreading
- What is deadlock, race-condition, data-race, livelock, starvation?
- What is double-checked-locking? How to make it right?
- How to implement singleton in the safe way? Enums as singletons.
- i++ How many operations must jvm perform in such line?
- What methods should be overridden in HttpServlet, what can we tell about thread safety of fields in servlet?
- java.util.concurrent -> CountDownLatch, locks etc.
- synchronized based on method, object, class etc. Pros/Cons of each solution
- How Atomic types work?
- How volatile works?
- How to start a new thread?
- Runnable vs Callable
- Describe Features
- What is the difference between synchronization of static and non-static methods?
- What does it mean that lock is reentrant?
- Write a code to make a deadlock
- How to debug deadlocks?
- What is thread dump? How to analyze that?

## Collections
- types of queues in Java
- FIFO vs LIFO
- hashcode/equals contract
- synchronized map vs ConcurrentHashMap
- how hashmap works? Buckets, how data is distributed in buckets
- Big O for collections (Hash, Tree, Linked, Array based)
- When to use which types of collections? (hash vs tree vs linked)
- Map vs Set vs Lists vs Queues
- What happens when you put something to map?
- What is EnumSet?
- What needs to be implemented to make i.e. tree based working (Comparable interface)
- What needs to be implemented to make hash based collection working (hashcode/equals)

### JVM
- What is full/major/minor GC? How to avoid full GC?
- Young vs Old generation
- How GC works? (root, phases etc.)
- What is the structure of JVM heap?
- Tools provided with JDK
- What is profiling?
- What is JIT?
- How the code is compiled in java? bytecode vs native code compiled by JIT
- What optimizations do you know that are performed by JIT?
- What is the difference between server/client JIT compiler?

# JMS
- Topic vs Queue in JMS
