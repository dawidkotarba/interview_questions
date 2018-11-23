Good practices for concurrency:
- Avoid using wait/notify etc. methods from Object, use java.util.concurrent instead
- use ExecutorService instead of spawning threads manually
- always give a name to a thread
- synchronize smallest possible pieces of code, do not synchronize whole methods
- avoid sharing state, write pure methods
- prefer immutable objects, use immutable wrappers from JDK
- do not use old synchronized collections, use newer from java.util.concurrent. Do not synchronize i.e whole maps when we have ConcurrentHashMap with bucket synchronization
- remember to use try/finally wherever you need to unlock threads
- volatile gives additional overhead as cannot be cached

