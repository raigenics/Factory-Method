# Factory Method Design Pattern
Factory method design pattern is all about creation of object, so it falls under creational design pattern category. This is one of the most commonly used GoF design pattern and quite easy to understand.
GoF defines it as 
“Define an interface for creating an object, but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.”
that simply means that you call a factory with a parameter and an instance of a class is created and given to you. You don’t create the class yourself. The factory takes care of all that internally for you. What is required from your end is that you just need to know what argument to pass for each distinct class you want to create.

So, what problem it tries to solve:

Similar to simple factory –
-	Object creation is scattered and repetitive in various parts of the code
-	Client is coupled to any new type creation in the project

Now looking at the problem statement, the objective of implementing factory method should be
- To make Client unaware of the object instantiation
- Client should access the objects through a common interface.

# For complete explanation visit - https://youtu.be/tdMOdeewTnc
