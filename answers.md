1. What does the word 'polymorphism' mean?
The condition of occurring in several different forms.
2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
It gives the ability to process objects differently depending on their data type or class. To put simply it is the ability to redefine methods for derived classes.
For example there may be a vehicle abstract class that is inherited by a car, motorbike and truck.
Although these vehicles are all different and have different properties, they can all be treated as vehicles.
3. What can we use to implement polymorphism in Java?
Multiple subclasses that inherit from the same abstract class, then an ArrayList with the type of
the abstract class. This will allow the array to be populated with instances of all subclasses.
4. How many 'forms' can an object take when using polymorphism?
Two types
  1 Dynamic polymorphism = Having many forms in different classes
  2 Static polymorphism = Having many forms happens in the same class
5. Give an example of when you could use polymorphism.
 When you want to perform a single action in multiple ways
6. What do we mean by 'composition' in reference to object-oriented programming?
 A class that references one or more objects of other classes in instance variables.
7. When would you use composition? Provide a simple example in Java.
when you want to reuse code, composition makes it easier to change code.
For example, creating an instance of a class within another
8. What is/are the advantage(s) of using composition?
Resuing of existing code
Designing clean APIs
Changing the implementation of a class without adapting any external clients
9. When an object is destroyed, what happens to all the objects it is composed of?
They remain intact.
