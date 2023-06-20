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

# Object-Oriented Programming

1. **What are the four principles of object-oriented programming?**
   - The four principles are encapsulation, inheritance, polymorphism, and abstraction. These principles promote code reusability, maintainability, and flexibility in object-oriented systems.

2. **Explain the concept of inheritance in Java.**
   - Inheritance is a mechanism in Java that allows a class to inherit properties and behaviors from another class. It promotes code reuse by enabling the subclass to access the members (methods and fields) of the superclass. It supports the "is-a" relationship between classes.

3. **What is method overriding in Java? Provide an example.**
   - Method overriding occurs when a subclass provides its implementation for a method that is already defined in its superclass. The method in the subclass must have the same name, return type, and parameters as the method in the superclass. Here's an example:

    ```java
    class Animal {
        public void makeSound() {
            System.out.println("The animal makes a sound.");
        }
    }

    class Dog extends Animal {
        @Override
        public void makeSound() {
            System.out.println("The dog barks.");
        }
    }

    // Usage:
    Animal animal = new Dog();
    animal.makeSound(); // Output: "The dog barks."
    ```

4. **Explain the concept of encapsulation in Java.**
   - Encapsulation is the process of hiding the internal details and implementation of a class and providing a public interface for interaction. It protects the data and prevents direct access to it from outside the class. Access to the data is controlled through getter and setter methods, allowing the class to maintain its integrity.

5. **What is the difference between composition and inheritance?**
   - Composition is a relationship between classes where one class contains an instance of another class as a member variable. It represents a "has-a" relationship. In contrast, inheritance is a relationship between classes where one class inherits properties and behaviors from another class. It represents an "is-a" relationship. Composition is typically more flexible and favors code reusability.

6. **What is the difference between method overloading and method overriding?**
   - Method overloading occurs when a class has multiple methods with the same name but different parameters. The methods are distinguished based on their parameter types and/or the number of parameters. Method overriding occurs when a subclass provides its implementation for a method that is already defined in its superclass. The methods must have the same name, return type, and parameters.

7. **What is the concept of polymorphism in Java?**
   - Polymorphism allows an object to take different forms or behave differently based on the context. In Java, polymorphism is achieved through method overriding and method overloading. It enables code flexibility, extensibility, and abstraction.

8. **What is an abstract class in Java?**
   - An abstract class is a class that cannot be instantiated and is meant to be subclassed. It can contain both abstract and concrete methods. Abstract methods are declared without an implementation and must be implemented by the subclasses. Abstract classes serve as a blueprint for the subclasses to provide common characteristics and behaviors.

9. **What is an interface in Java?**
   - An interface in Java is a collection of abstract methods that defines a contract for classes to implement. It provides a way to achieve multiple inheritances in Java. Classes implement interfaces by providing implementations for all the methods defined in the interface. Interfaces are used to achieve abstraction and promote loose coupling.

10. **What is the difference between a class and an object in Java?**
    - A class in Java is a blueprint or a template that defines the structure and behavior of objects. It describes the state (fields) and behavior (methods) that objects of that class can have. An object, on the other hand, is an instance of a class. It represents a specific occurrence or entity based on the defined class.



