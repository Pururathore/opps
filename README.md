# How to achieve Abstraction?

Abstraction is a process of hiding the implementation details and showing only functionality to the user. It only indicates important things to the user and hides the internal details, ie. While sending SMS, you just type the text and send the message. Here, you do not care about the internal processing of the message delivery. Abstraction can be achieved using Abstract Class and Abstract Method
          private void BindVideo()
            {
                Registration registration = new Registration();
                DataTable dt = new DataTable();
                try
                {
                    dt = registration.GetGetHomePageVideo();
                    if (!object.Equals(dt, null))
                    {
                        if (dt.Rows.Count > 0)
                        {
                            repeaterHomePageVideo.DataSource = dt;
                            repeaterHomePageVideo.DataBind();
                        }
                    }
                }
                catch (Exception ex)
                {
                }
            }

Abstract Class - A class which is declared “abstract” is called as an abstract class. It can have abstract methods as well as concrete methods. A normal class cannot have abstract methods.

Abstract Method - A method without a body is known as an Abstract Method. It must be declared in an abstract class. The abstract method will never be final because the abstract class must implement all the abstract methods.

Rules of Abstract Method-
1. Abstract methods do not have an implementation; it only has method signature
2. If a class is using an abstract method they must be declared abstract. The opposite cannot be true. This means that an abstract class does not necessarily have an abstract method.
3. If a regular class extends an abstract class, then that class must implement all the abstract methods of the abstract parent
Advantages of Abstraction
4. The main benefit of using an abstract class is that it allows you to group several related classes as siblings.
5. Abstraction helps to reduce the complexity of the design and implementation process of software.

# Difference between Abstraction and Encapsulation

Abstraction	Encapsulation
Abstraction solves the issues at the design level.	Encapsulation solves it implementation level.
Abstraction is about hiding unwanted details while showing most essential information.	Encapsulation means hiding the code and data into a single unit.

Abstraction allows focussing on what the information object must contain	Encapsulation means hiding the internal details or mechanics of how an object does something for security reasons.

Difference between Abstract Class and Interface

Abstract Class	Interface
An abstract class can have both abstract and non-abstract methods.	The interface can have only abstract methods.
It does not support multiple inheritances.	It supports multiple inheritances.
It can provide the implementation of the interface.	It can not provide the implementation of the abstract class.
An abstract class can have protected and abstract public methods.	An interface can have only have public abstract methods.
An abstract class can have final, static, or static final variable with any access specifier.	The interface can only have a public static final variable.
