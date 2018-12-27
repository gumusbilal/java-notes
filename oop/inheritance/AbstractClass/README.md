# Abstract Class

![Abstract Class Image](https://www.guru99.com/images/uploads/2012/06/java-abstract-classes.jpg)

-  There are situations in which you will want to define a superclass that declares the structure of a given abstration without providing a complete implement ation of every method.
- That is, sometimes you will want to create a superclass that only defines a generalized form that will be shared by all of its subclasses, leaving it to each subclass to dills in the detail.
- One way this situation can occur is when a superclass is unable to create a meaningful implementation for a method.
- When you want some way to ensure that a subclass does, indeed, override all necessary methods. Java's solution is the abstract method.

> Syntax of abstract method :

        abstract typeName (parameter List); // No body

> Example:

        abstract void sum(int a, int b);

- These abstract methods are sometimes referred to as sub classes responsibility because they have no implementation specified in the superclass. Thus subclass must override them.