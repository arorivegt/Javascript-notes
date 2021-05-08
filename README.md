# JavaScript
```javascript
var numer = 9;

//this is a comment
/*these are multiple comment*/
```

### Data Types
- undefined
- null 
- boolean
- string
- symbol
- number
- object


```javascript
//this used throughout your whole program
var myName = "anibal";
myName = 9;

//will only be used within the scope of where i declared that
let ourName = "freeCodeCamp";

//const is variable can't never change it
const pi = 3.14;
```

### Storing values with Assignment Operator

```javascript
var a; //declaring  a variable
var b = 2; //declaring and assignment a variable

a = 7 //assigmet a variable
```
### Initializing Variables / Assignment Operator
```javascript
var a = 9;
var b = 10;
var c = "I am a"

a = a + 1; // 6
b = b + 5; //15
c = c + " String"; //I am a String
```

### Case Sensitivity in Variables
```javascript
var hola; /* <= Different to => */ var HOLA;
```

### Adding, Subtracting, Multiplying, Dividing, Incrementing, Decrementing Numbers
```javascript
var sum = 10 + 10; // 20
var difference = 45 - 5; //40
var product = 2 * 5; //10
var quotient = 66 / 6; //11

var myVar = 87;
//increment
myVar = myVar + 1;
myVar++;
//decrement
myVar = myVar - 1;
myVar--;
```

### Decimal, multiply divided Decimals
```Javascript

//Decimals
var ourDecimal = 5.7;
var myDecimal = 0.009;

var product = 2.0 * 2.5; //5
var quotient = 4.4 / 2.0; //2
```

### Remainder
```Javascript
var remainder;
remainder = 11 % 3 ; //2

//the remainder is used to determine is a number is even or odd
//if you can divide a number by 2 and the remainder is 0 => the number is even

```
### Compound Assignment with Augmented Addition
```Javascript
var a = 3;
var b = 17;
var c = 12;

a = a + 12; /** <===> */ a +=12;
b = 9 + b; /** <===> */ b += 9;
c = c + 7 ; /** <===> */ c += 7;
```

### Compound Assignment with Augmented Subtraction
```Javascript
var a = 11;
var b = 9;
var c = 3;

a = a + 6; /** <===> */ a -=6;
b = b - 15; /** <===> */ b -= 15;
c = c -1 ; /** <===> */ c -= 1;
```

### Compound Assignment with Augmented Multiplication
```Javascript
var a = 5;
var b = 12;
var c = 4.6;

a = a * 5;  /** <===> */ a *=5;
b = 3 * b;  /** <===> */ b *= 3;
c = c * 10; /** <===> */ c *=10;
```

### Compound Assignment with Augmented Division
```Javascript
var a = 48;
var b = 108;
var c = 33;

a = a / 12;  /** <===> */ a /=12;
b = b / 4;   /** <===> */ b /=4;
c = c / 11;  /** <===> */ c /=12;
```
### Declare String Variables
```Javascript
var firstName = "Anibal";
var lastName = "Rodriguez";
```
### Escaping Literal Quotes in Strings
```Javascript
var firstName = "I am a \"Double quoted inside\" \"double guotes\"";
```
### Quoting String with Single Quotes
```Javascript
var firstName = "I am a 'simple quoted inside' 'double guotes' ";
var firstName = 'I am a "double quoted inside" "double guotes" ';
```
### Escape Sequences in Strings
```Javascript
/************
\' single quote
\" double quote
\\ backslash
\n newline
\r carriage return
\t tab
\b backspace
\f form feed
*************/

var myStr = "this is a String \n\t\\Second\bLines"
```

### Concatenating String with Plus Operator
```Javascript
var ourStr = "I come first . " + "I come second.";

var myStr = "This is the start. " + "This is the end.";
```

### Concatenating String with Plus Equals Operator
```Javascript
var ourStr = "I come first . ";
outStr += "I come second.";

var myStr = "This is the first sentence. "
myStr += "This is the second sentence.";
```
### Constructing String with Variables
```Javascript
var outName = "Anibal";
var outStr += "Hello our name is " + ourName + ", how are you?";

var myName = "Beau";
var myStr = "My name is " + myName + " and I am well!";
```

