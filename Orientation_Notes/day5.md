# OOP
## 4 pillars of OOP
### Abstraction
 - The porcess of hiding implementation and processes of an entity to
 reduce complexity or increase understanding of a systems properties
 ie TV remote we dont know how it works. Press button the volume goes uo
 or down.
### Polymorphism
- the ability for objects classes variables and or methods to alter functionality while maintaining structure.
### inheritance
- The ability for entites to adobt variables and methods form a parent super class
this allows for instantiating child objects from said class
- is -a relationship
### Encapsulation
- the act of wrapping code into a single unit and then selectively exposing and restricting access to that code based on functionality or use within classes
- classes should allow minimum necessary access to their members.
- access to class variables should be done through methods that can perform validation or are designed specifically to perfomr mutation or accessing funcitonality.
- these methods are commonly referred to as getters and setters ("Accessors and mutators)
- least amount of access is standard practice
   - we want classes to be the only ones responsible for themselves
### Acess modifiers: how we achieve encapsulation in java
- public : accessible to all classes everywhere
 - private : accessible only within the current class.
 - protected : accessible to all classes in the same package ** and** all sublcasses/children
 - defualt package private : accessible to all classes in the same package
 - defualt is not common. denoted by the absence of an access modifier.
 - ACCESS MODIFIERS HAVE NOTHING TO DO WITH SCOPE
 they are unrelated but something that can be easily be confused
 access modifiers = > accessibility
 variable scopes = > visibility 
 Encapsulation is not protection/securitythere are ways to change access modifiers at runtime (Java reflections API) little tricky to be changed
 //Notes first of all
 ## Inheritance
 - Is-a relationship
 we use the extends keyword
 - essentially inheritance copies  *visible* variables and methods from a parent class into a child class.
 - it promotes code reusibility, reduces duplication and redundancy.
 - extend a class to take all the functionality dont repeat yourself
 - enables polymorphism and code flexibility
 - structures classes into an understandable hierarchy.
 > All classes in Java implicitly inherit from the Object class.
 > all objects inherit the Object clas attributes and behaviors - which we can can override to provide a unique implementation.
