# Udemy: Coding for writers

## 1.1 Intro
* Scripting languages
  * Programming languages
  * Scripting languages (JavaScript)
* API
* SDK
  * API + docs + tools
* Web APIs
* Platform APIs
  * someties called SDKs
* SDK
  * a collection of code
  * makes it easy to perform some functionality
  * usually one language and one platform (Android, iOS)
  * not obvious how to use
* JavaScript
  * scripting language
  * don't need special software

## 1.2 What is programming?
* Organized into functions
  * functions can call other functions
  * functions can have data passed in and out
  * each function has a series of steps
* Most languages are case sensitve
* In C-style languages, the end of an instruction is marked with a semicolon
* Whitespace
  * means spaces, tabs, new lines
* SDKs
  * libraries, docs, tools
* Developer audience
  * do not read documentation from start to finish
  * scan for info that they need

## 2.4 Data types
* string
  * text - "hello"
  * double or single quotation marks
  * string concatenation 
    * use + to join two strings
  * special characters
    * \n for new line
    * \t for tab
    * \ to escape characters
      * \" - escaping quotation marks
      * \\ - escaping backslash 
* numbers
  * integers - whole numbers
  * decimal - not necessarily whole numbers
  * in JS - the data type is called number
  * some integers are written in hexadecimal
    * base 16
  * very large or small numbers use exponent format
* boolean
  * true
  * false
* objects
  * contain other data
  * complex data types
  * UI elements: e.g. buttons, sliders
  * structured data
* null
  * most languages - complex objects can be set to null, simple objects (e.g., numbers, Booleans) cannot
  * JS - anything can be set to null

## 2.6 HTML and JavaScript
* HTML
  * Tags
  * Attributes
    * attr="value"
* JavaScript
  * contains the action to take
  * put code in a \<script> tag
  * or in a separate file
  * HTML can reference functions through attributes
  * JS can reference HTML elements through their id attribute
  * functions
    * has parentheses after it
  * object oriented programming
    * periods used to indicate something belongs to something else
    * what comes after the period (after a function) is a *property*
  * JavaScript console
    * in the browser

## 2.8 Variables
* Variables
  * store information
  * name
    * numbers, letters, and underscores
    * no punctuation or spaces
    * case sensitive
    * should be meaningful
    * use camel case for multiple words
    * some people use underscores
  * data type
    * Boolean
    * statically typed
      * C, C++, Java, C#
      * can only have one type 
      * more work to program, but catches more mistakes
    * dynamically typed
      * JavaScript, Perl, Python, Objective-C, Ruby
      * can be any type
      * easier to program
  * declaring variables
    * JS
      * use `var`
        * var age;
  * value
    * assignment
      * assign with equals sign
      * username = "Peter";
      * can declare and give initial value in one line
        * var username = "Peter";
     
  * constants
    * special type of variable that your program never changes
    * use `const` instead of `var`
    * const companyName = "SDK Bridge";
    * often all uppercase
    * common constants
      * codes, error messages, display information
    * document with table: name, description, type, value
    * document with code

## 2.10 Operators
  * Operators
    * Binary
    * Unary
      * \- (multiplies value by -1)
    * Number operators
      * \+ (add)
      * \- (subtract)
      * \* (multiply)
      * / (divide)
      * % (mod)
        * divides 2 numbers and takes the remainder
    * Comparative operators
      * == (equal to)
      * != (not equal to)
      * \> (greater than)
      * < (less than)
      * \>= (greater than or equal to)
      * <= (less than or equal to)
    * Operation order
      1. Parentheses first
      2. Unary minus sign: -
      3. Multiplication, division, and mod: * / %
      4. Addition and subtraction: + -
      5. Comparisons: < <= > >= == !=
    * Assignment operator
      * equal sign used for assignment of variable
    * Assignment shortcuts
      Shortcut | Description | Example | Meaning
      --- | --- | --- | ---
      ++ | Add one | x++ |	x = x + 1
      -- | Subtract one | x-- |		x = x – 1
      += | Add something |	x += 3	|	x = x + 3
      -= | Subtract something |	x -= 3	|	x = x - 3
      *= | Multiply something |	x *= 3	|	x = x * 3
      /= | Divide something |	x /= 3	|	x = x / 3
      %= | Mod something |	x %= 3	|	x = x % 3
    * String operators
      * binary string operators
        * \+ (concatenates two strings)
      * comparison string operators
        * case sensitive
        * == (equal to)
        * != (not equal to)
    * Boolean operators
      * binary Boolean operators
        * && (and)
        * || (or)
      * unary Boolean operators
        * ! (not)
          * !true == false
          * !false == true

## 3.12 Functions
* Functions are groups of code
  * react to events
  * make code easier to understand
  * reuse code 
* Data in and out
  * can pass data into functions
    * any number of values, separated by commas
    * go into the parentheses
    * called *parameters*
  * functions can optionally return one value
    * any type
    * called the *return value*
* Creating a function
  * first line declares function name, parameters and (sometimes) what is returned
  * code is in curly brackets {}
  * use **return** keyword to return data
* Using a function
  * call the function and put the data to be passed inside the parentheses
* Parameters
  * act like local variables
* Dynamically typed vs statically typed
  * need to say type for statically typed languages
* Function names
  * same rules as variable names
  * should use camel case
  * can't start with a number
  * typically a verb
* Return
  * you can have more than one return line in a function
* Local and global variables
  * Local
    * declared in a function
    * only exists in that function
  * Global
    * declared outside the function (usually at the top)

## 3.15 Documenting functions
* Big part of SDK documentation
* OOP - usually called *methods*
* Summary
  * one-sentence description
  * If returns a value e.g. returns...
* Remarks
  * extra information
    * when you use the function
    * errors or problems that might occur
    * other related functions
* Paramters
  * name
  * data type
  * description
* Return value
  * data type
  * description

## 3.16 Conditionals
* If-then statements
  * If 
  * else
  * Else if
  * nested ifs
  * switch
    * shortcut for a series of if/else if statements

## 3.18 Making your code readable
* Comments
  * C-style languages use /* ... */
  * More common is: //
  * Non C-style use #
  * complete sentences
  * beginning of each file
  * beginning of each function
  * inside a function, before any section with complexity
  * occasionally at the end of a line
  * comments above functions should be similar to the summary line of their documentation
* Names
  * use clear English
  * camel case for multiple words
  * don't use
    * meaningless names (e.g., foo)
    * one letter variable names
    * obscure abbreviations
* Formatting
  * curly braces
  * indenting of code inside curly braces
  * spacing around operators and commas
* indenting
  * C-style
    * open curly brace at the end of the line
    * indent in (4 spaces)
    * closing curly brace matches indentation of line with open curly brace
* spacing
  * space on either side of binary operators
    * but only to the left of unary operators
  * no space before a comma, but one space after

## 3.20 Loops
* while loop 
* for loop 