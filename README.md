# Object-Oriented Programming (OOP) Overview Guide
**Definition/Overview:** Object-Oriented Programming (OOP) languages are contemporary programming languages based around the principle of creating objects as instances of classes. A *class* is similar to a blueprint (or a template) that contains instructions for variables and methods that an *object* will have assigned to it (defining such characteristics as the object's behavior, identity, and state). If you are new one or more of these concepts, they will be discussed later in this guide!
  
#### Table of Contents:
  
1. [OOP Attributes](#oop-attributes)
2. [Special Functions and Methods](#special-functions-and-methods)
3. [Supplemental Resources](#supplemental)
  
<hr />
  
## <a name="oop-attributes">1. OOP Attributes</a>
  
Four object attributes that unite OOP languages (and will be discussed in-depth in this guide) include:  
  
* **Abstraction**
  + This permits objects to have *hidden details*.
    - Classes can be modeled based on immediately necessary/relevant code, with the program's inner workings/complexities remaining hidden.
* **Encapsulation**
  + This permits objects to have *hidden data*.
    - Hidden data can be restricted to a class and its particular methods and variables.
    - Data hiding obscures unneeded information from being revealed/exposed to calling functions. 
* **Inheritance**
  + This is when a class shares behavior and structure that were defined by another class.
    - Inheritance is used for *creating new classes* with these shared characteristics.
      + Thus, inheritance can be thought of as a 'reuse' tool for convenient class creation.
* **Polymorphism**
  + As the name suggests, 'multiple forms' are implied: a subclass's structure and behavior are defined by what was declared in its superclass (or 'main' class).
    - Polymorphism is used to *have objects considered as if they were derived from another, common class*.

<hr />
  
## <a name="special-functions-and-methods">2. Special Functions and Methods</a>
  
**Constructors versus Destructors:** Constructors are methods that initialize object state. They have the same names as the classes they operate for, and do not have return types. Destructors, on the other hand, are methods that are automatically called if an object is to be destroyed (when this will be determined varies by OOP language). Although they also contain their class names, they also have tildes (~) before their names. The OOP language *Java* has a built-in 'garbage collection' functionality that handles this behavior automatically; therefore, destructors are not necessary in that language.
  
**Manipulators:** Some OOP languages (such as C++) include manipulator functions, which are used in tandem with the insertion (<<) and extraction (>>) operators to modify input and output data stream operations. A couple examples include the C++ 'endl' and 'scientific'  manipulators, which insert a newline (and flush the output stream) and format numbers to appear in scientific notation, respectively. 

<hr />
  
## 3. <a name="supplemental">Supplemental Resources</a>
  
* *[Intro to Java Overview Guide](https://github.com/chaseofthejungle/intro-to-java)*
* *[JavaScript Concepts Guide](https://github.com/chaseofthejungle/js-concepts-guide)*
  
<hr />
  
TODO: Add details on overloading, overriding, access modifiers, static versus nonstatic, and try/catch/finally blocks.
