# Compilation: Catching Errors

- Java is a compiled programming language
- code in .java file -> transformed into byte code by a compiler -> byte code is executed by the Java Virtual 
  Machine on your pc
- compiler: program that translates human-friendly programming languages into other programming languages that 
  computers can execute

MyProgram.Java -> Compiler -> MyProgram.class -> JVM -> 1000101 -> MyProgram

- the compiling process runs checks and catches mistakes while transforming code; code that doesn't pass these 
  checks won't be compiled
- Compile file Plankton.java with the terminal command:

````java
javac Plankton.java
````

- successful compilation produces Plankton.class file
- Execute .class file with terminal command:

````java
java Plankton
````

