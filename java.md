# Java Interview Questions

## Practical Tasks
- Implement Fibonacci (recursive, iterative, stream).
- Implement Factorial (recursive, iterative, stream).
- Reverse string (recursive, iterative, stream).
- Reverse array (recursive, iterative, stream).
- Refactor code to remove `instanceof`.

---

## Basic Tasks
- Implement custom **Stack / List / Queue**.
- Implement custom **Stack / List / Queue** using pure TDD.
- Implement **Stack / List / Queue** methods using only recursion.

---

## Core Java
- Ways of constructing a new object in Java (`new`, cloning, deserialization, reflection).
- Primitive types in Java – sizes and characteristics.
- Access modifiers: `protected`, `private`, `public`, (default).
- Overloading vs overriding vs hiding.
- Rules of overloading.
- Difference between override and overload; static vs runtime polymorphism.
- How to prevent class inheritance?
- `transient` keyword – usage.
- How to make an object immutable? What are the benefits?
- What is defensive copying?
- References: strong, soft, weak, phantom – differences and use cases (e.g. caches).
- Alternatives to `finalize()` method.
- Memory leaks in Java – how to create, analyze, and what tools to use?
- What is new in JDK 7/8/9/10...?
- Checked vs unchecked exceptions. Can we catch `Error`? How to design good API with exceptions?
- Exception translation.
- Can static methods be overloaded? What is method hiding?
- Difference between object and primitive.
- How to demonstrate polymorphism in Java? (with example).
- Interfaces – default and private methods.
- Keywords: `final`, `finalize`, `finally`.
- Cases when `finally` is not executed.
- Boxing / Unboxing / Autoboxing – implications.
- Try-with-resources – how it works?
- Java 8 streams: laziness, terminal vs non-terminal operations.
- Loop vs stream performance (for ~100 elements).
- Performance analysis in Java – tools and good practices.
- Benchmarking best practices.
- Cloning in Java – `Cloneable`, `clone()`, proper patterns, pros/cons.
- Serialization in Java – `serialVersionUID`, `transient`.
- Covariant return types.
- Strings: immutability, `intern()`, string pool security, extendability.
- Compilers inside JDK distribution.
- Immutable object pattern in JDK.
- Design patterns used in JDK (Decorator, Strategy, Singleton, Builder, etc.).
- Methods in `Object` class.
- Method resolution with `null` parameter (`Object` vs `String` argument).
- Usage of `Optional` as method parameter and serialization concerns.
- Returning `Stream` from a method – pros/cons.
- Stream exercises: users with sets of languages → all languages (using `flatMap` + `distinct`).
- Effectively final in lambdas – how to bypass? (`AtomicInteger` etc.)
- ClassLoaders – hierarchy (Bootstrap, Platform, Application, Custom).
- How to create an annotation?
- Can we have a final constructor? Why not?
- Do we need to override `hashCode` when overriding `equals`?
- `ThreadLocal` – usage examples.
- Inner (non-static) vs Nested (static) classes.
- When do we need a private constructor?
- How to implement XOR in Java?
- How to create a copy constructor?
- What is dynamic binding?
- When are default methods in interfaces useful?

---

## Generics
- What is type erasure? Why introduced? Which Java version?
- Bounded generics.
- PECS principle ("Producer extends, Consumer super") – rules and limitations.
- Invariance vs covariance vs contravariance.
- Are arrays covariant?
- Difference between `List<?>` and `List<Object>`. Purpose of wildcard.
- Generic fields in non-generic class – possible?

---

