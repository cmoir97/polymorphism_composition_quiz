# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

When an object has several types.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

An example of an interface being used would be an interface called IDrive being implemented in several classes i.e. car, motorbike, bus


3. What can we use to implement polymorphism in Java?

Interfaces


4. How many 'forms' can an object take when using polymorphism?

Two

5. Give an example of when you could use polymorphism.

When you have a number of classes that all share similar functions, i.e. a number of different devices could all share a common connect property and be put in an IConnect interface.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

When an object is made up of a number of other objects.


7. When would you use composition? Provide a simple example in Java.

When there are a number of objects that can perform the same purpose or have
the same properties i.e. cars, motorbikes and buses all have engines so they could
all inherit an engine object and its properties.


8. What is/are the advantage(s) of using composition?

You can give the properties of the interface to any object without causing
problems with any existing superclasses.
No need for the object to know about how the behaviour works only the outcome of
it.


9. When an object is destroyed, what happens to all the objects it is composed of?
The objects will still exist.
