# Design Patterns

### Creational Patterns

- __Factory__ also known as __Simple Factory__:
  - Creates objects without exposing the instantiation logic to the client.
- __Factory Method__:
  - Define an interface for creating an object, but let subclasses decide which class to instantiate.
- __Abstract Factory__:
  - Provide an interface for creating families of related or dependent objects without specifying their concrete classes.
- __Builder__:
  - Separate the construction of a complex object from its representation so that the same construction process can create different representations.
- __Prototype__:
  - Specify the kind of objects to create using a prototypical instance, and create new objects by copying this prototype.
- __Singleton__:
  - Ensure a class has only one instance and provide a global point of access to it.

### Structural Patterns

- __Adapter__:
  - Convert the interface of a class into another interface clients expect. Adapter lets classes work together that couldn't otherwise because of incompatible interfaces.
- __Bridge__:
  - Decouple an abstraction from its implementation so that the two can vary independently.
- __Composite__:
  - Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.
- __Decorator__:
  -  Attach additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality. 
- __Facade__:
  -  Provide a unified interface to a set of interfaces in a subsystem. Façade defines a higher-level interface that makes the subsystem easier to use.
- __Flyweight__:
  - Use sharing to support large numbers of fine-grained objects efficiently. 
- __Proxy__:
  - Provide a surrogate or placeholder for another object to control access to it.

### Behavioral Patterns

- __Chain of Responsibility__:
  - Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.
- __Command__:
  - Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.
- __Iterator__:
  - Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
- __Interpreter__:
  - Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.
- __Mediator__:
  - Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently.
- __Memento__:
  - Without violating encapsulation, capture and externalize an object's internal state so that the object can be restored to this state later.
- __Observer__:
  - Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.   
- __State__:
  - Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.
- __Strategy__:
  - Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it.
- __Template Method__:
  - Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.
- __Visitor__:
  - Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates. 
