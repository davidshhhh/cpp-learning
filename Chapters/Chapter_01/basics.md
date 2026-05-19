# Just getting Used to the basics

## What is c++ 

C++ is a programming language. A standardized, general-purpose, object-oriented, compiled language. C++ is accompanied by a set of functions and containers called the **C++ Standard-Library**. Bjarne Stroustrup created C++ as an extension to a C programming language. Still, C++ evolved to be a completely different programming language.

> **Let us emphasize this:** C and C++ are two different languages. C++ started as "C with classes," but it is now a completely different language. So, C++ is not C; C++ is not C with classes; it is just C++. And there is no such thing as a C/C++ programming language.

C++ is widely used for the so-called *systems programming* as well as application programming. C++ is a language that allows us to *get down to the metal* where we can perform low-level routines if needed, or soar high with abstraction mechanisms such as templates and classes.

---

## C++ Standards

C++ is governed by the ISO C++ standard. There are multiple ISO C++ standards listed here in chronological order: 
* C++03
* C++11
* C++14
* C++17
* C++20

Every C++ standard starting with the C++11 onwards is referred to as **"Modern C++."** 


--- 

## Comments

single lined comments start with: // 

'''cpp

int main(){

    // this is a comment
}


multi lined comments start and end with: /* */

'''cpp

int main(){

    /* this is a comment
    with multiple lilnes */
}


--- 

## #include <iostream> explenation

the iostream header is part of the standard library. 

## std::cout 

known as the standard output stream. 

## new line 

to output on a new line we need to output a newline charater : \n

## Complining files 

to compile a C++ file.  we use the basic command:

'''bash 
g++ fileName.cpp 

this then gives us ./a.out

to compile for  a C++11 standard, we add the -std=c++11 flag:  g++ -std=c++11 main.cpp

to enable warnings we can add the -Wall flag: -Wall

to get a custom executable name, we add the -o flag folled by the name: -o basics