### Appending Variables to String
```Javascript
var anAdjective = "awesome!";
var ourStr = "FreeCodeCamp is ";
ourStr += anAdjective;

var someAdjective = "wortwhile";
var myStr = "Learning to code is ";
myStr += someAdjective;
```
### Find Length of String
```Javascript
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length; // 3
```
### Bracket Notation to Find First Character in String
```Javascript
var firstLetterOfFirstName = 0;
var firstName = "Jose";

firstLetterOfFirstName = firstName[0]; //the result is -> J
firstLetterOfFirstName = firstName[1]; //the result is -> o
firstLetterOfFirstName = firstName[2]; //the result is -> s
firstLetterOfFirstName = firstName[3]; //the result is -> e
firstLetterOfFirstName = firstName[4]; //the result is an error or undefined value, because doesn't exist the position four, the position begin in the position zero.
```
### String Immutability
```Javascript
var myStr = "Jello World";

myStr[0] = "H"; //this is not possible because when i created, the string cannot be changed in any character only a full word, phrases, i need to assignment a new string

mstry = "Hello World"; //This is the way to change the original String
```

### Bracket Notation to Find Nth Character in String
```Javascript
var fisrtName = "Ada";
var secondLetterOfLastName = fisrtName[1]; //A
var thirdLetterOfLastName = fisrtName[3]; //a
```
### Bracket Notation to Find Last Character in String
```Javascript
var fisrtName = "Jello World";
var lastLetterOfFirstName = fisrtName[fisrtName.length -1]; //the result is d, because firstName.length = 11 then 11 - 1 is equal 10, the position of the last character, because we remember the position began in 0.
```

### Bracket Notation to Find Nth-to-Last Character in String
```Javascript
var fisrtName = "Jello World";
var thirdToLastLetterOfFirstName = fisrtName[fisrtName.length - 3]; // 11 - 3 = 8 and the result is o
```

### Word Blanks
```Javascript

//This is a function, later we will describe more about functions
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb){
    var result = "";
    result += "The " + myAdjective + " "  + myNoun + " "  + myVerb + " to the store " + myAdverb;
    return result;
}

console.log(wordBlanks("dog","big", "ran", "quickly"));
```
### Store mutiple Values with Arrays
```Javascript
var ourArray = ["John" , 23]; 

var myArray = ["Quincy", 1];
```
### Nested Arrays
```javascript
//Array with other array as value or many arrays as values
var ourArray = [ ["John" , 23], ["Quincy", 1] ]; 
```
### Acces Array Data with Indexes
```javascript
var ourArray = [50, 60 , 70]; 
var ourData = ourArray[0]; // ourData is igual to 50
```
### Modify Array Data with Indexes
```javascript
var ourArray = [50, 60 , 70]; 
ourArray[1] = 45; // ourArray is igual to  [50, 45 , 70]; 
```
### Access Multi-Dimensional Array with Indexes
```javascript
var myArray = [ [1,2,3], [4,5,6], [7,8,9], [10,11,12], 13, 14];
var myData = myArray[0][0]; //myData is igual to 1
myData = myArray[2][1]; //myData is igual to 8
myData = myArray[4]; //myData is igual to 13
```
### Manipulate Arrays with push()
```javascript
var myArray = ["Hola", "como", "estas"];
myArray.push(["what's","happening"]); //now my array is igual to ["Hola", "como", "estas", ["what's","happening"]]
```
### Manipulate Arrays with pop()
```javascript
var myArray = ["Hola", "como", "estas"];
var removeFromMyArray = myArray.pop(); //now myArray is igual to ["Hola","como"]

var ourArray = [ ["John" , 23], ["Quincy", 1] ]; 
var removeFromMyArray = ourArray.pop(); //now ourArray is igual to  ["John" , 23]
```
### Manipulate Arrays with unshift()
```javascript
var myArray = ["Hola", "como", "estas"];
var removeFromMyArray = myArray.unshift(); //now myArray is igual to ["como","estas"]

var ourArray = [ ["John" , 23], ["Quincy", 1] ]; 
var removeFromMyArray = ourArray.unshift(); //now ourArray is igual to  ["Quincy", 1]
```
