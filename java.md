# Java

## Core
- Describe what is the meaning of following keywords : protected,  private, public, no keyword.
- What is the difference between override and overload?
- How can you prevent class from being subclassed?
- Transient keyword, what is it used for
- Sax vs DOM XMl parsing. What is the difference with the approach?
- What is jaxb? What tools (i.e wsimport) do you know?
- How to make an object immutable?
- What is defensive copying
- Hard, soft, weak, phantom references. What are differences? How to make a cache from weak references? What can be used instead of finalize method?
- How to make a memory leak in Java?
- What is new in JDK7/8?
- Checked vs unchecked exceptions. Can we catch Error? How to make a good API?
- Exceptions translation
- Overloading vs overriding vs hiding
- Rules of overloading
- Can static method be overloaded? What is hiding? What will happen if extending class will define the non-static method with the same name?
- Difference between object and primitive?
- How to observe polymorphism in Java? Provide an example
- Can interface have methods implemented?
- final, finalize, finally
- When finally is not going to be executed?
- Boxing, Unboxing, Autoboxing - performance implications
- What is try-with-resources in Java7?
- What does it mean that a stream from Java8 is lazy?
- Clone in Java (Cloneable interface, clone() method)
- How to serialize object in Java? What is versionUID?
- What is "transient" keyword?
- Can Java return a covariant type?
- String interning in Java. intern() method
- How many compilers are there in the JDK distribution?
- What is immutable object pattern? Is it used in java (JDK)? Describe immutable types
- What design patterns are used in JDK?
- What methods are defined in Object class in Java?
- There are two methods with same name - one takes the argument of Object, another one of String. Which one will be invoked if we pass null and why?

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
- How to create and start a new thread? 
- Runnable vs Callable
- Describe Features
- What is the difference between synchronization of static and non-static methods?
- What does it mean that lock is reentrant?
- Write a code to make a deadlock
- How to debug deadlocks?
- What is thread dump? How to analyze that?
- What does it mean that synchronized methods are reentrant synchronization?
- What is the difference between wait and sleep?

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
- PECS - when to use super, extends. What limitations they have? (i.e. putting/getting from collections, cast required etc.)
- How to make a good key in Map?

# JVM
- What is full/major/minor GC? How to avoid full GC?
- Young vs Old generation
- How GC works? (root, phases etc.)
- What is the structure of JVM heap?
- Tools provided with JDK
- What is profiling?
- What is JIT?
- Describe how the code is compiled in Java (javac -> JIT)
- How the code is compiled in java? bytecode vs native code compiled by JIT
- Is Java a compiled or interpreted language?
- What optimizations do you know that are performed by JIT? (inlining, branch prediction,loop enrolling moving some objects from heap to stack etc.)
- What is the difference between server/client JIT compiler?
- What is "Stop the world" in GC? When it is run?

# JMS
- Topic vs Queue in JMS
