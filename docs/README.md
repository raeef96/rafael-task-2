#### Exercise 2.45
- The method does not need to have any parameters, and the method is a mutator. 

#### Exercise 2.58
- because the balance is set to zero in the body of the method and the the new value of the balance would return rather than the old value.
- We can check this by inserting a certain amount in the ticket machine then use refundBalance(). it will give us the value 0 for balance instead of the value of the inserted amount that the original code give us.

#### Exercise 2.59 
- the code doesnt compile and bluej states that it is an unreachable statement. It is because the return statement ends the method, and anything added after the return statement in the body of the same method does not get executed.

#### Exercise 2.60
-The code wil compile, but the getPrice() will return zero raathar than cost of the ticket. Tis happens because of the insertion of the int type to price, price is being counted as a local variable and does not associate with the price field. 

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
