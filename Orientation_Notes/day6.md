## PolyMorphism
- ability for Java to take advantage of the difference between a reference variable and an object in memory when the two are related by inheritance
- an objects type determines the behaviors it has, the reference variable type determines which behaviors can be accessed.
- 2 seperate entities basically
- an objects type determines the behaviors it has 
- the reference variable type determins which behaviors can be accessed.
**Method overloading and method overriding**
method overriding chaning the implementation of an inheritaed behavior
@override
- method overloading multiple implemenations of a single behaciors by changed the number or type of parameters.
** covariance covariant typing 
- referencing an instance of a superclass using its subclass (or vice versa)
```java
Car c = new Subaru();
```
can upcast and change a reference variable.