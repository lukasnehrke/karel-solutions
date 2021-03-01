# 2.2.2 decrement

## Lösung

```java
void decrement() {
    while (!onBeeper()) {
        dropBeeper();
        moveForward();
    }
    pickBeeper(); 
}
```
