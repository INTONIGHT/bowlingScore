## types of languages
- binary
  - lowest level
  - not actually written
  - 0s and 1s light or electrical current. 
- assembly
   - language used by the processor(CPU) to generate binary
   - it is meant to be machine readable.
- compiled 
 - written in plain text so they need to be transformed into 
 another form that can be directly used by the CPU
 or another application(interpreted language)
 - java is compiled
- interpreted / scripting languages
     - treated as a series of instructions by other software which in turn gewnerate assembly 
    - generally they are not human readbale but scripting are
- markup
- used by another application to give context or to describe static content.
- **not a programming language**
## Java Notes
> Java is very OOP(object oriented Programming) This is by design
- java was going for scalability. create large apps.
- python = > readibility 
- Javascript = >flexibility
- Java is not flexible forces into good patterns. 
- Java runs on the JVM(java virtual machine)
   - allows it to run on any device that has a JVM.
   - Java has a massive ecosystem of software and support
   - Has great frameworks(Spring)
   ### **Core Features**
   - automatic memory management (garbage collection)
   - developers are not responsible for managing memory (like in C)
   - Object oriented
   - classes and interfaces
   - objects and methods
   - strongly and staticly typed
      - strong a variable cannot change its type once it has been assigned
      - staticly a variables type must be declared when it is created
    - compiled language
      - souce code written into a `.java` file human readable text
      this compiles into a .class file into java byte to be read by a machine and that is not meant for humans.
      cant do 5 + "5" like js.
## JDK JRE JVM
- JDK
  - java dev kit software development for developing java apps
    - a kit that provides the environment to develop and execute java programs.
    - includes :
      - JRE
      - interpreter/loader (java)
      - compiler(javac)
      - other tools needed in java development.
- JRE
  - java runtime environment
    - provides the minimum requirement for excuting a java application.
      - provides enironment to run and only run not develop Java programs
      -consists of :
        -JVM
        - core libraries classes and supporting files.
- JVM 
  - java virtual machine instance of the JRE at runtime
    - WORA (write once run anywhere)
      - any java program will work the same on any device with a JVM.
      
