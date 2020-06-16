# Introduction to Python

In this I will try to cover basics of python which is required for Data Science.

##  What is Python?
* Python is a very general purpose programming language, which means it has wide variety of applications. 
* It can be used in web development, Mobile Applications, Machine Learning, Data Mining etc.

##  Why Python?
* If you ask any person who knows python all of them will tell that its the easiest language to learn and code.
* You can code in python like writing steps in english or any language.
* Its very to easy to interpret.
* Line of codes require to run a program is less compare to other programming languages. This we can encounter below when we run our 1st program

### 1st Program in Python - [Hello World](https://github.com/Ankit-Khule/Python/blob/master/Hello%20Word.ipynb "Hello World") 
#### Python is **[Case Sensitive](https://github.com/Ankit-Khule/Python/blob/master/Case%20Sensitivity.ipynb "Case Sensitive")** means Print and print have different meaning in python. So If i write Z=1 and z=2 it will not overide the variables but store two different values in each.
![Case Sensitive](https://github.com/Ankit-Khule/Python-for-Data-Science/blob/master/Images/Case%20Sensitive.JPG)

## [Variables](https://github.com/Ankit-Khule/Python/blob/master/Variables.ipynb)
* Variable is used to store values in python.
* Syntax : Variable_name = "Value". **=** is used an assignment operator.
![Variable_name](https://github.com/Ankit-Khule/Python-for-Data-Science/blob/master/Images/Variables%20Part%201.JPG)
* Variable names can consist of any characters or alphabets. They can have alphanumeric or special characters in them.
* Variable names cannot start with number or special characters except the **_** (Underscore).
![Variable_name](https://github.com/Ankit-Khule/Python-for-Data-Science/blob/master/Images/Variables%20Part%202.JPG)
> * Try to keep variables in plain and simple language so its easy to understand what values they represent.
> * Avoid using variables which are similar to the attributes or function in the in-built libraries.

## [Operators](https://github.com/Ankit-Khule/Introduction-to-Python/blob/master/Operators.ipynb)
## Types of Operators in Python

* Arithmetic Operators (For Basic calculation Purpose)
    * '*' --> Multiplication
    * '/'--> Division
    * '+' --> Addition
    * '-'-- > Subtraction
    * '%' --> Modulous

![Arithmetic](https://github.com/Ankit-Khule/Python-for-Data-Science/blob/master/Images/Arithmetic.JPG)
   
    
* Comparison Operator (For Comparing two variables and constants)
    * Less than '<'
	* greater than '>'
	* Equal to '=='
	* Less than or equal to '<='
	* Greater than or equal to '>='
	* Not equal to '!='

![Comparison](https://github.com/Ankit-Khule/Python-for-Data-Science/blob/master/Images/Comparison.JPG)
    
* Logical Operator (Used for Logical conditions)
    * And
    * Or
    * Not
 
![Logical](https://github.com/Ankit-Khule/Python-for-Data-Science/blob/master/Images/Logical.JPG)
  
* Bitwise Operator (Used to compare binary numbers i.e numbers which are represented in 0 and 1)
    * Bitwise And '&' 	- Set each bit to 1 if both bits are 1 eg: 1001 **&** 1010 will give --> 1000
    * Bitwise OR '|' 	- Set each bit to 1 if one of the bits is 1 eg: 1001 **|** 1010 will give --> 1011
    * Bitwise XOR '^' 	- Set each bit to 1 if only one of the bits is 1 eg: 1001 **^** 1010 will give --> 0011
    * Left shift '<<'	- shift left by inserting zeroes from left and right most digit is removed eg: 1001 **<<**2 will give --> 0010
    * Right shift '>>'	- shift rigth by inserting zeroes from right and left most digit is removed eg: 1011 **>>**2 will give --> 1100

![bitwise](https://github.com/Ankit-Khule/Introduction-to-Python/blob/master/Images/bitwise.JPG)
 
* Identity Operator (For checking the identity of constants and variables)
    * is - returns true if the objects are similar
    * is not - returns true  if the objects are not similar
   
![Identity](https://github.com/Ankit-Khule/Introduction-to-Python/blob/master/Images/Identity.JPG)   

* Membership Operator (For finding relations between two variables)
    * in - Returns true if the value is present in the object
    * not in - Returns true if the value is not present in the object

![Membership](https://github.com/Ankit-Khule/Introduction-to-Python/blob/master/Images/Membership.JPG)    


## [Data Types](https://github.com/Ankit-Khule/Introduction-to-Python/blob/master/Data%20Types.ipynb)

* The most important thing in any code is data types. These are objects used to store some kind of information.
* Each data types can store only certain type of data.
* Basic Types of Data
	* int 	  - This data type is used to store only numerical or Integers and non decimal values
	* Float   - This data type is used to store only Decimal or floating values.
	* Bool 	  - This data type is used to store only Boolean data (true or false)
	* Str 	  - This data type is used to store only Strings which can be alphanumeric and consist of any special characters.
	* complex - Numbers with real and imaginary part such as 3+2j where j is square root of -1

* type("xxx") is used to get the information about type of data for that particular object

![Data Types](https://github.com/Ankit-Khule/Introduction-to-Python/blob/master/Images/Datatype.JPG)


> * This repository covers the basic of pythons now we will level up a little and explore more in depth of python.
> * Below are the list of other respository for learning each concept
> * [Data Structures](https://github.com/Ankit-Khule/Data-Structures-in-Python) 
> * [Conditional Statements](https://github.com/Ankit-Khule/Conditonal-Statements-in-Python)
> * [Functions](https://github.com/Ankit-Khule/Functions) 
> * OOPS
> * Debugging
> * File handling
> * Exception handling
> * Algorithms
