# OOPCourse
OOP Course notes and solutions.

Course Link: https://www.linkedin.com/learning/programming-foundations-object-oriented-design-3
Course Name: Programming Foundations: Object-Oriented Design
Auth:  Olivia Chiu Stone and Barron Stone


Day 1: 

The whole point of OOP is to create re-usable objects but also objects that can be slightly modified later to serve similar but slightly variable purposes. This is why and more importantly when it is better than procedural programming like in C or what I always thought of as spaghetti code.

Attributes tell us more about each object. Some attributes might be fixed but others might vary over the object's lifetime.

One object can contain other objects. (eg: nodes in LL and Trees).

Behaviors also tell us what an object can and can't do.

Objects = Nouns, Verbs = Functions (?)

Objects are created in/from classes.

Classes can be thought of as a template of what an object can be. But it is not the object itself. We can use a single class to create several objects.

An object is an instance of a class.

Different classes help us create different types of objects.

Classes have:
1) name
2) attributes (aka properties and data)
3) behaviors (what I know as functions or also known as operations or methods)

For a node it would be:

__init__ would have val, left right.

For a LL it would be:

__init__ would have root, tail, mid, total len etc.
pop, push, insert, clear, and delete (at a specific location) would be able to edit these attributes if needed.

Method is a program procedure that returns a value.

Method VS Function:
  Methods and functions are the same except methods are defined as part of a class so they are included in any object in that class. They can also only access data that is known to the object.


Class diagram:

![image_65](https://github.com/user-attachments/assets/0580e4f0-6dd6-4e07-9802-43ee625b4357)


Instances: creating an instance of an object using a class is called instantiation. Calling a method of an instance of an object only affects the attributes of the class.

4 fundamental ideas in OOP:

  1) Abstraction
  2) Polymorphism
  3) Inheritance
  4) Encapsulation

aka A-PIE

1) <ins>Abstraction</ins>: We focus on one specific quality of something vs focusing on a particular example of that kind of object. Hence you know the attributes potentially associated with the object (and hence the class). Abstraction means the idea of a class differs from any particular instance of an object based on said class. Abstraction helps us decide how to create classes. I.E. Abstraction tells us the repeated properties that will be needed to create several instances of an object without having to create several classes for each object when it can just be 1 class.

We only focus on the essential ideas of an object hence answering "What does this class look like at this point for this application?".


2) Encapsulation: containing the attributes and methods (that use and manipulate the attributes of the class) within the class to improve readability and safety. This forces other classes to use methods in the original class of the object to make changes to said object. Helps maintain consistency across several places in code where the object is created for that class, prevents/helps manage edge cases and invalid updates to attributes, etc.

Encapsulation creates a black box that prevents outsiders from knowing how a class works. However, we know its expected behavior so we can test via black box testing.

Encapsulation also helps keep separate clean code and only singular changes are needed (this means you don't have to chase down same section of code written in n places and maybe miss a couple and have it cause issues.
   
3) inhert 



