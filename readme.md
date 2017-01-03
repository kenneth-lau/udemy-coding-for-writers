# Notes from the "Coding for Writers 1: Basic Programming" course on Udemy
For more information on this course, see [Coding for Writers 1: Basic Programming](https://www.udemy.com/coding-for-writers-1-basic-programming)

## Final project: Therapist Bot
- [Carl the Therapist Bot](https://kenneth-lau.github.io/udemy-coding-for-writers/)
- [Documentation for "Carl the Therapist Bot"](exercise17-therapist-bot-doc.md)

## Exercises
- Exercise 2: [Strings](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise2-strings.html)
- Exercise 3: [JavaScript](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise3-html-javascript.html)
- Exercise 4: [Documenting constants](/exercise4-constants.md)
- Exercise 5: [Operators](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise5-operators.html)
- Exercise 6: [Functions](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise6-functions.html)
- Exercise 7: [Function documentation](/exercise7-function-doc.md)
- Exercise 8: [Conditionals](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise8-conditionals.html)
- Exercise 9: [Comments](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise9-comments.html)
- Exercise 10: [Loops](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise10-loops.html)
- Exercise 11: [Function documentation 2](exercise11-function-doc.md)
- Exercise 12: [Collections](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise12-collections.html)
- Exercise 13: [Documenting enumerations](exercise13-enumerations-doc.md)
- Exercise 14: [Libraries](https://kenneth-lau.github.io/udemy-coding-for-writers/exercise14-libraries.html)


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
    * syntax
    ```
    if (expression) {
        ...
    }
    ```
    * example
    ```
    if (temperature > 100) {
    display.innerHTML = "Warning! Too hot!";
    }
    ```
  * else
    * example
    ```
    if (temperature > 100) {
        display.innerHTML = "Warning! Too hot!";
    } else {
        display.innerHTML = "Temperature fine";
    }
    ```
  * Else if
    * example
    ```
    if (temperature > 100) {
        display.innerHTML = "Warning! Too hot!";
    } else if (temperature < 0) {
        display.innerHTML = "Warning! Too cold!";
    } else {
        display.innerHTML = "Temperature fine";
    }
    ```
  * nested ifs
    * example
    ```
    if (fluid == "water") {
      if (temperature > 100) {
        display.innerHTML = "Warning! Too hot!";
      } else {
        display.innerHTML = "Water is fine";
      }
    }
    ```
  * switch
    * shortcut for a series of if/else if statements
    * example
    ```
    switch(expression) {
        case value1:
            code block
            break;
        case value2:
            code block
            break;
        default:
            default code block
    }
    ```

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
  * syntax
  ```
    while (condition) {
      code block to be executed
  }
  ```
  * example
  ```
  var person= "child";
  while (person != "grandparent") {
      if (person == "child" {
          person = "parent";
      } else if (person == "parent")
          person = "grandparent";
      }
      ...   
  }
  ```
* for loop 
  * repeats a block of code while a variable changes
  * example of meaning "for every box, add a label"
  * convention to use variables "i, j, k"
  * syntax
  ```
  for (i = 0; i < totalNumber; i++) {
  ```
  * example:
  ```
  var numberString = "";
  var i;
  for (i = 0; i < 4; i++) {
    numberString += i + " ";
  }
  ```
* Loops are used a lot with "containers" of data

## 4.2 Advanced function documentation
* Booleans
  * Parameters
    * Example "Whether to turn off the light"
  * Return value
    * Example: "true if the operation was successful; false if it failed
    * "otherwise, false"
  * If main purpose is to return a Boolean value
    * Example: "Returns whether the database is empty"
* Units
  * very important
  * Examples: 
    * kilobytes, seconds, km, miles, pixels
    * "in seconds"
    * Example: "Time before timeout, in seconds"
* Use of "specified"
  * Example: "Changes the password for the specified user", "Deletes the specified photo"
* Callback
  * when a parameter is a function
  * "Called when..."
* Links and fonts
  * function name should be links
  * can use bold/monospace for functions, constants, etc
  * can use monospace for programming language keywords
  * Example: "Function makes a call to a server. Callback function is called when the server response is received"
  * Use "Called when... "
* "See Also" section
* Sample code
  * illustrates how the function is called
  * should be meaningful

## 4.24 Object oriented programming
* OOP is a way of organizing code
  * groups data and functions together
* Classes
  * data type
  * contains:
    * fields and/or properties (variables)
    * methods (functions)
  * methods and properties are called "members"
  * data type
  * instantiate an "object" of that class type
  * call methods on an object
  * example  
    `var firstName = "Peter";`  
    `firstName.toUpper();`
* Fields
* Properties
  * for getting and setting data
  * In JS, properties are like variables
  * use the period after an object to access a property
  * can use a second period to string together methods and properties 
  * example:
    * Set a property: `textbox.size = 20;`
    * Get a property: `var maxCharacters = textbox.size;`
    * `page.textbox.size`
* Methods
  * functions for classes
  * use period like a property
  * example:
    * `var sentence = "life is bad";`  
    `var newSentence = sentence.replace("bad", "good");`
* Class methods and properties
  * sometimes called "static" method or property
  * put a dot after the class name
  * don't require instantiating an object
  * example: `Math.random();`
* Documenting Classes
  * vast majority of SDK are object oriented
  * Classes
    * one sentence description
    * example: "Represents an employee"
  * Properties
    * document like for constants
  * Methods
    * document like for functions

## 4.25 Programming languages
* Programming languages
  * machine code (assembly language)

## 5.26 Collections
* Arrays
  * a size (how many in the list)
  * an order (which comes first)
  * JS: represented by square brackets, elements separated by commas
  * example
    * numbers: `[5, 2, 60, -7, 1, 6.5, 0]`
    * strings: `var beatles = ["John", "Paul", "George", "Ringo"];`
  * accessing array values
    * index value starts at 0 and goes to array length minus one
    * access value by putting index in square brackets
      * example:   
      ```
      var beatles = ["John", "Paul", "George", "Ringo"];
      alert(beatles[2]);`
      ```
  * looping through arrays
    * example:
    ```
    var beatles = ["John", "Paul", "George", "Ringo"];
    var credits = "";
    for (int i=0; i < beatles.length; i++) {
        credits += beatles[i] + " ";
    }
    ```
  * array methods
    * JS
      * length
      * concat
      * indexOf
      * push
      * reverse
      * sort
* Dictionaries = Objects in JS
  * also called "hashtable"
  * collection of data keys and values
  * called objects in Javascript
    * dictionary keys are object "properties"
    * same name as the instantiation of classes
    * enclosed in curly brackets
    * keys and values are separated by colons
    * pairs separated by commas
    * and data type
      * keys are almost always strings
    * example of an object:  
    `{"red":205, "green":123, "blue":53}`
    * example of declaring an object
    ```
    var employee = {
      name: "Peter Gruenbaum", 
      company: "SDK Bridge, 
      title: "President"};
    ```
    * example of accessing the object element  
    `var title= employee["title"];`
    * if key is a string, you can access it like a property  
    `var title= employee.title;`
    * object values can be mixed data types
    * looping through object properties  
      * example
      ```
      for (var key in employee) {
          if (employee.hasOwnProperty(key)) {
              ...
          }
      }
      ``` 
    * nesting 

## 5.28 Enumerations
* special data type
  * can only have certain values
* use with `EnumName.EnumValue`
* Java enumerations
  * example  
  ```
  enum TrafficLight { RED, YELLOW, GREEN };
  ```
  * example usage  
  ```
  if (currentLigtht == TrafficLight.RED) {
  ```
  * convention of being in all caps
* JavaScript
  * does not have enums
  * can create something similar with a constant object
  * example
  ```
  const TrafficLight = {
    RED: 0,
    YELLOW: 1,
    GREEN: 2
  };
  ```
* enumerations for switch statements
* Documenting an enums
  * name and description of values and (numerical value)
  * example

## 5.30 Libraries
* self-contained set of code that provides certain functionality
* import the library into your code to use
* in JavaScript, called "modules"
* documentation
  * classes, methods, properties, constants, enumerations
  * overview material
* Using a JavaScript module
  * `<script>` tag
    * `type` attribute set to `application/javascript`
    * `src` attribute with the module file name
* Import
  * `import` keyword
  * lets you add a name to all functions and variables in the module (called a "namespace")
* library location
  * usually download the library and have on server
  * sometimes imported from another location on the Web

## 5.32 Automated doc generation
* helps keep doc in sync
* doc text is included as special comments
* JSDoc
  * special comment characters
  * keywords preceded by @
  * types are in curly brackets