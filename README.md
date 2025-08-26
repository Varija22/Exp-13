Program 1

Aim:
To demonstrate the concept of constructors in C++, including the default constructor, parameterized constructor, and copy constructor.

Software Used:**
Programiz online C++ compiler and IDE.

Theory:
Constructors are special member functions in C++ used to initialize objects. There are several types of constructors:

* Default Constructor:** Initializes an object with default values.
* Parameterized Constructor:** Initializes an object with user-defined values.
* Copy Constructor:** Creates a new object as a copy of an existing object.

In the given program, these constructors initialize the integer member `num` of the class `fetch` in different ways. The `disp()` method is used to display the value of `num`.

Algorithm:

1. Define a class `fetch` with a private integer variable `num`.
2. Implement three constructors:

   * Default constructor to assign `num` a default value.
   * Parameterized constructor to assign `num` a passed integer value.
   * Copy constructor to initialize a new object by copying `num` from another object.
3. Implement a method `disp()` to display the value of `num`.
4. In the `main()` function:

   * Create an object `f1` using the default constructor.
   * Create an object `f2` using the parameterized constructor with the value 5.
   * Create an object `f3` using the copy constructor to copy `f2`.
5. Call `disp()` for all three objects to display their values.

Conclusion:
The program successfully demonstrates how different constructors work in C++. The default constructor assigns a default value, the parameterized constructor assigns a user-defined value, and the copy constructor creates a new object with the same value as an existing object. This helps in understanding object initialization and copying in C++.

