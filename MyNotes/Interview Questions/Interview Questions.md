[[Interview Questions#OOPS|OOPS]]
[[Interview Questions#Basics|Java Basics]]
[[Interview Questions|DS]]
[[Interview Questions#Programming In C|Programming in C]]


# OOPS
- What are the main features of OOPS. Inheritance, Polymorphism, Encapsulation, Data Abstraction with Example
- Polymorphism - Runtime Polymorphism and Compile time polymorphism
- Overloading(Compile Time. like overloading function) vs Overriding(Runtime. overriding function already described in parent class)
- Multiple Inheritance vs Multi Level Inheritance
- Problems of Multiple Inhertance ( Hybrid Inheritance )
- What is a constructor
- What is a interface? What are abstract classes? Difference between both.
- What are access specifiers?
- Static
- What is an exception? What is an Error?
- What is Cohesion and Coupling? Which scenario is better?


# Basics
- JVM is platform independent
- Javac compiler the source file into byte code and then .class file is generated which is then executed in JVM.
- JDK ( JRE + Other Development Tools  ( JVM + Class and Libraries ) )
- Is Java completely object oriented?
- What are wrapper classes? What are Autoboxing and Unboxing?
- What are marker interfaces?
- Call by Value and Call by Reference
- What is constructor chaining?
- **Constant string pool**
- Why there is not concept of pointers in Java?
- Final, Finally and Finalize
- Throw Throws


# Data Structure
- Worst Case of Quick Sort
The worst case occurs when the picked pivot is always an extreme (smallest or largest) element. This happens when input array is sorted or reverse sorted and either first or last element is picked as pivot.

# Programming In C
- Malloc and Calloc
- What is a Pointer?
- What is a dangling pointer?
```c
#include <stdio.h>

int main() {
    int a[5][5];
    a[0][0] = 9;
    a[0][1] = 3;
    int i = 0;
    printf("%d\n", *(a[0] + 1));
    return 0;
}
```