Atomic types in Java:
- AtomicBoolean
- AtomicInteger
- AtomicIntegerArray
- AtomicIntegerFieldUpdater
- AtomicLong
- AtomicLongArray
- AtomicLongFieldUpdater
- AtomicReference

Atomic types use CAS (Compare and Swap technique):
- a thread retrieves existing value from the atomic type
- then a thread tries to set a new value (passing both values as arguments)
- the new value is set only if the retrieved previously value matches the current one (so it was not modified by another thread in the meantime). Therefore only one thread can update the value, other will fail.
- every thread gets the information whether it was successful or not, so it can retry with newest value

CAS is by nature like optimistic locking.


Example from https://www.baeldung.com/java-atomic-variables:

```java
public class SafeCounterWithoutLock {
    private final AtomicInteger counter = new AtomicInteger(0);

    public int getValue() {
        return counter.get();
    }
    public void increment() {
        while(true) {
            int existingValue = getValue();
            int newValue = existingValue + 1;
            if(counter.compareAndSet(existingValue, newValue)) {
                return;
            }
        }
    }
}
```
