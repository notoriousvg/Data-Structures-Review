# CH 1 : A C++ Primer

"building data structures and algorithms require communication instructions to a computer...\[i\]n this chapter, we present a quick tour of C++ programmming language and its features" (Goodrich, et al). 

## Contents
 **1.1 Basic C++ Programming Elements**
 **1.2 Expressions**
 **1.3 Control Flow**
 **1.4 Functions**
 **1.5 Basic C++ Programming Elements**
 **1.6 C++ program and File ORganization**
 **1.7 Writting a C++ Program**
 **1.1 Exercises**

## Definitions
 **class:** user defined type that encaptulates many important mechanisms such as:<br> -guaranteed initialization<br> -implicit type conversion<br> -control of memory management<br> -operator overloading
 **header files:** used to provide special declarations and definitions of use to the program.
 **Fundamental Types:** <br>
 - **bool**     Boolean value
 - **char**     character       (8 bits)
 - **short**    short integer   (16 bits)
 - **int**      integer         (32 bits)
 - **long**     long integer    (32 bits)
 - **float**    single-precision floating point number
 - **double**   double-precision floating point number

 **Enumerations:** user-defined type that can hold anys et of sicrete values and behave much like integeres. Provide meaningful names to a set of related values.

 ```cpp
 // SUN = 0 .... SAT = 6
 enum Day { SUN, MON, TUE, WED, THU, FRI, SAT };
 enum Mood { HAPPY = 3, SAD = 1, ANXIOUS = 4, SLEEPY = 2};
 Day today = THU;
 Mood myMood = SLEEPY;
```
 **address:** location where a variable in computer's memory is stored.
 **pointer:** a variable tht holds the value of such an address. 
  - **address-of operator:** returns the address g an object in memory
  - **dereferencing:** returns the contents of a fiven address
 **Arrays:** a collection of elements of the same type and T\[N\] is referenced by the indecees 0 to N-1
 A two dimensional array is implimented as an "array of arrays". For example <br>
 ```cpp
 int A[15][30] 
 ```
 declares A to be an array of 30 objects, each of which is an array of 15 integers
 
