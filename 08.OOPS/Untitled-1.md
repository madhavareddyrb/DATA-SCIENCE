# Module: Classes and Objects Assignments
## Lesson: Creating and Working with Classes and Objects
### Assignment 1: Basic Class and Object Creation

Create a class named `Car` with attributes `make`, `model`, and `year`. Create an object of the class and print its attributes.

### Assignment 2: Methods in Class

Add a method named `start_engine` to the `Car` class that prints a message when the engine starts. Create an object of the class and call the method.

### Assignment 3: Class with Constructor

Create a class named `Student` with attributes `name` and `age`. Use a constructor to initialize these attributes. Create an object of the class and print its attributes.

### Assignment 4: Class with Private Attributes

Create a class named `BankAccount` with private attributes `account_number` and `balance`. Add methods to deposit and withdraw money, and to check the balance. Create an object of the class and perform some operations.

### Assignment 5: Class Inheritance

Create a base class named `Person` with attributes `name` and `age`. Create a derived class named `Employee` that inherits from `Person` and adds an attribute `employee_id`. Create an object of the derived class and print its attributes.

### Assignment 6: Method Overriding

In the `Employee` class, override the `__str__` method to return a string representation of the object. Create an object of the class and print it.

### Assignment 7: Class Composition

Create a class named `Address` with attributes `street`, `city`, and `zipcode`. Create a class named `Person` that has an `Address` object as an attribute. Create an object of the `Person` class and print its address.

### Assignment 8: Class with Class Variables

Create a class named `Counter` with a class variable `count`. Each time an object is created, increment the count. Add a method to get the current count. Create multiple objects and print the count.

### Assignment 9: Static Methods

Create a class named `MathOperations` with a static method to calculate the square root of a number. Call the static method without creating an object.

### Assignment 10: Class with Properties

Create a class named `Rectangle` with private attributes `length` and `width`. Use properties to get and set these attributes. Create an object of the class and test the properties.

### Assignment 11: Abstract Base Class

Create an abstract base class named `Shape` with an abstract method `area`. Create derived classes `Circle` and `Square` that implement the `area` method. Create objects of the derived classes and call the `area` method.

### Assignment 12: Operator Overloading

Create a class named `Vector` with attributes `x` and `y`. Overload the `+` operator to add two `Vector` objects. Create objects of the class and test the operator overloading.

### Assignment 13: Class with Custom Exception

Create a custom exception named `InsufficientBalanceError`. In the `BankAccount` class, raise this exception when a withdrawal amount is greater than the balance. Handle the exception and print an appropriate message.

### Assignment 14: Class with Context Manager

Create a class named `FileManager` that implements the context manager protocol to open and close a file. Use this class to read the contents of a file.

### Assignment 15: Chaining Methods

Create a class named `Calculator` with methods to add, subtract, multiply, and divide. Each method should return the object itself to allow method chaining. Create an object and chain multiple method calls.