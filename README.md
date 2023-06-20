# Java Interview Questions

Welcome to the Java Interview Questions repository! This collection provides a set of commonly asked interview questions for Java developers. It's designed to help you prepare for Java programming interviews and strengthen your understanding of key concepts.

## Table of Contents

- [General Questions](#general-questions)
- [Object-Oriented Programming](#object-oriented-programming)
- [Java Core Concepts](#java-core-concepts)
- [Data Structures](#data-structures)
- [Algorithms](#algorithms)

# General Questions

1. **What is Java Virtual Machine (JVM)?**
   - JVM is an essential part of the Java platform that executes Java bytecode. It provides a runtime environment and enables Java programs to run on any device or operating system.

2. **Explain the differences between `ArrayList` and `LinkedList`.**
   - `ArrayList` is implemented as a resizable array and provides fast element access but slower insertions and deletions. In contrast, `LinkedList` is implemented as a doubly linked list and offers fast insertions and deletions but slower element access.

3. **What is the difference between an abstract class and an interface?**
   - An abstract class can have both concrete and abstract methods, while an interface can only have abstract methods. Additionally, a class can implement multiple interfaces but can inherit from only one abstract class.

4. **What is the `final` keyword in Java?**
   - The `final` keyword can be applied to classes, methods, and variables. When applied to a class, it indicates that the class cannot be subclassed. When applied to a method, it prevents the method from being overridden in subclasses. When applied to a variable, it makes the variable constant, and its value cannot be modified once assigned.

5. **What is the purpose of the `static` keyword in Java?**
   - The `static` keyword is used to define class-level members (methods and variables) that can be accessed without creating an instance of the class. Static methods can be called using the class name, while static variables are shared among all instances of the class.

6. **Explain the difference between checked and unchecked exceptions in Java.**
   - Checked exceptions are checked at compile-time and require explicit handling using try-catch blocks or declaring them in the method signature using the `throws` keyword. Unchecked exceptions, on the other hand, are not checked at compile-time, and handling them is optional.

7. **What is the difference between `StringBuilder` and `StringBuffer` classes?**
   - Both `StringBuilder` and `StringBuffer` are used for string manipulation, but `StringBuilder` is not thread-safe, whereas `StringBuffer` is thread-safe. Therefore, if thread-safety is not a concern, using `StringBuilder` is generally more efficient.

8. **What are the access modifiers in Java?**
   - Java has four access modifiers: `public`, `protected`, `default` (no explicit modifier), and `private`. They determine the accessibility of classes, methods, and variables. `public` allows access from any class, `protected` allows access from the same package or subclass, `default` allows access from the same package only, and `private` restricts access to the same class only.

9. **What is the difference between `==` and `equals()` in Java?**
   - The `==` operator compares the references of objects or primitive values for equality. In contrast, the `equals()` method is used to compare the contents of objects for equality. The `equals()` method can be overridden by classes to provide custom comparison logic.

10. **What is autoboxing and unboxing in Java?**
    - Autoboxing is the automatic conversion of primitive types to their corresponding wrapper classes (e.g., `int` to `Integer`) when needed. Unboxing is the opposite process of converting wrapper class objects back to primitive types. Java automatically performs these conversions behind the scenes.


