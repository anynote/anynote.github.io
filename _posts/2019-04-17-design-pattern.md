---
title:  "Design Pattern"
tags: design-pattern
---
The best practices adapted by experienced object-oriented software developers

## 3 types
### Creational
About class instantiation or object creation, further categorized into:

* `class-creation`: use inheritance effectively in the instantiation process
* `object-creation`: use delegation effectively to get the job done.

Creational design patterns are Factory Method, Abstract Factory, Builder, Singleton, Object Pool and Prototype.

### Structural
About organizing different classes and objects to form larger structures and provide new functionality.

* Adapter
* Bridge
* Composite
* Decorator
* Facade
* Flyweight
* Private Class Data
* Proxy

### Behavioral
About identifying common communication patterns between objects and realize these patterns.

* Chain of responsibility
* Command
* Interpreter
* Iterator
* Mediator
* Memento
* Null Object
* Observer
* State
* Strategy
* Template method
* Visitor

## Singleton

* Restricts the instantiation of a class to one object.

## Builder

* To “Separate the construction of a complex object from its representation so that the same construction process can create different representations.”
* To construct a complex object step by step and the final step will return the object.
* The process of constructing an object should be generic so that it can be used to create different representations of the same object.

# References
- [Geeks for Geeks - Software Design Patterns](https://www.geeksforgeeks.org/software-design-patterns/)
