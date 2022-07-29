# Oops_Interview_Questions
Basic Oops interview questions

1. What is meant by the term OOPs?

OOPs refers to Object-Oriented Programming. It is the programming paradigm that is defined using objects. Objects can be considered as real-world instances of entities like class, that have some characteristics and behaviors.

2. What is the need for OOPs?

There are many reasons why OOPs is mostly preferred, but the most important among them are: 

OOPs helps users to understand the software easily, although they don’t know the actual implementation.
With OOPs, the readability, understandability, and maintainability of the code increase multifold.
Even very big software can be easily written and managed easily using OOPs.

3. What are some major Object Oriented Programming languages?

The programming languages that use and follow the Object-Oriented Programming paradigm or OOPs, are known as Object-Oriented Programming languages. Some of the major Object-Oriented Programming languages include:

Java
C++
Javascript
Python
PHP
And many more.

4. What are some other programming paradigms other than OOPs?

Programming paradigms refers to the method of classification of programming languages based on their features. There are mainly two types of Programming Paradigms:

Imperative Programming Paradigm
Declarative Programming Paradigm
Now, these paradigms can be further classified based:

1. Imperative Programming Paradigm: Imperative programming focuses on HOW to execute program logic and defines control flow as statements that change a program state. This can be further classified as:
a) Procedural Programming Paradigm: Procedural programming specifies the steps a program must take to reach the desired state, usually read in order from top to bottom.
b) Object-Oriented Programming or OOP: Object-oriented programming (OOP) organizes programs as objects, that contain some data and have some behavior.
c) Parallel Programming: Parallel programming paradigm breaks a task into subtasks and focuses on executing them simultaneously at the same time.

2. Declarative Programming Paradigm: Declarative programming focuses on WHAT to execute and defines program logic, but not a detailed control flow. Declarative paradigm can be further classified into:
a) Logical Programming Paradigm: Logical programming paradigm is based on formal logic, which refers to a set of sentences expressing facts and rules about how to solve a problem
b) Functional Programming Paradigm: Functional programming is a programming paradigm where programs are constructed by applying and composing functions.
c) Database Programming Paradigm: Database programming model is used to manage data and information structured as fields, records, and files.

