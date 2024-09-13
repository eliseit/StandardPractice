Interview practice
-------------------

Motto: Practice creates perfection!


1. Coding Standards
2. Design Patterns

Java Coding Standards
======================


Naming Conventions:
--------------------

* Classes and Interfaces: Use CamelCase and start with an uppercase letter (e.g., EmployeeManager, StudentRecord).
* Methods and Variables: Use camelCase, starting with a lowercase letter (e.g., calculateSalary, studentName).
* Constants: Use ALL_CAPS with underscores between words (e.g., MAX_CAPACITY, PI).
 
Code Formatting:
------------------

* Indentation: Use 4 spaces (or tabs depending on project conventions).
* Line Length: Typically 80-100 characters per line.
* Braces: Opening braces should be on the same line (K&R style).
  
Error Handling:
----------------
* Always handle exceptions using try-catch blocks and avoid empty catch blocks.

Best Practices:
---------------
1. DRY (Don’t Repeat Yourself): Avoid code duplication.
2. KISS (Keep It Simple, Stupid): Simplify code wherever possible.
3. SOLID Principles: Apply them for maintainable and scalable code:
4. Single Responsibility
5. Open-Closed
6. Liskov Substitution
7. Interface Segregation
8. Dependency Inversion

General practice recommended reading:
* CODE COMPLETE 2nd ED Steve McConnell

Design Patterns
===============

Design patterns provide reusable solutions to common software design problems. They are typically divided into three categories:

Creational Patterns:
--------------------

## I. Singleton Pattern:
Ensures that a class has only one instance and provides a global point of access to it.

## II. Factory Pattern:
Defines an interface for creating objects, but lets subclasses decide which class to instantiate.

## III. Builder Pattern:
Useful for creating complex objects with multiple attributes.

Structural Patterns:
--------------------

## I. Adapter Pattern:
Allows incompatible interfaces to work together by creating an adapter.

## II. Decorator Pattern:
Adds additional responsibilities to an object dynamically.

Behavioral Patterns:
---------------------

## I. Observer Pattern:
Defines a one-to-many dependency between objects, so when one object changes state, all dependents are notified.

## II. Strategy Pattern:
Defines a family of algorithms and allows them to be interchangeable.

# Extended list:

This document provides a quick summary of various design patterns, organized into Creational, Structural, and Behavioral categories. These patterns are frequently used in Java to design flexible, maintainable, and reusable code.

## Creational Patterns

- **Singleton Pattern:** Ensures a class has only one instance and provides a global access point to that instance.
- **Factory Pattern:** Defines an interface for creating objects, but lets subclasses decide which class to instantiate.
- **Builder Pattern:** Builds complex objects step-by-step and allows for a more flexible object creation process.
- **Prototype Pattern:** Creates new objects by cloning an existing object, useful for reducing the cost of creating complex objects.
- **Abstract Factory Pattern:** Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

## Structural Patterns

- **Adapter Pattern:** Allows incompatible interfaces to work together by wrapping an object with an adapter that makes its interface compatible with other code.
- **Decorator Pattern:** Adds additional responsibilities to an object dynamically without modifying its structure.
- **Facade Pattern:** Provides a simplified interface to a complex system of classes, hiding the complexities of the system.
- **Composite Pattern:** Composes objects into tree-like structures to represent part-whole hierarchies. It allows clients to treat individual objects and compositions uniformly.
- **Bridge Pattern:** Decouples an abstraction from its implementation, allowing both to vary independently.
- **Flyweight Pattern:** Minimizes memory usage by sharing as much data as possible with other similar objects.

## Behavioral Patterns

- **Observer Pattern:** Establishes a one-to-many relationship between objects, so that when one object changes state, all its dependents are notified.
- **Strategy Pattern:** Defines a family of algorithms and allows them to be interchangeable at runtime.
- **Command Pattern:** Encapsulates a request as an object, allowing parameterization of clients with different requests and supporting undoable operations.
- **Chain of Responsibility Pattern:** Passes a request along a chain of potential handlers, where each handler decides to process or pass it further.
- **Mediator Pattern:** Defines an object that manages communications between different objects to reduce dependencies between them.
- **Memento Pattern:** Captures and restores an object's state without violating encapsulation, useful for undo operations.
- **Visitor Pattern:** Represents an operation to be performed on elements of an object structure without changing the classes of the elements.
- **State Pattern:** Allows an object to alter its behavior when its internal state changes, appearing as if the object changes its class.
- **Interpreter Pattern:** Defines a grammar for a language and provides an interpreter to process this grammar.

## Other Patterns

- **Proxy Pattern:** Provides a surrogate or placeholder for another object to control access to it.

## Usage

Design patterns are reusable solutions to common software design problems. They should be chosen based on the problem at hand, ensuring flexibility, modularity, and maintainability.

---