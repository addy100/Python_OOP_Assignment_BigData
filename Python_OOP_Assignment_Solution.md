## Python OOP Assignment
Q1. What is the purpose of Python's OOP?

Ans1. Object-oriented programming (OOP) in Python is a way of writing code that makes it easier to understand, maintain, and reuse.

OOP does this by grouping related data and functions together into objects. This makes the code more organized and modular, which makes it easier to understand and maintain. It also makes the code more reusable, because programmers can create new objects that inherit from existing objects.

Q2. Where does an inheritance search look for an attribute?

Ans2. An inheritance search looks for an attribute in the following places:

i)  The instance object itself.

ii) The class that the instance was created from.

iii) All higher superclasses, progressing from left to right (by default).

The search stops at the first place the attribute is found.

Q3. How do you distinguish between a class object and an instance object?

Ans3. a class object is a reference to the class itself, while an instance object is a reference to an object that was created from a class. The type() function, the __class__ attribute, and the isinstance() function can all be used to distinguish between class objects and instance objects.

Q4. What makes the first argument in a class’s method function special?

Q5. What is the purpose of the init method?

Ans5. The init method is the constructor for a class. It is called when an instance of the class is created. The init method is used to initialize the attributes of the instance.

Q6. What is the process for creating a class instance?

Ans6. To create a class instance, you use the __init__() method. The __init__() method takes in the arguments that you want to pass to the instance and initializes the attributes of the instance.

Q7. What is the process for creating a class?

Ans7. To create a class, you use the class keyword. The class keyword takes in the name of the class and the body of the class. The body of the class can contain methods, attributes, and other class definitions.


Q8. How would you define the superclasses of a class?

Ans8. The superclasses of a class are the classes that the class inherits from. The superclasses of a class are defined in the __bases__ attribute of the class.

Q9. What is the relationship between classes and modules?

Ans9. Classes and modules are both ways of organizing code in Python. Classes are used to create objects, while modules are used to organize code that is not related to objects. Classes are defined in modules, but they can also be imported from other modules. 

Q10. How do you make instances and classes?

Ans10. Instances of a class are created using the __init__() method. The __init__() method takes in the arguments that you want to pass to the instance and initializes the attributes of the instance.

Classes are created using the class keyword. The class keyword takes in the name of the class and the body of the class. The body of the class can contain methods, attributes, and other class definitions.

Q11. Where and how should be class attributes created?

Ans11. Class attributes are created in the body of the class. They can be accessed using the __class__ attribute of an instance.

Q12. Where and how are instance attributes created?

Ans12. Instance attributes are created in the __init__() method of the class. They can be accessed using the __self__ attribute of an instance.

Q13. What does the term "self" in a Python class mean?

Ans13. 
Q14. How does a Python class handle operator overloading?

Q15. When do you consider allowing operator overloading of your classes?

Q16. What is the most popular form of operator overloading?

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

Q18. Describe three applications for exception processing.

Q19. What happens if you don't do something extra to treat an exception?

Q20. What are your options for recovering from an exception in your script?

Q21. Describe two methods for triggering exceptions in your script.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists.

Q23. What is the purpose of the try statement?

Q24. What are the two most popular try statement variations?

Q25. What is the purpose of the raise statement?

Q26. What does the assert statement do, and what other statement is it like?

Q27. What is the purpose of the with/as argument, and what other statement is it like?

Q28. What are *args, **kwargs?

Q29. How can I pass optional or keyword parameters from one function to another?

Q30. What are Lambda Functions?

Q31. Explain Inheritance in Python with an example?

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Q34.Explain the use of the 'nonlocal' keyword in Python.

Q35. What is the global keyword?