## Multithreading
- Deadlock, race condition, data race, livelock, starvation.
- Thread lifecycle (states in JVM).
- Double-checked locking – correct implementation.
- Singleton patterns (safe impl, enum-based).
- `i++` – how many JVM operations?
- Servlet thread-safety (methods to override, handling fields).
- Concurrency utilities: `CountDownLatch`, `Semaphore`, `ReentrantLock`, `Atomic` types, etc.
- `synchronized` on method, object, class – pros/cons.
- Atomic types – CAS mechanism.
- `volatile` keyword – behavior.
- Creating and starting a thread.
- How to stop a thread (deprecated `stop()` issue).
- Runnable vs Callable.
- Synchronization of static vs non-static methods.
- Reentrant locks.
- Write code that causes deadlock.
- Debugging deadlocks.
- Thread dumps – generation and analysis.
- Difference between `wait` and `sleep`.
- Methods: `wait`, `notify`, `notifyAll`, `sleep`, `yield`.
- What happens to thread when sleeping? Where can `wait()` be called?
- POJO – definition and use.
- JNI (Java Native Interface).
- Thread pools – usage, frameworks.
- I/O resources and deadlocks.
- Callable and Future.
- Determining number of CPU cores in environment.
- Generating thread dump from CLI.
- Critical section – definition.
- Thread-safe collections in Java.
- Concurrency patterns and good practices.

### Multithreading – Practical
- Implement safe Singleton (handling serialization, classloading issues).
- Implement double-check idiom.

---

## Collections
- Diagram of Java Collections framework.
- When to use Hash vs Tree vs Linked collections.
- Big O complexity of collections (Hash, Tree, Linked, Array-based).
- Map vs Set vs List vs Queue.
- FIFO vs LIFO.
- `EnumSet` – usage.
- Comparable interface in Tree-based collections.

### Maps
- Map interface vs Collection interface.
- Map vs Switch performance.
- Switch with String vs Map.
- Types allowed in switch (by Java version).

#### HashMap
- Initial size and load factor.
- Why use bit-shift instead of modulo?
- Buckets – structure and storage.
- Data structures for buckets (LinkedList → Tree).
- `put()` and `get()` return types.
- How items are stored/retrieved.
- How nulls are handled.
- Rehashing – when it occurs.
- Hash collisions – effect in JDK 7 vs JDK 8+.
- Perfect hashing – supported?
- Requirements for keys (`hashCode`, `equals`).
- SynchronizedMap vs ConcurrentHashMap.
- Designing a good key.

### Lists / ArrayList
- Can you put primitive types into List?
- ArrayList vs LinkedList – when to use.
- Detecting loops in LinkedList.
- Data structure behind ArrayList.
- Default initial size.
- Ensuring capacity when full.
- Interfaces unique to ArrayList.
- Meaning of `RandomAccess`.
- Big O for operations.
- Thread-safety of ArrayList.
- Alternatives in multithreaded env.

### Queues
- Types of queues in Java.

---

## JVM, Garbage Collector, JIT
- Java memory model: heap vs stack, generations, metaspace.
- JVM/GC tuning flags.
- Threads in a "Hello World" program.
- Performance measurement tools.
- PermGen vs Metaspace.
- Full/Major/Minor GC – differences.
- Eden, Survivor, Old generation.
- Survivor spaces (S1 vs S2).
- GC phases, root references.
- Profiling tools in JDK.
- JIT compiler – how code is compiled (`javac` → bytecode → JIT).
- Compiled vs interpreted aspects of Java.
- JIT optimizations (inlining, branch prediction, loop unrolling, escape analysis).
- Client vs Server JIT.
- Stop-the-world in GC.
- Memory fragmentation – impact.
- OS-level memory limitations despite available RAM.
- JNI to bypass JVM memory limitations.
- Securing JVM applications (e.g., socket apps).
- Creating another instance of Singleton.
- Heap vs thread vs core dump – analysis tools.
- `jcmd` usage.

---

## Libraries
- Logging frameworks in Java.
- Why use logging instead of `System.out`.

---

## JMX
- What is JMX?
- JMX communication model – read/write or both?

---

## JMS
- Topic vs Queue in JMS.

---

## XML / JAXB
- SAX vs DOM vs JAXB parsing approaches.
- JAXB – what is it, tools (`wsimport`).
- Marshalling: Java object → XML.
- `XmlTransient` behavior.
- What is XSLT?
- DTD vs XML Schema.
