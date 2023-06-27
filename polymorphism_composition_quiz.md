# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Polymorphism is where objects of different classes can be treated the same, as long as they can perform the same methods. 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means that, when we have a function to perform an action, we do not need to specify one class to meet this criteria. We are leaving it open-ended and anything that can perform the task can be used.

3. What can we use to implement polymorphism in Java?

An interface can be used to implement polymorphism. In the below example, we would have an iDrive interface, and any class that could perform the function drive() wouuld be able to be used. 

4. How many 'forms' can an object take when using polymorphism?

Unlimited.

5. Give an example of when you could use polymorphism.

We might have a travel() method which takes a car as an argument. However, this limits the vehicle that can be used to drive. Making the travel() function take in anything that has the function to drive means that you do not have to specify the class that is required. It makes the function more flexible. 


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition allows objects to be composed of other objects.

7. When would you use composition? Provide a simple example in Java.

If you were building a car class, it could be assembled with a variety of sub class objects. EG. An engine, 4 doors, 4 wheels etc. The car would be COMPOSED of these sub classes.

8. Give a difference between composition and aggregation?

Aggregation can be called a "has a" relationship where once class has a reference instance of another class. These can co-exist independently. These instances of the other class can be shared amongst aggregates. 

Composition is where the main class is made up of the sub classes. The sub-classes cannot exist independently of the main. 

9. What is/are the advantage(s) of using composition/aggregation?

Aggregation allows for navigation in two directions - the containing object can access the associated objects, and the associated objects can also access the containing object. It also allows multiple instances of the associated class to be associated with a single instance of the containing class.

Composition is a stronger form of association, indicating that the sub classes are an essential part of the main. 

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed. 

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

They remain. 