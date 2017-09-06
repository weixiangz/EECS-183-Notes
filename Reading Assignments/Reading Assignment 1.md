# Suggested Reading Assignment Day 1

##Check List: 

- []Zyantic Reading

- [ ]cplusplus.com reading
- [x]What are compilers
- [x]Structure of a program
- []variable and constant
- []Operators
- []Basic Input and Output


##Zybooks Reading Note, To review later. 
* Errors: If a compiler says that an error exists on line 90, the actual error may be on line 91, 92, etc.
	* Is this statement true of false? 
		* [Answer](https://learn.zybooks.com/zybook/UMICHEECS183Fall2017/chapter/1/section/6?content_resource_id=7357093)
* What if a compiler generates a specific message like "missing semicolon", then a semicolon must be missing somewhere, though maybe from an earlier line?
	* Is this statement true or false? 
		* [Answer](https://learn.zybooks.com/zybook/UMICHEECS183Fall2017/chapter/1/section/6?content_resource_id=7357093)


## Cplusplus reading -- Introduction Section:

### What are compilers
- **Machine Language** is 0 and 1
	- Compilers turn machine language → to high level language 
	- C++ is a type of high level language, since it’s not 0 or 1
	-  **Compilers** *translate* high level language into machine language.
	- C++ → a bunch of 0 and 1
- Console Programs
	- Programs that instructs the operating system to give the user a GUI.

## Basics of C++  
### Structure of a Program 

<!-- lang-cpp -->
	1|	#include<iostream>
	2|	using namespace std; 
	3|	int main ()
	4|	{
	5|	
	6|	cout << "hello world"; 
	7|	return 0; 
	8|	}
	9|	
	
Line 1:

The addition of # means that’s it’s being used as a instruction before hand, allowing the library **“iostream”** to be included
— Official word for #include is **Preprocessor**
— The IOStream part: Header IOStream

Line 3: Declares a function! 

Definition of **function**

	Function: A group of statement which are given a name. 

Everything within *4 and 6* are defined by the brackets, allowing for beginning and end statement 

Why use **namespace** std

	You can either use std::cout every time, 
	or you can just include the standard library. 


### Variable and Types
What is a variable: 
	- Variable: Portion of memory to store a value.
	- Each of the variables requires a name. 

Naming of variables or **identifers**: camelCase dawg, the name of 

- Different data types!
	- **strings**
		- **Char** = Just 1 string
	- Whole Numbers, or **ints.** 
		- Just whole numbers

	- Floating Points
		- **float**: Any number
		- **Double**: Any number, but not as *precise* as **float**
		- Long **double**: Any number, but not as *precise* as **double**


	

### Constants
### Operators
### Basic input/output

