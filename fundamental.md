# Fundamental Design Pattern - Delegation

1. **Code Reusability**: Delegation pattern is often used to achieve code reuse by delegating specific functionality or behavior to another object. This allows you to encapsulate common functionality in a separate class and delegate the implementation details to that class, promoting code reuse and modularity.

2. **Composition over Inheritance**: Delegation pattern is favored over inheritance when you want to avoid the limitations and complexities associated with class inheritance. Instead of inheriting from a base class, you can delegate functionality to a separate class, allowing for greater flexibility and reducing the coupling between classes.

3. **Interface Segregation**: Delegation pattern can be used to implement interface segregation, where an object only exposes a specific set of methods that it delegates to another object. By delegating the implementation of certain methods to another class, you can create more focused and cohesive interfaces, promoting better separation of concerns.

4. **Runtime Behavior Modification**: Delegation pattern allows you to modify or extend the behavior of an object at runtime by swapping the delegate object. This can be useful when you need to dynamically change the behavior of an object without modifying its core implementation.

5. **Wrapper or Adapter Classes**: Delegation pattern can be used to wrap or adapt the functionality of an existing class by delegating the method calls to the wrapped object. This is useful when you want to add additional functionality, modify behavior, or provide a different interface to an existing class without modifying its source code.

6. **Event Handling**: Delegation pattern is commonly used in event-driven programming to handle events. Instead of implementing event handling logic directly in a class, the class delegates the event handling to a separate event handler or callback object. This allows for better separation of concerns and makes the code more maintainable and extensible.

7. **Security and Access Control**: Delegation pattern can be used to enforce security and access control by delegating authorization and permission checks to a separate security object. This allows for centralized control and management of access rights, ensuring that only authorized operations are performed.

These are just a few examples of the use cases for the delegation pattern. The actual implementation and application of the pattern will depend on the specific requirements and design considerations of your project.