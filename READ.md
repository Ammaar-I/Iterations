## Iteration
Java has three different control structures that allow the computer to perform iteration tasks: `for` loop, `while` loop, and `do ... while` loop.

### The `for` loop
The general form of a `for` loop is 
```java 
for ( initialization; termination conition; update statement){
  statement //body of loop
}
```

The termination condition is tested at the top of the loop; the update statement is performed at the bottom.

**Example**
```java
for(int i = 1; 1 < 5; i++){
  System.out.print(i + " ");
}
//output: 1 2 3 4
```