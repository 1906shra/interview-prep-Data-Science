
# Benefit of OOPS

- Modularity and Reusability
- Maintainability and Flexibility
- Encapsulation and Data Protection

## Different Parts of OOPS

1. **Class**: A class in object-oriented programming (OOP) is a blueprint or template for creating objects. It defines a set of properties (attributes) and behaviors (methods) that the objects created from the class will have.

   **Key Components of a Class:**
   - **Attributes** (Fields or Properties)
   - **Methods** (Functions or Procedures)
   - **Constructors**: A special method in a class that is automatically called when an object is created. It is used to initialize the object’s attributes.
   - **Access Modifiers**: 
     - **Public**: Can be accessed from any code.
     - **Private**: Can be accessed within the class or subclass.
     - **Protected**: Only within the class.

2. **Object**: An object is a fundamental building block in object-oriented programming (OOP). It is an instance of a class created from a class blueprint.

   **Why Do We Need Objects:**
   - Modeling Real-World Entities
   - Encapsulation of Data and Behavior
   - Reusability and Modularity

3. **Inheritance**: Inheritance is a fundamental concept in object-oriented programming (OOP) that allows one class (known as the child or subclass) to inherit attributes and methods from another class (known as the parent or superclass).

   **Types of Inheritance (in C++):**
   - **Single Inheritance**: A derived class inherits from only one base class.
   - **Multiple Inheritance**: A derived class inherits from more than one base class.
   - **Multilevel Inheritance**: A class is derived from another class, which is also derived from another class, creating a chain of inheritance.
   - **Hierarchical Inheritance**: Multiple derived classes inherit from a single base class.
   - **Hybrid Inheritance**: A combination of two or more types of inheritance. It is a mix of multiple and multilevel inheritance or other combinations.
   - **Virtual Inheritance**: Used to solve the diamond problem in hybrid inheritance, where a derived class inherits from two classes that share a common base class.

   **Note**: Virtual inheritance ensures that only one instance of the base class (A in this case) is shared among all derived classes that inherit virtually from it. This is achieved by using the `virtual` keyword in the inheritance declaration.
