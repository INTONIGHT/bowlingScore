### stack and heap
java handle memory management for us
## the heap term
the term for memory in jhava all objects are stored in the heap
**The stack** stack memory is used for static memory allocation
and the execution of a thread.
faste when compared to heap memory
- includes :
     - primitives 
        - they never leave the stack unless attached to an object
        - THis is what makes them fast to work with esp wrappers
    - LiFO : last in first out
    - reference variables point to a location in the heap where an object is stored
        - LIFO - new method called = ? new block on top of the stack  (contains everything it needs for the method to run) = > method executes = > the stack pushes off the block.
    **Memory Structure** 
    - variables are stored in memory
    - a specific location in memory is called an "address"
         - each address stores a single byte of data
         - most variables then occupy multiple addressed
         - the number of addresses reserved determines value range (binary)
        **Referance Variables**
        - stored the memory address or reference to an object in memory
        - Objects have to reserve enough memory to hold all the variables stored for that single object.
          - the memory reserved for an object might contain references to other objects which contain others etc
          - this confusion and messiness is why Java lets us ignore memory management
        *The reference variable is not the object... its the door through which the object is accessed*
    **Pass-by-value**
     - Java is always pass by value.
     with primitives:
      - Java creates a copy of the variable being passed into a method


    - with Objects (References) 
    - Java creates a copy of the reference and passes it to the method 
    but it still points to the same memory address.
    - check out encapsulation. 