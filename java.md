# Java

## Practical tasks:
- Fibonacci recursive, iterative, stream.
- Factorial recursive, iterative, stream.
- Get rid of instanceOf() from code sample.
- Reverse string recursive, iterative, stream.
- Reverse array recursive, iterative, stream.

### Basic tasks:
- Implement custom Stack / List / Queue.
- Implement custom Stack / List / Queue using pure TDD.
- Implement Stack / List / Queue methods using only recursion.
- Fibonacci recursive, iterative, stream.
- Factorial recursive, iterative, stream.
- Get rid of instanceOf() from code sample.
- Reverse string recursive, iterative, stream.
- Reverse array recursive, iterative, stream.

### Multithreading tasks:
- Implement good singleton ( with serialization / classloading and instantiation problems solved ).
- Implement double check idiom.

## Core
- Describe what is the meaning of following keywords : protected,  private, public, no keyword.
- What is the difference between override and overload + static and runtime polymorphism.
- How can you prevent class from being subclassed?
- Transient keyword, what is it used for
- Sax vs DOM XMl parsing. What is the difference with the approach?
- What is jaxb? What tools (i.e wsimport) do you know?
- How to make an object immutable?
- What do we gain from class immutability?
- What is defensive copying?
- Hard, soft, weak, phantom references. What are differences? How to make a cache from weak references? What can be used instead of finalize method?
- How to make a memory leak in Java? How to analyze memory leaks in Java? What tools you can use?
- What is new in JDK7/8/9/10...? [Answer](answers/java/java_versions_comparison.md)
- Checked vs unchecked exceptions. Can we catch Error? How to make a good API?
- Exceptions translation
- Overloading vs overriding vs hiding
- Rules of overloading
- Can static method be overloaded? What is hiding? What will happen if extending class will define the non-static method with the same name?
- Difference between object and primitive?
- How to observe polymorphism in Java? Provide an example
- Can interface have methods implemented?
- Can interface have private methods?
- final, finalize, finally
- When finally is not going to be executed?
- Will finally be executed when we override SecurityManager behavior?
- Boxing, Unboxing, Autoboxing - performance implications
- What is try-with-resources in Java7?
- What does it mean that a stream from Java8 is lazy?
- For loop performance vs Stream performance for 100 items.
- How to analyze the app performance? What tools you can use?
- What good pratices for benchmarking in Java do you know?
- Clone in Java (Cloneable interface, clone() method). How to implement a clone mechanism properly? Shall we use that at all?
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
- What is thread dump? How to analyze that? What tools you can use to analyze a thread dump?
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
- What thread safe structures do you know in Java?
- What concurrency patterns / good practices do you know [Answer] (answers/java/java_concurrency_good_practices.md)

### Multithreading tasks:
- Implement good singleton (with serialization / classloading and instantiation problems solved).
- Implement double check idiom.

## Collections
- Draw diagram of Java collections.

### Maps
* How does Map interface correspond with Collection interface?
* Map vs Switch statement performance?
* Would you use Switch with String or Map instead?

#### HashMap
- What is HashMap initial size?
- How is initial size calculated. Why is bit-shift preferred over modulo for calculations like this?
- What is HashMap loadFactor?
- What is default value of load factor for HashMap?
- What is bucket?
- What data structures are used for buckets?
- Does put() method have return type or is it void method?
- Does get() method have return type of is it void method?
- How is item stored in HashMap when put() is called.
- How is item retrieved when get() is called.
- Where are nulls stored in HashMap ( with index )?
- What data structure is HashMap build upon?
- Describe what rehashing is and when it occurs.
- What data retrieval speed you would get from JDK 7 HashMap if someone implemented malicious hashcode that returns same value for all items put to map. Would such thing even work? If yes why if no why? What about JDK 8+ ?
- Does Java HashMap support perfect hashing?
- What needs to be implemented to make hash based collection working (hashcode/equals)
- Synchronized map vs ConcurrentHashMap
- How to make a good key in Map?

### Lists
- Can you put primitive types to List? Why?
- When would you use ArrayList and when LinkedList?
- How can we check whether the LinkedList has a loop?

#### ArrayList
- What data structure is used for array list.
- What is default size of underlying array if we don't specify initial size of ArrayList?
- Is it good idea to define initial size of ArrayList and why?
- What happens if underlying array gets filled up to much? ( ensureCapacity() )
- What specific interface ArrayList implements that LinkedList does not?
- What means that ArrayList implements RandomAccess?
- Big O for each ArrayList methods.
- Is ArrayList thred safe?
- Is ArrayList thread safe?
- What other data structure would you use in place of ArrayList in multithreaded environment?
- How many thread simple program that prints "Hello world" to console has?

### Queues
- Types of queues in Java

### Others
- FIFO vs LIFO
- Big O for collections (Hash, Tree, Linked, Array based)
- When to use which types of collections? (hash vs tree vs linked)
- Map vs Set vs Lists vs Queues
- What is EnumSet?
- What needs to be implemented to make i.e. tree based working (Comparable interface)
- PECS - when to use super, extends. What limitations they have? (i.e. putting/getting from collections, cast required etc.)

### Collections - practial tasks:
- Implement custom Stack / List / Queue.
- Implement custom Stack / List / Queue using pure TDD.
- Implement Stack / List / Queue methods using only recursion.

# JVM
- Java memory model (heap vs stack, young generation vs old generation, metaspace etc.)
- What flags do you know for tuning JVM/Garbage Collector?
- How many thread simple program that prints "Hello world" to console has?
- Describe Java memory model
- How can we measure performance of the application? What tools do you know for such purpose?

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
- How to bypass memory limitations of JVM using JNI interface? Why we can do that?
- How you will secure JVM application from perspective of performance, when you're developing socket application?
- How to create a second instance of a singleton object?

# Libraries
- How can we provide logging mechanisms inside Java application? What logging frameworks do you know?
- Why it's better to use logging frameworks instead of output to System.out?

# JMX
- What is JMX?
- Is JMX one way or two way communication protocol (read, write or read & write)?

# JMS
- Topic vs Queue in JMS
