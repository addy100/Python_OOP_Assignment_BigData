## Python OOP Assignment
<h4> Q1. What is the purpose of Python's OOP? </h4>

Ans1. Object-oriented programming (OOP) in Python is a way of writing code that makes it easier to understand, maintain, and reuse.

OOP does this by grouping related data and functions together into objects. This makes the code more organized and modular, which makes it easier to understand and maintain. It also makes the code more reusable, because programmers can create new objects that inherit from existing objects.

<h4> Q2. Where does an inheritance search look for an attribute? </h4>

Ans2. An inheritance search looks for an attribute in the following places:

i)  The instance object itself.

ii) The class that the instance was created from.

iii) All higher superclasses, progressing from left to right (by default).

The search stops at the first place the attribute is found.

<h4> Q3. How do you distinguish between a class object and an instance object? </h4>

Ans3. a class object is a reference to the class itself, while an instance object is a reference to an object that was created from a class. The type() function, the ``__class__`` attribute, and the `isinstance()` function can all be used to distinguish between class objects and instance objects.

<h4> Q4. What makes the first argument in a class’s method function special? </h4>

Ans4. The first argument in a class's method function is special because it refers to the instance of the class that the method is being called on. This argument is typically named `self`.

<h4> Q5. What is the purpose of the init method? </h4>

Ans5. The `init` method is the constructor for a class. It is called when an instance of the class is created. The `init` method is used to initialize the attributes of the instance.

<h4> Q6. What is the process for creating a class instance? </h4>

Ans6. To create a class instance, you use the `__init__()` method. The `__init__()`method takes in the arguments that you want to pass to the instance and initializes the attributes of the instance.

<h4> Q7. What is the process for creating a class? </h4>

Ans7. To create a class, you use the class keyword. The class keyword takes in the name of the class and the body of the class. The body of the class can contain methods, attributes, and other class definitions.

<h4> Q8. How would you define the superclasses of a class? </h4>

Ans8. The superclasses of a class are the classes that the class inherits from. The superclasses of a class are defined in the `__bases__` attribute of the class.

<h4> Q9. What is the relationship between classes and modules? </h4>

Ans9. Classes and modules are both ways of organizing code in Python. Classes are used to create objects, while modules are used to organize code that is not related to objects. Classes are defined in modules, but they can also be imported from other modules. 

<h4> Q10. How do you make instances and classes? </h4>

Ans10. Instances of a class are created using the `__init__()` method. The `__init__()` method takes in the arguments that you want to pass to the instance and initializes the attributes of the instance.

Classes are created using the class keyword. The class keyword takes in the name of the class and the body of the class. The body of the class can contain methods, attributes, and other class definitions.

<h4> Q11. Where and how should be class attributes created? </h4>

Ans11. Class attributes are created in the body of the class. They can be accessed using the `__class__` attribute of an instance.

<h4> Q12. Where and how are instance attributes created? </h4>

Ans12. Instance attributes are created in the `__init__()` method of the class. They can be accessed using the `__self__` attribute of an instance.

<h4> Q13. What does the term "self" in a Python class mean? </h4>

Ans13. The term `self` in a Python class refers to the instance of the class that the method is being called on.

<h4> Q14. How does a Python class handle operator overloading? </h4>

Ans14. Operator overloading in Python allows you to define how operators work with your own classes. For example, you could define how the `+` operator works with your own class to add two instances of the class together.

<h4> Q15. When do you consider allowing operator overloading of your classes? </h4>

Ans15. if you have a class that represents numbers, it might make sense to allow operator overloading of the `+` operator so that you can add two instances of the class together.

i) When you want to create a class that represents a mathematical object, such as a vector or a matrix.

ii)When you want to create a class that represents a data structure, such as a list or a dictionary.

iii) When you want to create a class that represents a user interface element, such as a button or a checkbox.

<h4> Q16. What is the most popular form of operator overloading? </h4>

Ans16. The most popular form of operator overloading in Python is the `__add__()` method. The `__add__()` method is called when the `+` operator is used with two instances of the class.

<h4> Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code? </h4>

Ans17. The two most important concepts to grasp in order to comprehend Python OOP code are classes and objects. Classes are the blueprints for objects, and objects are the instances of classes.

<h4> Q18. Describe three applications for exception processing. </h4>

Ans18. Three applications for exception processing are:
<ul>
<li> To handle errors that occur during program execution.
<li> To provide a way to gracefully exit a program.
<li> To provide a way to log errors for debugging
</ul>

<h4> Q19. What happens if you don't do something extra to treat an exception? </h4>

Ans19. If you don't do something extra to treat an exception, your program will crash. This means that the program will stop executing and you will not be able to get any further output.

<h4> Q20. What are your options for recovering from an exception in your script? </h4>

<h4> Q21. Describe two methods for triggering exceptions in your script. </h4>

<h4> Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists. </h4>

<h4> Q23. What is the purpose of the try statement? </h4>

<h4> Q24. What are the two most popular try statement variations? </h4>

<h4> Q25. What is the purpose of the raise statement? </h4>

<h4> Q26. What does the assert statement do, and what other statement is it like? </h4>

<h4> Q27. What is the purpose of the with/as argument, and what other statement is it like? </h4>

<h4> Q28. What are *args, **kwargs? </h4>

<h4> Q29. How can I pass optional or keyword parameters from one function to another? </h4>

<h4> Q30. What are Lambda Functions? </h4>

<h4> Q31. Explain Inheritance in Python with an example? </h4>

<h4> Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked? </h4>

<h4> Q33. Which methods/functions do we use to determine the type of instance and inheritance? </h4>

<h4> Q34.Explain the use of the 'nonlocal' keyword in Python. </h4>

<h4> Q35. What is the global keyword? </h4>
