# Software Design Patterns

## Types of design patterns

1. Behavioral pattern
2. Concurrency pattern
3. Creational pattern
4. Structural pattern

## The 23 Gang of Four Design Patterns (Cheat Sheet)
 
1. **Strategy:**
Defines a family of algorithms, encapsulates each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients who use it. (behavioral)
 
2. **Decorator:**
Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality. (structural)
 
3. **Factory Method:**
Define an interface for creating an object, but let the subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses. (creational)
 
4. **Observer:**
Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically. (behavioral)
 
5. **Chain of Responsibility:**
Avoid coupling the sender of a request to its receiver by giving more then one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it. (behavioral)
 
6. **Singleton:**
Ensure a class only has one instance, and provide a global point of access to it. (creational)
 
7. **Flyweight:**
Use sharing to support large numbers of fine-grained objects efficiently. A flyweight is a shared object that can be used in multiple contexts simultaneously. The flyweight acts as an independent object in each context; it’s indistinguishable from an instance of the object that’s not shared. (structural)
 
8. **Adapter/Wrapper/Translator:**
Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn’t otherwise because of incompatibility interfaces. (structural)
 
9. **Façade:**
Provide a unified interface to a set of interfaces in a system. Façade defines a higher-level interface that makes the subsystem easier to use. (structural)
 
10. **Template method:**
Define a skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithms structure. (behavioral)
 
11. **Builder:**
Separate the construction of a complex object from its representation so that the same construction processes can create different representations. (creational)
 
12. **Iterator:**
Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation. (behavioral)
 
13. **Composite:**
Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly. (structural)

14. **Command:**
Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations. (behavioral)
 
15. **Mediator:**
Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and lets you vary their interaction independently. (behavioral)
 
16. **State:**
Allow an object to alter its behavior when its internal state changes. The object will appear to change its class. (behavioral)
 
17. **Proxy:**
Provide a surrogate or placeholder for another object to control access to it. (structural)
 
18. **Abstract Factory:**
Provide an interface for creating families of related or dependent objects without specifying their concrete classes. (creational)
 
19. **Bridge:**
Decouple an abstraction from its implementation so that the two can vary independently. (structural)
 
20. **Interpreter:**
Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language. (behavioral)
 
21. **Memento:**
Without violating encapsulation, capture and externalize an object’s internal state so that the object can be restored to this state later. (behavioral)
 
22. **Prototype:**
Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype. (creational)
 
23. **Visitor:**
Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates. (behavioral)

## Concurrency patterns

1. **Active object**

2. **Balking pattern**

3. **Binding properties**

3. **Barrier**

4. **Disruptor**

5. **Double-checked locking**

5. **Event-based asynchronous**

6. **Guarded suspension**

6. **Join**

6. **Lock**

7. **Leaders/followers pattern**

7. **Messaging design pattern (MDP)**

8. **Monitor object**

9. **Reactor pattern** 

10. **Read write lock pattern**

11. **Scheduler pattern**

12. **Thread pool pattern**

13. **Thread-local storage**

## Code Complete

1. **Front controller**

## Pattern-oriented software architecture 

## Not in the list

1. **Multiton** (creational)
2. **Object pool** (creational)
3. **Resource acquisition is initialization** (creational)
4. **Module** (structural)
5. **Twin** (structural)
6. **Blackboard** (behavioral)
7. **Null object** (behavioral)
8. **Servant** (behavioral)
9. **Specification** (behavioral)

##  Patterns of Enterprise Application Architecture

## Sources

1. https://social.msdn.microsoft.com/forums/en-US/af062e83-3e61-45d4-aeaa-d30b4366c6a2/the-23-gang-of-four-design-patterns-cheat-sheet  (2015-03-17)
2. https://en.wikipedia.org/wiki/Software_design_pattern (2015-03-17)
3. https://en.wikipedia.org/wiki/Design_Patterns (2015-03-17)
4. https://en.wikipedia.org/wiki/Code_Complete (2015-03-17)
5. https://en.wikipedia.org/wiki/Behavioral_pattern (2015-03-17)
6. https://en.wikipedia.org/wiki/Creational_pattern (2015-03-17)
7. https://en.wikipedia.org/wiki/Concurrency_pattern (2015-03-17)
8. https://en.wikipedia.org/wiki/Structural_pattern (2015-03-17)
9. http://www.amazon.com/Pattern-Oriented-Software-Architecture-Concurrent-Networked/dp/0471606952/ref=sr_1_1?s=books&ie=UTF8&qid=1426625009&sr=1-1&keywords=Pattern-Oriented+Software+Architecture+2 (2015-03-17)
