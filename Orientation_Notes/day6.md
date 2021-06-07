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
create a hierarchy to save code basically.
### Class relationships
> OOP seeks to whenever possible eliminate redunant or repetive code. we want to promote code reuse.
- A class can:
   - inherit states and behaviors from another
   - IS-A relationship
   - create or contain an instance of another class
     - HAS-A relationship
    - aka composition or composite relaitonship.
    ## Abstraction
    the process of hiding implementation and processes of an entity to reduce complexity or increase understanding of a systems properties.
    - we do not need to know how something works we just need to know how to use it.
    - in java we achieve abstractions using abstract classes and interfaces. we dont need to know all the processes just that it works and how to run it.
    - the why of abstraction.
    - Abstract classes are structures that contain state and behaviors
      - if a behavior is reliant on what something i - > Abstract class
        - use abstract class when we want to have a common root class but dont want to instantiate it
    ** interfaces ** better define behaviors only.
      - if a behavior can be described serperately from the states interface
      - we use interface when we want to definte behavior only.
      - adding more hierarchial sturcture to our code with abstract classes
      - we use interfaces to add behaviors without affecting our parent class.
      - Java does not support multiple inheritance. being able to inherit from more than one class.
      - interface uses the keyword `implements`
         - and with interfaces we can implement as many as we would like.
    
Base root class that shares all these functionalities
## Project B
Doesnt have to be a tour of your home. creates a starting place.
- if you want to be creative :)
- how to figure the exits to work.
-Given a prompt and allowed to chose which way you want to go ie go north upstars etc. figure how to get the directions to an exit in an array so that you are brought into a room and then exits from the room.
make sure that they enter something valid.