How to achieve Abstraction?

Abstraction is a process of hiding the implementation details and showing only functionality to the user. It only indicates important things to the user and hides the internal details, ie. While sending SMS, you just type the text and send the message. Here, you do not care about the internal processing of the message delivery. Abstraction can be achieved using Abstract Class and Abstract Method

Abstract Class - A class which is declared “abstract” is called as an abstract class. It can have abstract methods as well as concrete methods. A normal class cannot have abstract methods.

Abstract Method - A method without a body is known as an Abstract Method. It must be declared in an abstract class. The abstract method will never be final because the abstract class must implement all the abstract methods.

Rules of Abstract Method-
1. Abstract methods do not have an implementation; it only has method signature
2. If a class is using an abstract method they must be declared abstract. The opposite cannot be true. This means that an abstract class does not necessarily have an abstract method.
3. If a regular class extends an abstract class, then that class must implement all the abstract methods of the abstract parent
Advantages of Abstraction
4. The main benefit of using an abstract class is that it allows you to group several related classes as siblings.
5. Abstraction helps to reduce the complexity of the design and implementation process of software.
