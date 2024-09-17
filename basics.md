
# Java Basic Interview Questions

## 1. What is Java?
Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA).

## 2. What are the main features of Java?
- **Object-Oriented**: Java is based on the Object-Oriented Programming (OOP) model.
- **Platform Independent**: Java code can be run on any platform without the need for recompilation.
- **Simple and Easy to Understand**: Java has a clear and concise syntax.
- **Secure**: It provides a secure environment by eliminating explicit pointer use and implementing a security manager.
- **Multithreaded**: Java supports multithreaded programming.
- **Portable**: Java's bytecode is platform-independent, making Java applications portable.

## 3. What is the difference between JDK, JRE, and JVM?
- **JDK (Java Development Kit)**: It provides an environment to develop and execute Java programs. It includes JRE and development tools.
- **JRE (Java Runtime Environment)**: It provides the libraries, Java Virtual Machine (JVM), and other components to run applications written in Java.
- **JVM (Java Virtual Machine)**: It is an abstract machine that provides the runtime environment in which Java bytecode can be executed.

## 4. What are the OOP principles in Java?
- **Encapsulation**: Wrapping data (variables) and code (methods) into a single unit, known as a class.
- **Inheritance**: The process by which one class acquires the properties (methods and fields) of another class.
- **Polymorphism**: The ability of a variable, function, or object to take on multiple forms.
- **Abstraction**: Hiding the complex implementation details and showing only the essential features of the object.

## 5. What is the difference between "== operator" and "equals()" method in Java?
- The **== operator** compares the reference or memory location of objects.
- The **equals()** method compares the contents or values within the objects.

## 6. What is the main() method in Java?
The `main()` method is the entry point of any Java program. It has the following syntax:
```java
public static void main(String[] args) {
    // code
}
```
- **public**: It is accessible from anywhere.
- **static**: It can be called without creating an instance of the class.
- **void**: It does not return any value.
- **String[] args**: It accepts command-line arguments.

## 7. What are Java access modifiers?
Java has four access modifiers:
- **public**: The code is accessible from any other class.
- **private**: The code is only accessible within the declared class.
- **protected**: The code is accessible within the same package and subclasses.
- **default** (no modifier): The code is only accessible within the same package.

## 8. What is a constructor in Java?
A constructor is a block of code that initializes a newly created object. It has the same name as the class and no return type.

## 9. What is the difference between an interface and an abstract class in Java?
- **Interface**: It can have only abstract methods (until Java 8, where default and static methods were introduced).
- **Abstract class**: It can have both abstract and non-abstract methods.

## 10. What are wrapper classes in Java?
Wrapper classes provide a way to use primitive data types (int, char, etc.) as objects. Example: `Integer`, `Character`, `Double`.

## 11. What is the use of the `final` keyword in Java?
- **final variable**: Its value cannot be changed once assigned.
- **final method**: It cannot be overridden by subclasses.
- **final class**: It cannot be subclassed.

## 12. What is exception handling in Java?
Exception handling in Java is a mechanism to handle runtime errors. It uses five keywords: `try`, `catch`, `finally`, `throw`, and `throws`.

## 13. What is the difference between checked and unchecked exceptions?
- **Checked exceptions**: These are exceptions that are checked at compile time. Example: `IOException`.
- **Unchecked exceptions**: These are exceptions that are not checked at compile time. Example: `ArithmeticException`.

## 14. What is multithreading in Java?
Multithreading is a Java feature that allows the concurrent execution of two or more threads. It maximizes the utilization of CPU.

## 15. What are Java Collections?
The Java Collections framework provides a set of classes and interfaces that implement commonly reusable collection data structures like List, Set, Map, etc.

## 16. What is the difference between ArrayList and LinkedList in Java?
- **ArrayList**: Uses a dynamic array to store elements. It is better for storing and accessing data.
- **LinkedList**: Uses a doubly linked list to store elements. It is better for manipulating data (insertion, deletion).

## 17. What is the `StringBuilder` class, and how is it different from `String`?
- **String**: Immutable. Every modification creates a new `String` object.
- **StringBuilder**: Mutable. It allows changes to the string without creating a new object.

## 18. What is a Java Stream?
A Java Stream is a sequence of elements supporting sequential and parallel aggregate operations. Streams can be created from Collections, Lists, Sets, ints, longs, doubles, arrays, and I/O channels.

## 19. What is garbage collection in Java?
Garbage collection is the process by which Java programs perform automatic memory management. The Java runtime environment deletes objects that are no longer in use to free up memory.

## 20. What is the difference between `throw` and `throws`?
- **throw**: Used to explicitly throw an exception.
- **throws**: Used in a method signature to indicate that the method may throw an exception.