![image](https://user-images.githubusercontent.com/81725794/181589877-0274fd0b-d286-45e3-b31b-e4effbe23067.png)

5. What is meant by Structured Programming?

Structured Programming refers to the method of programming which consists of a completely structured control flow. Here structure refers to a block, which contains a set of rules, and has a definitive control flow, such as (if/then/else), (while and for), block structures, and subroutines.

Nearly all programming paradigms include Structured programming, including the OOPs model.

6. What are the main features of OOPs?

OOPs or Object Oriented Programming mainly comprises of the below four features, and make sure you don't miss any of these:

Inheritance
Encapsulation
Polymorphism
Data Abstraction

![image](https://user-images.githubusercontent.com/81725794/181589989-3d7140aa-572f-4361-9458-9ec1f033e6f0.png)


7. What are some advantages of using OOPs?

OOPs is very helpful in solving very complex level of problems.
Highly complex programs can be created, handled, and maintained easily using object-oriented programming.
OOPs, promote code reuse, thereby reducing redundancy.
OOPs also helps to hide the unnecessary details with the help of Data Abstraction.
OOPs, are based on a bottom-up approach, unlike the Structural programming paradigm, which uses a top-down approach.
Polymorphism offers a lot of flexibility in OOPs.

8. Why is OOPs so popular?

OOPs programming paradigm is considered as a better style of programming. Not only it helps in writing a complex piece of code easily, but it also allows users to handle and maintain them easily as well. Not only that, the main pillar of OOPs - Data Abstraction, Encapsulation, Inheritance, and Polymorphism, makes it easy for programmers to solve complex scenarios. As a result of these, OOPs is so popular.

Advanced OOPs Interview Questions

9. What is a class?

A class can be understood as a template or a blueprint, which contains some values, known as member data or member, and some set of rules, known as behaviors or functions. So when an object is created, it automatically takes the data and functions that are defined in the class.
Therefore the class is basically a template or blueprint for objects. Also one can create as many objects as they want based on a class.

For example, first, a car’s template is created. Then multiple units of car are created based on that template.

10. What is an object?

An object refers to the instance of the class, which contains the instance of the members and behaviors defined in the class template. In the real world, an object is an actual entity to which a user interacts, whereas class is just the blueprint for that object. So the objects consume space and have some characteristic behavior.
For example, a specific car.

11. What is encapsulation?

![image](https://user-images.githubusercontent.com/81725794/181692037-7a24f077-2ae4-4bf9-a052-9b51973c53d8.png)

One can visualize Encapsulation as the method of putting everything that is required to do the job, inside a capsule and presenting that capsule to the user. What it means is that by Encapsulation, all the necessary data and methods are bind together and all the unnecessary details are hidden to the normal user. So Encapsulation is the process of binding data members and methods of a program together to do a specific job, without revealing unnecessary details.

Encapsulation can also be defined in two different ways:

1) Data hiding: Encapsulation is the process of hiding unwanted information, such as restricting access to any member of an object.

2) Data binding: Encapsulation is the process of binding the data members and the methods together as a whole, as a class.

12. What is Polymorphism?

Polymorphism is composed of two words - “poly” which means “many”, and “morph” which means “shapes”. Therefore Polymorphism refers to something that has many shapes.

![image](https://user-images.githubusercontent.com/81725794/181692087-5fda9f82-7b31-41ea-9f0b-464e591d835d.png)

In OOPs, Polymorphism refers to the process by which some code, data, method, or object behaves differently under different circumstances or contexts. Compile-time polymorphism and Run time polymorphism are the two types of polymorphisms in OOPs languages.

13. What is Compile time Polymorphism and how is it different from Runtime Polymorphism?

![image](https://user-images.githubusercontent.com/81725794/181692128-79175fb1-9f00-4064-bad1-93bd4705b0c7.png)

Compile Time Polymorphism: Compile time polymorphism, also known as Static Polymorphism, refers to the type of Polymorphism that happens at compile time. What it means is that the compiler decides what shape or value has to be taken by the entity in the picture.

Example:

// In this program, we will see how multiple functions are created with the same name, 
// but the compiler decides which function to call easily at the compile time itself.
class CompileTimePolymorphism{
   // 1st method with name add
   public int add(int x, int y){ 
   return x+y;
   }
   // 2nd method with name add
   public int add(int x, int y, int z){
   return x+y+z;
   }
   // 3rd method with name add
   public int add(double x, int y){ 
   return (int)x+y;
   }
   // 4th method with name add
   public int add(int x, double y){ 
   return x+(int)y;
   }
}
class Test{
   public static void main(String[] args){
   CompileTimePolymorphism demo=new CompileTimePolymorphism();
   // In the below statement, the Compiler looks at the argument types and decides to call method 1
   System.out.println(demo.add(2,3));
   // Similarly, in the below statement, the compiler calls method 2
   System.out.println(demo.add(2,3,4));
   // Similarly, in the below statement, the compiler calls method 4
   System.out.println(demo.add(2,3.4));
   // Similarly, in the below statement, the compiler calls method 3
   System.out.println(demo.add(2.5,3)); 
   }
}

In the above example, there are four versions of add methods. The first method takes two parameters while the second one takes three. For the third and fourth methods, there is a change of order of parameters. The compiler looks at the method signature and decides which method to invoke for a particular method call at compile time.

Runtime Polymorphism: Runtime polymorphism, also known as Dynamic Polymorphism, refers to the type of Polymorphism that happens at the run time. What it means is it can't be decided by the compiler. Therefore what shape or value has to be taken depends upon the execution. Hence the name Runtime Polymorphism.

Example:

class AnyVehicle{
   public void move(){
   System.out.println(“Any vehicle should move!!”);
   }
}
class Bike extends AnyVehicle{
   public void move(){
   System.out.println(“Bike can move too!!”);
   }
}
class Test{
   public static void main(String[] args){
   AnyVehicle vehicle = new Bike();
   // In the above statement, as you can see, the object vehicle is of type AnyVehicle
   // But the output of the below statement will be “Bike can move too!!”, 
   // because the actual implementation of object ‘vehicle’ is decided during runtime vehicle.move();
   vehicle = new AnyVehicle();
   // Now, the output of the below statement will be “Any vehicle should move!!”, 
   vehicle.move();
   }
}

As the method to call is determined at runtime, as shown in the above code, this is called runtime polymorphism. 

14. How does C++ support Polymorphism?

C++ is an Object-oriented programming language and it supports Polymorphism as well:

Compile Time Polymorphism: C++ supports compile-time polymorphism with the help of features like templates, function overloading, and default arguments.
Runtime Polymorphism: C++ supports Runtime polymorphism with the help of features like virtual functions. Virtual functions take the shape of the functions based on the type of object in reference and are resolved at runtime.

15. What is meant by Inheritance?

The term “inheritance” means “receiving some quality or behavior from a parent to an offspring.” In object-oriented programming, inheritance is the mechanism by which an object or class (referred to as a child) is created using the definition of another object or class (referred to as a parent). Inheritance not only helps to keep the implementation simpler but also helps to facilitate code reuse.

16. What is Abstraction?

If you are a user, and you have a problem statement, you don't want to know how the components of the software work, or how it's made. You only want to know how the software solves your problem. Abstraction is the method of hiding unnecessary details from the necessary ones. It is one of the main features of OOPs. 
For example, consider a car. You only need to know how to run a car, and not how the wires are connected inside it. This is obtained using Abstraction.

17. How much memory does a class occupy?

Classes do not consume any memory. They are just a blueprint based on which objects are created. Now when objects are created, they actually initialize the class members and methods and therefore consume memory.

18. Is it always necessary to create objects from class?

No. An object is necessary to be created if the base class has non-static methods. But if the class has static methods, then objects don’t need to be created. You can call the class method directly in this case, using the class name.

19. What is a constructor?

Constructors are special methods whose name is the same as the class name. The constructors serve the special purpose of initializing the objects.
For example, suppose there is a class with the name “MyClass”, then when you instantiate this class, you pass the syntax:
MyClass myClassObject = new MyClass();

Now here, the method called after “new” keyword - MyClass(), is the constructor of this class. This will help to instantiate the member data and methods and assign them to the object myClassObject.

![image](https://user-images.githubusercontent.com/81725794/181692832-079dabdb-1294-4cf8-831f-cec780ddf30b.png)

20. What are the various types of constructors in C++?

The most common classification of constructors includes:

Default constructor: The default constructor is the constructor which doesn’t take any argument. It has no parameters.

class ABC
{
   int x;
      
   ABC()
   {
       x = 0;
   }
}
Parameterized constructor: The constructors that take some arguments are known as parameterized constructors.

class ABC
{
   int x;
      
   ABC(int y)
   {
       x = y;
   }
}
Copy constructor: A copy constructor is a member function that initializes an object using another object of the same class.

class ABC
{
   int x;
      
   ABC(int y)
   {
       x = y;
   }
   // Copy constructor
   ABC(ABC abc)
   {
       x = abc.x;
   }
}

21. What is a copy constructor?

Copy Constructor is a type of constructor, whose purpose is to copy an object to another. What it means is that a copy constructor will clone an object and its values, into another object, is provided that both the objects are of the same class.

22. What is a destructor?

Contrary to constructors, which initialize objects and specify space for them, Destructors are also special methods. But destructors free up the resources and memory occupied by an object. Destructors are automatically called when an object is being destroyed. 

23. Are class and structure the same? If not, what's the difference between a class and a structure?

No, class and structure are not the same. Though they appear to be similar, they have differences that make them apart. For example, the structure is saved in the stack memory, whereas the class is saved in the heap memory. Also, Data Abstraction cannot be achieved with the help of structure, but with class, Abstraction is majorly used.

24. Explain Inheritance with an example?

Inheritance is one of the major features of object-oriented programming, by which an entity inherits some characteristics and behaviors of some other entity and makes them their own. Inheritance helps to improve and facilitate code reuse.

Let me explain to you with a common example. Let's take three different vehicles - a car, truck, or bus. These three are entirely different from one another with their own specific characteristics and behavior. But. in all three, you will find some common elements, like steering wheel, accelerator, clutch, brakes, etc. Though these elements are used in different vehicles, still they have their own features which are common among all vehicles. This is achieved with inheritance. The car, the truck, and the bus have all inherited the features like steering wheel, accelerator, clutch, brakes, etc, and used them as their own. Due to this, they did not have to create these components from scratch, thereby facilitating code reuse.

![image](https://user-images.githubusercontent.com/81725794/181693258-391909b3-43ae-42a6-93ef-41a6d4a61b9b.png)


25. Are there any limitations of Inheritance?

Yes, with more powers comes more complications. Inheritance is a very powerful feature in OOPs, but it has some limitations too. Inheritance needs more time to process, as it needs to navigate through multiple classes for its implementation. Also, the classes involved in Inheritance - the base class and the child class, are very tightly coupled together. So if one needs to make some changes, they might need to do nested changes in both classes. Inheritance might be complex for implementation, as well. So if not correctly implemented, this might lead to unexpected errors or incorrect outputs.

26. What are the various types of inheritance?

The various types of inheritance include:

Single inheritance
Multiple inheritances
Multi-level inheritance
Hierarchical inheritance
Hybrid inheritance

![image](https://user-images.githubusercontent.com/81725794/181693335-b611da36-4e92-4687-8f5c-7317097ec503.png)

27. What is a subclass?

The subclass is a part of Inheritance. The subclass is an entity, which inherits from another class. It is also known as the child class.

28. Define a superclass?

Superclass is also a part of Inheritance. The superclass is an entity, which allows subclasses or child classes to inherit from itself.

![image](https://user-images.githubusercontent.com/81725794/181693392-d7304c65-1f48-4389-9d76-2167b1dd20a9.png)

29. What is an interface?

An interface refers to a special type of class, which contains methods, but not their definition. Only the declaration of methods is allowed inside an interface. To use an interface, you cannot create objects. Instead, you need to implement that interface and define the methods for their implementation. 

30. What is meant by static polymorphism?

Static Polymorphism is commonly known as the Compile time polymorphism. Static polymorphism is the feature by which an object is linked with the respective function or operator based on the values during the compile time. Static or Compile time Polymorphism can be achieved through Method overloading or operator overloading.

31. What is meant by dynamic polymorphism?

Dynamic Polymorphism or Runtime polymorphism refers to the type of Polymorphism in OOPs, by which the actual implementation of the function is decided during the runtime or execution. The dynamic or runtime polymorphism can be achieved with the help of method overriding.

32. What is the difference between overloading and overriding?
