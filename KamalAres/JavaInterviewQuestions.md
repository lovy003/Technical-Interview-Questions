# Java Interview Questions


## 1. What are the types of Java Applications?

There are mainly four types of Java applications that can be created using Java Programming:

1. Standalone Application - Desktop Application.
   The framework used: AWT and swing.
Example: Media Player, Antivirus.
2. Web Application - An application that runs on the server-side and creates a dynamic web page. The framework used: Servlet, Jsp, Spring.
3. Enterprise Application - Banking Application. The Framework used: EJB.
4. Mobile Application. The Framework used: Java ME.

## 2. What are the types of Java platforms?

There are four types of platforms or editions of Java:

1. Java SE (Standard Edition) - AWT, swing
2. Java EE (Enterprise Edition) - Spring, Servlet
3. Java ME (Mobile Edition)
4. Java FX 

## 3. Why is Java platform Independent?

The meaning of platform-independent is that the java compiled code(byte code) can run on any operating system.

1. Whenever a program is written in Java, the javac compiler compiles it to a class file or byte code.
2. The bytecode generated is a non-executable code and needs an interpreter to execute on a machine. This interpreter is the JVM and thus the Byte code is executed by the JVM.
3. In the case of Java it is the magic of the Byte code that makes it platform Independent. Java is a Write Once Run Anywhere Language.

## What are the features of Java?

The features of Java are:

1. Simple
2. Object-Oriented
3. Portable
4. Platform Independent
5. Robust
6. Secured
7. Architecture Neutral
8. Interpreted
9. High Performance
10. Multithreaded
11. Distributed
12. Dynamic

## 5. What is automatic garbage collection in Java?

Automatic Garbage Collection in Java is responsible to free heap memory by destroying unreachable objects. The unreachable objects are those which doesn't contain any reference to them. 

Even though the programmer is not responsible to destroy useless objects but it is highly recommended to make an object unreachable (thus eligible for Garbage Collection) if it is no longer required.

To make an object eligible for garbage collection:

1. Nullifying the reference variable.
2. Re-assigning the reference variable.
3. Object created inside the method.

## 6. Why Java is Robust?

Robust simply means Strong. Java is robust because:

1. It uses strong memory management.
2. There is a lack of a pointer that avoids security problems.
3. There is automatic garbage collection in Java which runs on the Java virtual machine to get rid of objects which are not being used by a Java application anymore.
3. There is an exception handline and type checking mechanism in Java.

## 7. Difference between JVM, JRE, and JDK?
### JVM

JVM (Java Virtual Machine) is an abstract machine. It is called a virtual machine because it doesn't physically exist. It is a specification that provides a runtime environment in which Java byte code can be executed.

There are three notions of the JVMs: specification, implementation, and instance.

The JVM performs the following main tasks:

1. Loads code
2. Verifies code
3. Executes code
4. Provides runtime environment

### JRE

JRE is an acronym for Java Runtime Environment. It is used to provide Runtime Environment. It is the implementation of JVM. It contains a set of libraries and other files that JVM uses at runtime.

### JDK

JDK is an acronym for Java Development Kit. The JDK is the software development environment that is used to develop Java applications.  It contains JRE and development tools.

## 8. What are Primitive and Non-Primitive Datatypes?

In Java, Primitive Data types are the building block of data manipulation.

There are 8 types of primitive data types:

1. boolean datatype - 1 bit
2. byte datatype - 1 byte
3. char datatype - 2 byte
4. short datatype - 2 byte
5. int datatype - 4 byte
6. long datatype - 8 byte
7. float datatype - 4 byte
8. double datatype - 8 byte

The Non-primitive datatype will contain a memory address of variables value because the reference types won't store the variable value directly in memory.

1. string
2. class
3. objects
4. interface
5. array

## 9. What is Unicode in java?


Unicode defines a fully international character set that can represent most of the world's written language.  Java uses a Unicode system and not ASCII so it takes 2 bytes for a charcter.  Lowest value:  '\u 0000' and Highest value: '\u FFFF'.

## 10. What is the OOPs concept you know?

Some of the important OOPs concepts are:

1. Object
2. Class
3. Encapsulation
4. Inheritance
5. Polymorphism
6. Abstraction

Apart from these,

1. Coupling
2. Cohesion
3. Association
4. Aggregation
5. Composition


### Prepared by:

* [KamalAres](https://github.com/KamalAres)
