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
