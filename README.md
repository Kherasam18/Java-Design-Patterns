# 🧠 Java Design Patterns

This repository demonstrates **popular Design Patterns in Java**, each implemented in its own directory with example code and explanation.  
Design patterns help developers write **scalable, maintainable, and flexible software architectures**.

---

## 🏗️ Creational Patterns

### 🔹 Singleton
Ensures a class has only one instance and provides a global access point to it.  
Use when exactly one object is needed (e.g., logging, configuration, thread pools).

### 🔹 Factory
Defines an interface for creating objects but lets subclasses alter the type of objects created.  
Use when the exact class of object to create isn’t known until runtime.

### 🔹 Prototype
Creates new objects by copying an existing instance (the prototype).  
Use when object creation is costly and can be cloned instead (e.g., caching, document templates).

### 🔹 Builder *(optional addition if you later include it)*
Separates the construction of a complex object from its representation.  
Use when building complex objects with many optional parameters.

---

## ⚙️ Structural Patterns

### 🔹 Adapter
Converts the interface of a class into another interface clients expect.  
Use when integrating incompatible interfaces without modifying existing code.

### 🔹 Bridge
Separates abstraction from implementation so both can evolve independently.  
Use when you need to decouple abstraction layers, e.g., UI and platform rendering.

### 🔹 Composite
Composes objects into tree structures to represent part-whole hierarchies.  
Use when you want clients to treat individual objects and compositions uniformly.

### 🔹 Decorator
Attaches additional responsibilities to an object dynamically.  
Use when you need flexible alternatives to subclassing for extending functionality.

### 🔹 Dependency *(Dependency Injection / Inversion Principle)*
Manages object dependencies externally instead of hardcoding them inside classes.  
Use when promoting loose coupling and testability in your architecture.

---

## 🔄 Behavioral Patterns

### 🔹 Iterator
Provides a way to sequentially access elements of a collection without exposing its internal structure.  
Use when traversing different data structures uniformly.

### 🔹 Observer
Defines a one-to-many dependency where objects automatically update when the subject changes.  
Use in event-driven systems (e.g., GUI listeners, publish/subscribe systems).

### 🔹 State
Allows an object to change its behavior when its internal state changes.  
Use for finite state machines or workflows (e.g., order processing).

### 🔹 Strategy
Defines a family of algorithms, encapsulates each, and makes them interchangeable.  
Use when you want to select an algorithm’s behavior at runtime (e.g., sorting strategies, payment methods).

---
