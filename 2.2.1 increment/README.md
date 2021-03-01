# 2.2.1 increment

## Lösung

```java
void increment() {
    while (onBeeper()) {
        pickBeeper();
        moveForward();
    }
    dropBeeper();
}
```
