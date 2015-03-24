# Software Design Patterns

## Types of design patterns
1. [Behavioral patterns](#behavioral-patterns)
2. [Concurrency patterns](#concurrency-patterns)
3. [Creational patterns](#creational-patterns)
4. [Decoupling patterns](#decoupling-patterns)
5. [Optimization patterns](#optimization-patterns)
6. [Sequencing patterns](#sequencing-patterns)
7. [Structural patterns](#structural-patterns)

###Behavioral patterns
1. **Blackboard:**
Generalized observer, which allows multiple readers and writers. Communicates information system-wide.
WIKI
2. **Bytecode:**
Give behavior the flexibility of data by encoding it as instructions for a virtual machine.
GPP
3. **Chain of Responsibility:**
Avoid coupling the sender of a request to its receiver by giving more then one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.
CS
4. **Command:**
Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.
CS
6. **Interpreter:**
Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.
CS
7. **Iterator:**
Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
CS
8. **Mediator:**
Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and lets you vary their interaction independently.
CS
9. **Memento:**
Without violating encapsulation, capture and externalize an object’s internal state so that the object can be restored to this state later.
CS
10. **Null object:**
Avoid null references by providing a default object.
WIKI
11. **Observer or publish/subscribe:**
Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
CS
12. **Servant:**
Define common functionality for a group of classes.
WIKI
13. **Specification:**
Recombinable business logic in a Boolean fashion.
WIKI
15. **State:**
Allow an object to alter its behavior when its internal state changes. The object will appear to change its class. CS
15. **Strategy:**
Defines a family of algorithms, encapsulates each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients who use it.
CS
16. **Subclass Sandbox:**
Define behavior in a subclass using a set of operations provided by its base class.
GPP
17. **Template method:**
Define a skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithms structure.
CS
18. **Type Object:**
Allow the flexible creation of new “classes” by creating a single class, each instance of which represents a different type of object.
GPP
19. **Visitor:**
Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.
CS

![Visitor.uml](http://yuml.me/cd5c5e05)

###Concurrency patterns
1. **Active object:**
Decouples method execution from method invocation that reside in their own thread of control. The goal is to introduce concurrency, by using asynchronous method invocation and a scheduler for handling requests.
WIKI
2. **Balking:**
Only execute an action on an object when the object is in a particular state.
WIKI
3. **Barrier:**
3. **Binding properties:**
Combining multiple observers to force properties in different objects to be synchronized or coordinated in some way.
WIKI
4. **Disruptor:**
5. **Double-checked locking:**
Reduce the overhead of acquiring a lock by first testing the locking criterion (the 'lock hint') in an unsafe manner; only if that succeeds does the actual lock proceed.
Can be unsafe when implemented in some language/hardware combinations. It can therefore sometimes be considered an anti-pattern.
WIKI
5. **Event-based asynchronous:**
Addresses problems with the asynchronous pattern that occur in multithreaded programs.
WIKI
6. **Guarded suspension:**
Manages operations that require both a lock to be acquired and a precondition to be satisfied before the operation can be executed.
WIKI
6. **Join:**
Join-patterns provides a way to write concurrent, parallel and distributed programs by message passing. Compared to the use of threads and locks, this is a high level programming model.
WIKI
7. **Leaders/followers pattern:**
6. **Lock:**
One thread puts a "lock" on a resource, preventing other threads from accessing or modifying it.
WIKI
7. **Messaging design pattern (MDP):**
Allows the interchange of information (i.e. messages) between components and applications.
WIKI
8. **Monitor object:**
An object whose methods are subject to mutual exclusion, thus preventing multiple objects from erroneously trying to use it at the same time.
WIKI
9. **Reactor:** 
A reactor object provides an asynchronous interface to resources that must be handled synchronously.
WIKI
10. **Read write lock:**
Allows concurrent read access to an object, but requires exclusive access for write operations.
WIKI
11. **Scheduler pattern:**
Explicitly control when threads may execute single-threaded code.
WIKI
12. **Thread pool pattern:**
A number of threads are created to perform a number of tasks, which are usually organized in a queue.
Typically, there are many more tasks than threads. Can be considered a special case of the object pool pattern.
WIKI
13. **Thread-local storage (TLC):**
Static or "global" memory local to a thread.
WIKI

###Creational patterns
1. **Abstract Factory:**
Provide an interface for creating families of related or dependent objects without specifying their concrete classes.
CS
2. **Builder:**
Separate the construction of a complex object from its representation so that the same construction processes can create different representations.
CS
3. **Factory Method:**
Define an interface for creating an object, but let the subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.
cs
4. **Multiton:**
5. **Object pool:**
6. **Prototype:**
Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype.
CS
7. **Resource acquisition is initialization:**
8. **Singleton:**
Ensure a class only has one instance, and provide a global point of access to it.
CS

###Decoupling Patterns
1. **Component:**
2. **Event Queue:**
3. **Service Locator:**

###Optimization Patterns
1. **Data Locality:**
2. **Dirty Flag:**
3. **Object Pool:**
4. **Spatial Partition:**

### Sequencing Patterns
1. **Double Buffer:**
2. **Game Loop:**
3. **Update Method:**

###Structural patterns
1. **Adapter/Wrapper/Translator:**
Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn’t otherwise because of incompatibility interfaces.
CS
2. **Bridge:**
Decouple an abstraction from its implementation so that the two can vary independently.
CS
3. **Composite:**
Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.
CS
4. **Decorator:**
Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality.
CS
5. **Façade:**
Provide a unified interface to a set of interfaces in a system. Façade defines a higher-level interface that makes the subsystem easier to use.
CS
6. **Flyweight:**
Use sharing to support large numbers of fine-grained objects efficiently. A flyweight is a shared object that can be used in multiple contexts simultaneously.
The flyweight acts as an independent object in each context; it’s indistinguishable from an instance of the object that’s not shared.
CS
7. **Front controller:**
The pattern relates to the design of Web applications. It provides a centralized entry point for handling requests.
WIKI
8. **Module:** (structural)
9. **Proxy:**
Provide a surrogate or placeholder for another object to control access to it.
CS
10. **Twin:** (structural)

## Books
1. The 23 Gang of Four Design Patterns
2. Code Complete
3. Pattern-oriented software architecture 
4. Patterns of Enterprise Application Architecture

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
10. http://gameprogrammingpatterns.com/contents.html (2015-03-17)
