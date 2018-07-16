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
- What is new in JDK7/8/9/10...?
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
- Is it a good practice to use "Optional" as a method argument? How about serialization?
- What do you think about returning a Stream from a method?
- There is set of users. Each user contains set of languages he speaks. How to get all languages spoken by all users? (stream with flatmap and distincts)

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
- java.util.concurrent -> CountDownLatch, Read/Write locks, Atomic types etc.
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
- What is POJO and where we should use it?
- What is JNI (Java Native Interface)?
- What are thread pools? What framework have you used to build such thread pool?
- Why I/O resources are most likely exposed to deadlocks?
- Where we can use Callable interface? What is Future an object in Callable interface?
- How can we determine how may cores we can utilize in current environment to build our thread pool?
- How we can generate ThreadDump on the machine we have only console/CLI access?
- What is a critical section?
- What is thread pools? What framework have you used to build such thread pool?
- Why Concurrency Utilities were introduced? What data structures it implements? What other mechanisms it provides?

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

## Garbage Collector
- What is full/major/minor GC? How to avoid full GC?
- Young vs Old generation
- How GC works? (root, phases etc.)
- Do you know difference between survivor 1 and survivor 2 in Java?
- What is the structure of JVM heap?
- How we can influence garbage collection in JVM?
- Tools provided with JDK
- What is profiling?
- What is JIT?
- Describe how the code is compiled in Java (javac -> JIT)
- How the code is compiled in java? bytecode vs native code compiled by JIT
- Is Java a compiled or interpreted language?
- What optimizations do you know that are performed by JIT? (inlining, branch prediction,loop enrolling moving some objects from heap to stack etc.)
- What is the difference between server/client JIT compiler?
- What is "Stop the world" in GC? When it is run?
- What is memory fragmentation and why this can effect JVM-based applications performance or possibility to work?
- If JVM cannot allocate memory for big collection of data but we have more than enough memory what can be an issue on level of operation system that we can expect?
- How we can bypass memory limitations of JVM using JNI interface? Why we can do that?
- How you will secure JVM application from perspective of performance, when you're developing socket application?
- How we can create a second instance of Singleton object?

# Libraries
- How can we provide logging mechanisms inside Java application? What logging frameworks do you know?
- Why it's better to use logging frameworks instead of output to System.out?

# JMX
- What is JMX?
- Is JMX one way or two way communication protocol (read, write or read & write)?


# JMS
- Topic vs Queue in JMS

