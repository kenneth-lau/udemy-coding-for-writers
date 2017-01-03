# Exercise 17: Documentation for "Carl the Thearpist Bot"

## Constants

Name | Description | Type
--- | --- | ---
exclamationResponses | Responses to user inputs ending with an exclamation mark | Array of strings
genericResponses | Generic responses to keep users interested | Array of strings
povSwitches | First person words that are replaced with second person words | Object
questionResponses | Responses when a user asks a question | Array of strings
questionStarts | Question beginnings for sentences that contain a modified first person word | Array of strings

## Functions

### `createQuestion(patientLine)`
Returns a question based on the patient line

#### Parameters
- `patientLine`  
Type: String  
Text user inputs

#### Returns
Type: String
Question based on the user's input

### `lastChar(myString)`
Returns the last character in a string

#### Parameters
- `myString`  
Type: String  
String to return last character for

#### Returns
Type: String  
Last character of the string

### `randomElement(myArray)`
Returns a random element of an array

#### Parameters
- `myArray`  
Type: Array  
Array with one or more elements

#### Returns
Type: Whatever is in the array  
Random element from the array

## Enumeration

Property name | Description | Value
--- | --- | ---
Generic | Generic response to user input | 0
Question | Answer to a question | 1
Exclamation | Answer to user string ending with an exclamation mark | 2
PointOfView | Answer that makes use of the user input by switching first person words to second person words | 3
