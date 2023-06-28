# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
The word 'polymorphism' means __Many Forms__. So an object can take on different forms or have multiple types.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
In an OO design, polymorphism refers to the ability of objects of different classes to be treated as objects of a superclass or interface. A simple Java example would be a superclass called "Shape" and subclasses like "Circle" and "Rectangle" that inherit from it. An array of Shape objects can be created and both circles and rectangles can be stored in it.

3. What can we use to implement polymorphism in Java?
We can use inheritance and method overriding.

4. How many 'forms' can an object take when using polymorphism?
An object can take as many forms as there are subclasses or types that it can be treated as within the inheritance hierarchy.

5. Give an example of when you could use polymorphism.
An example of using polymorphism is having different types of animals share common behaviors, such as "speak()" or "eat()", and they are treated the same within the code without having to write separate code for each specific animal type.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
In object-oriented programming, composition refers to a design principle where a class consists of one or more objects of other classes, forming a part-whole relationship.

7. When would you use composition? Provide a simple example in Java.
Composition is used when one class represents a larger entity that is composed of smaller, more specialised parts. For example, a "Car" class may be composed of objects like 'Engine,' 'Wheels,' and 'doors.'

8. Give a difference between composition and aggregation?
The main difference between composition and aggregation lies in the lifecycle and ownership of the associated objects. In composition, the composed objects are owned by the containing object and have a strong relationship, while in aggregation, the associated objects have an independent lifecycle and a weaker relationship.

9. What is/are the advantage(s) of using composition/aggregation?
The advantages of using composition/aggregation include code reuse, modularity, flexibility, and the ability to represent complex relationships between objects.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
When an object composed of other objects is destroyed, the composed objects are also destroyed or deallocated, as they are part of the whole object and have a strong relationship.


11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
When an object is destroyed in aggregation, the objects it is composed of are not automatically destroyed or deallocated, as they have an independent existence and lifecycle. They can be used by other objects or exist separately.