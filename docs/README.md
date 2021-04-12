#### Exercise 2.44
```java
public TicketMachine (){
    price = 20;
}
public TicketMachine (int thisPrice){
    thisPrice = price; 
}

```

#### Exercise 2.45
```java
public void empty(){
    total=0;
}
```

#### Exercise 2.61
```java
public int emptyMachine(){
    int beforeTotal = afterTotal;
    afterTotal = 0;
    return beforeTotal;
}
```
