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
myArray.push(["what's","happening"]); //now my array is igual to ["Hola", "como", "estas", ["what's","happening"]] because push insert a value at the end of the array.
```
### Manipulate Arrays with pop()
```javascript
var myArray = ["Hola", "como", "estas"];
var removeFromMyArray = myArray.pop(); //now myArray is igual to ["Hola","como"], because pop remove the last element of my array.
```
### Manipulate Arrays with shift()
```javascript
var myArray = ["Hola", "como", "estas"];
var removeFromMyArray = myArray.shift(); //now myArray is igual to ["como","estas"], because this function removed the first element of my array and removeFromArray is ["Hola"]
```

### Manipulate Arrays with unshift()
```javascript
var myArray = ["Hola", "como", "estas"];
var removeFromMyArray = myArray.unshift("Anibal"); //now myArray is igual to ["Anibal", "Hola","como", "estas"], because this function insert at the begining of my array
```

### Shopping List
```javascript
var myList = [["Cereal", 3], ["milk", 2], ["bananas", 3], ["juice", 2]];
```

### Write Reusable code with Functions
```javascript
function ourReusableFunction(){
  console.log("Hi, World");
}

ourReusableFunction(); //we'll call the function and then the function will print in the console Hi, World
```
### Passing Values to Function with Arguments
```javascript
function ourFunctionWithArgs(a, b){
  console.log(a - b); 
}

ourFunctionWithArgs(13, 4); // we'll pass two values to the function, and then the function will print in console the result that is inside the function. The result in this case is 13 -4 => 9
```
### Global and Local Scope and Functions
```javascript
//This is a global variable, and we can call it in anywhere of the program
var myGlobal = 10; //=> global scope

function _functionOne(){
  //this variables cannot be use in other function or anywhere of the program. Only in this function
  var oopsGlobal = 5; // => Local Scope
}

function _functionTwo(){
  var output= "";
  if( typeof myGlobal !== "undefined"){
    output += "myGlobal: " + myGlobal;
  }
  if( typeof oopsGlobal !== "undefined"){
    oopsGlobal += "oopsGlobal: " + oopsGlobal;
  }

  console.log(output);
}

// i am going to call my two functions to print the result
_functionOne();
_functionTwo();
```
## Return a Value from a Function with Return
```javascript
function minusSeven(num){
  return num -7; //the name return means that the function will return a value, the operation num - 7
}

console.log(minusSeven(10)); // the function will return the value 7
```
## Understanding undefined value returned from a function
```javascript
var sum = 0;

//in this case, it doesn't return a value, only did a operation or many operations
function addThree(){
  sum = sum + 3;
}

console.log(sum); // the function doesn't return a value, and we will print the value of the variable sum, because sum is a global variable
```
## Assignment with a returned value
```javascript
var changed = 0;

function change(num){
  return (num + 5) / 3;
}

changed = change(10); //we will assignment the value returned

console.log(changed)
```
## Booleans value
```javascript
function booleanValuesFalse(){
  return false;
}
function booleanValuesTrue(){
  return true;
}
```
## Use Conditional Logic with If Statements
```javascript
function ourTrueOrFalse(isItTrue){
  //this is a conditional statement to determinate if the operation is true or false, in this case a it'll be sent a boolean value
  if(isItTrue){ 
    return "yes, it is true";
  }
  return "No, it is false";
}

console.log(ourTrueOrFalse(true)); //it will be printed => yes, it is true
console.log(ourTrueOrFalse(false)); //it will be printed => no, it is no
```
## Comparison with the Equality Operator, Strict Equality Operator, Inequality Operator, Strict Inequality Operator
```javascript
function operatorComparison(values){
  //this is the equality operator (==), to determinate if the value is equal to twelve
  if(value == 12){ 
    return "Equal with ==";
  }
  //this is the Strict Equality Operator (===), the different between the other equal (==) is the following => the equaity operator (==) try to convert both values being compared to a common type, example => 3 == '3' is true with this operator.
  //the strict equality  (===) doesn't try to convert both values, example => 3 === '3', with this operator the result is false, because one of these is a number and the other is a string.
   if(value === 13){ 
    return "Equal with ===";
  }
  //this is the Inequality Operator (!=) what means that the different between of two values.
  if(value != 14){ 
    return "Nothing is equal with !=";
  }
  
  //this is the Inequality Operator (!=) what means that the different between of two values. The different between the Inequality Operator is what the operator (!==) always considers operands of different types to be different
  if(value !== 15){ 
    return "Nothing is equal  with !==";
  }  
  
  return "Nothing";
}

console.log(operatorComparison('12'));//it will be printed => Equal with ==
console.log(operatorComparison(13));//it will be printed => Equal with ===
console.log(operatorComparison(15));//it will be printed => Nothing is equal with !=
console.log(operatorComparison(15));//it will be printed => Nothing is equal with !==
```
 ## Comparison with the Greater Operator
```javascript
function operatorComparison(values){
  if ( values > 0 ){
    return "the values is greater than 0";
  }
}

console.log(operatorComparison(12));//it will be printed => the values is greater than 0
console.log(operatorComparison(0));//it will not be printed because the values is not greater than 0, is igual but not greater than 0
```
 ## Comparison with the Greater than Or Equal to Operator
```javascript
function operatorComparison(values){
  if ( values >= 0 ){
    return "the values is Greater than Or Equal to 0";
  }
}

console.log(operatorComparison(12));//it will be printed => the values is Greater than Or Equal to 0
console.log(operatorComparison(0));//it will be printed => the values is Greater than Or Equal to 0
```
 ## Comparison with the Less than Operator
```javascript
function operatorComparison(values){
  if ( values < 0 ){
    return "the values is Less than 0";
  }
}

console.log(operatorComparison(-12));//it will be printed => the values is Less than 0
console.log(operatorComparison(0));//it will not be printed because the values is not Less than 0, is igual but not Less than 0
```
 ## Comparison with the Less Than Or Equal to Operator
```javascript
function operatorComparison(values){
  if ( values <= 0 ){
    return "the values is Less than Or Equql 0";
  }
}

console.log(operatorComparison(-12));//it will be printed => the values is Less than Or Equql 0
console.log(operatorComparison(0));//it will be printed => the values is Less than Or Equql 0
```
 ## Comparison with the Logical And Operator
```javascript
function operatorComparison(values){
  if ( values >= 0  && values <= 10){
    return "The values is greater  or equal than 10 and is less or equal to 0";
  }
}

console.log(operatorComparison(-12));//it will be printed => The values is greater than 10 and is less or equal to 0
console.log(operatorComparison(0));//it will be printed => The values is greater than 10 and is less or equal to 0
```
 ## Comparison with the Logical Or Operator
```javascript
function operatorComparison(values){
  if ( values <= 0  || values >= 10){
    return "The values is greater than or equal 10 or is less or equal to 0";
  }
}

console.log(operatorComparison(-12));//it will be printed => The values is greater than or equal 10 or is less or equal to 0
console.log(operatorComparison(10));//it will be printed => The values is greater than or equal 10 or is less or equal to 0
console.log(operatorComparison(1));//it will not be printed because the value is not greater than or equal to then and is not less or equal to 0
```
 ## Else Statements
```javascript
function testElse(values){

  if (value > 5 ){
    return "this value is greater than five";
  }else{
    rerurn "this value isn't greater than five";
  }
}

console.log(testElse(10));//it will be printed => this value is greater than five
console.log(testElse(5));//it will be printed => this value isn't greater than five
```
 ## Else If Statements
```javascript
function testElseIf(values){

  if (value > 5 ){
    return "this value is greater than 5";
  }else if(value < 5){
    return "this value is less than 5";
  }else{
    return "this value is equal than 5";
  }
}

console.log(testElseIf(10));//it will be printed => this value is greater than 5
console.log(testElseIf(4));//it will be printed => this value is less than 5
console.log(testElseIf(5));//it will be printed => this value is equal than 5
```
 ## Switch Statements
```javascript
function casInSwitch(values){
  var asnwer = "";
  switch(values){
    case 1: //if the values is equal to 1
      answer = "alpha";
      break; //this mean the end of the case
    case 2:
      answer = "beta";
      break;
    case 3:
      answer = "gama";
    default:// when the values doesn't match with the other case, this statment return a default value
      asnwer = "Stuff";
      break;
  }

  return asnwer;
}

console.log(casInSwitch(1));//it will be printed => alpha
console.log(testElseIf(2));//it will be printed => beta
console.log(testElseIf(3));//it will be printed => "gama"
console.log(testElseIf(4));//it will be printed => "Stuff"
```
 ## Multiple Identical Options in Switch Statements
```javascript
function casInSwitch(values){
  var asnwer = "";
  switch(values){
    //when i will need the same answer with a cases different
    case 1: 
    case 2:
    case 3:
      asnwer = "Low";
      break;
    case 4: 
    case 5:
    case 6:
      asnwer = "Mid";
      break;
    case 7: 
    case 8:
    case 9:
      asnwer = "High";
      break;
    default:
      asnwer = "Stuff";
      break;
  }

  return asnwer;
}

console.log(casInSwitch(2));//it will be printed => Low
console.log(testElseIf(5));//it will be printed => Mid
console.log(testElseIf(9));//it will be printed => "High"
console.log(testElseIf(10));//it will be printed => "Stuff"
```
 ## Return a Boolean value
```javascript
function casInSwitch(values){
  return value > 5;
}


console.log(casInSwitch(10));//it will be printed => true
console.log(testElseIf(5));//it will be printed => false
```
 ## Building JavaScript Objects
```javascript
var ourDog = {
  "name":"Camper",
  "legs":4,
  "tails":1,
  "friends":["Everything!"]
};
```
 ## Accessging Object Properties with Dot Notation, Bracket Notation, Variables
```javascript
var ourDog = {
  "name":"Camper",
  "legs":4,
  "tails":1,
  "friends":["Everything!"]
};

var nameOfMyDog = ourDog.name; //dot notation
var legOfMyDog = ourDog.legs; //dot notation
var tailsOfMyDog = ourDog["tails"]; //bracket notation
//Accesing Object properties with vriables
var name = "name";
var nameOfMyDogWithVariables = ourDog[name];

console.log(nameOfMyDog); //it will be printed => Camper
console.log(legOfMyDog); //it will be printed => 4
console.log(tailsOfMyDog); //it will be printed => 1
console.log(nameOfMyDogWithVariables); //it will be printed => 1
```
 ## Updating Object Properties
```javascript
var ourDog = {
  "name":"Camper",
  "legs":4,
  "tails":1,
  "friends":["Everything!"]
};

ourDog.name = "Koda";

console.log(ourDog.name ); //it will be printed => Koda
```
 ## Add / Delete Properties to an Object
```javascript
var ourDog = {
  "name":"Camper",
  "legs":4,
  "tails":1,
  "friends":["Everything!"]
};

//we can add properties with dot notation or bracket notation to an object
ourDog.bark = "bow-bow";
ourDog['bark'] = "bow-bow";

//delete properties to an object
delete ourDog.bark;
```
 ## Using Objects for Lookups
```javascript
function phoneticLookup(values){
  var result = "";

  var lookup = {
    "alpha":"Adams",
    "bravo":"Boston",
    "charlie":"Chigago",
    "delta":"Denver"
  }
  result = lookup[val];

  return result;
}

console.log(phoneticLookup("alpha")); //it will printed => Adams
```

 ## Accesing Nested Arrays
```javascript

var myObj =  [{
  "alpha":"Adams",
  "bravo":"Boston",
  "charlie":"Chigago",
  "delta":"Denver"
},
{
  type: "trees".
  list: ["fir","pine","birah"]
}];

var secondTree = myObj[1].list[1];
console.log(secondTree); //it will printed => pine
```
 ## Record Collection
```javascript

var collection = {
  "123":{
    "album":"album1",
    "artist":"artis1",
    "track":[
      "track1", "track2"
    ]
  },
  "456":{
    "album":"album1",
    "artist":"artis1",
    "track":[
      "track1", "track2"
    ]
  },
  "891":{
    "album":"album1",
    "artist":"artis1",
    "track":[
      "track1", "track2"
    ]
  }
};
 
//JSON.parse -> this method is for analyzed the content of a chain with json format
//JSON.stringify -> this method converts an object or value from JavaScript in a JSON chain text
var collectionCopy = JSON.parse(JSON.stringify(collection));

function updateRecords(id, prop, value){
  if (value ===""){
    delete collection[id][prop];
  }else if(prop === "Tracks"){
    collection[id][prop] = collection[id][prop] || [];
    collection[id][prop].push(value);
  }else{
    
  }
}

updateRecords("891","album2", "album1");
updateRecords("891","album2", "");
```
 ## Iterate with While Loops
```javascript
var myArray = [];

var i = 0;
while (i < 5){ //when the operator be true, the operator while continues with everything inside the curly braces
  myArray.push(i); // adds the value inside the variable i into myArray
  i++; //this is equal to => i = i + 1; the i will increase by 1 in each iteration
}
console.log(myArray) //the result is  [0, 1, 2, 3, 4]
```
 ## Iterate with For Loops
```javascript
var myArray = [];

for (var i =0; i < 5; i++){ //the first thing it do, is the variable assignment ,when the operator be true i < 5, the operator for continues with everything inside the curly braces and this is equal to => i = i + 1; the variable i, will increase by 1 in each iteration
  myArray.push(i); // adds the value inside the variable i into myArray
  i++; //
}
console.log(myArray) //the result is  [0, 1, 2, 3, 4]
```

 ## Generate Random Fractions
```javascript
function randomFraction(){
  return Math.random(); //this function return a value between 0 and 1, but never 1, almost 1
}

console.log(randomFraction());
```
 ## Generate Random Whole Numbers
```javascript

//assigns to the variable between 0 and 20, but never 20, almost 20
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);
function randomWholeNum(){
 // assigns to the variable between 0 and 10, but never 10, almost 10
  return Math.floor(Math.random() * 10);
}
console.log(randomWholeNum());
```
 ## Generate Random Whole Numbers within a range
```javascript
function ourRandomRange(ourMin, ourMax){
  return Math.floor(Math.random() * (ourMax - ourMin + 1)) + ourMin;
}
console.log(ourRandomRange(1,9));
```
 ## Use the parseInt Function
```javascript
function convertToInteger(str){
  //if the function can't convert the number from a string, then the function will return NaN (Not a Number)
  return parseInt(str);
}
console.log(convertToInteger("2"));
```
 ## Use the parseInt Function with a Radix
```javascript
function convertToInteger(str){
  //this function return the number in base 2 or whatever you want
  return parseInt(str, 2);
}
console.log(convertToInteger("10011"));
```
 ## Use the Conditional(Ternary) Operator
```javascript
function checkEqual(a,b){
  //can transform it in another expression more simple
  /*
  if ( a === b ){
    return true;
  }else{
    return false;
  }
  */
  return a === b ? true : false;
}
console.log(checkEqual(2,2)); //this function will return the value true
console.log(checkEqual(2,3)); //this function will return the value false
```
 ## Use Multiple Conditional(Ternary) Operators
```javascript
function checkSign(num){
  return num > 0 ? "positive" : num < 0 ? "negative" : "zero";
}
console.log(checkSign(2)); //this function will return the value positive
console.log(checkSign(-2)); //this function will return the value negative
console.log(checkSign(0)); //this function will return the value negative
```
 ## Differences Between tha var and let Keywords
```javascript
let catLastName = "Rodriguez";
var catName = "Anibal";
var quote ;
//when i use the var keyword then it will accept the declaration duplicate
//the var keyword is declare as global variable
var catName = "Beau";
//the program can't accept this, we will see an error message where will say, duplicate declaration "catLastName".
//keyword is declared as local variable, this means the variable will only use in the scope where was declare
let catLastName;
```

## Declare a Read-only Variable with the const Keyword
```Javascript
const number = 3.14 //The const keyword has the same properties as let, the difference is that it cannot be modified
```
## Prevent Object Mutation
```Javascript
function freezeObj(){
  const MATH_CONSTANTS = {
    PI: 3.14
  };
  //with this function i prevent object mutation
  Object.freeze(MATH_CONSTANTS);

  try{
    MATH_CONSTANTS.PI = 99;
  }catch( ex ){
    console.log(ex);
  }
  return MATH_CONSTANTS.PI;
}

const PI = freezeObj();
```
## Use Arrow Functions to Write Concise Anonymous Functions
```Javascript
var magic = function() {
  return new Date();
}
//the above we can write it like this 
var magic = () => {
  return new Date();
}

//more short
const magic = () => new Date();
```
## Write Arrow Functions with Parameters
```Javascript
var myConcat = function(arr1, arr2) {
  return arr1.concat(arr2)
}

//more short
const myConcat = (arr1, arr2) => arr1.concat(arr2)
```
## Write Higher Order Arrow Functions
```Javascript
const squeareList = (arr1, arr2) => {
  const squaredIntegers = arr.filter (num => Number.isInteger(num) && num > 0).map(x => x * x);
  return squaredIntegers;
}

const increment = (function() {
  //if it isn't paased in, it will be set to 1 automatically
  return function increment(number, value = 1) {
    return number + value;
  }
})();
console.log(increment(5, 2));//the result will be 7
console.log(increment(5)); //the result will be 6
```
## Use the Rest Operator with Function Parameters
```Javascript
const sum = (function(){
  return function sum(x, y, z){
    const args = [x, y, z];
    return args.reduce((a,b) => a + b, 0);
  };
})();

const sum = (function(){
//i put the rest operator (...) and convert everythong in an array
  return function sum(...args){
    return args.reduce((a,b) => a + b, 0);
  };
})();
console.log(sum(1,2,3,6));
```
## Use the Spread Operator to Evaluate Array In-Place
```Javascript
const arr1 = ['JAN', 'FEB', 'MAR', 'APR', 'MAY'];
let arr2;
(function(){
//in this case arr2 is equal to arr1, and when i change one of the values from arr1, i change arr2 too, because they are the same.
  arr2 = arr1;
  arr1[0] = 'potato'
})

let arr2;
(function(){
  //when i put the Spreed Operator([...]) then i copy all values from arr1 to arr2, when i change one of the arr1 values, the arr2 doesn't change, because they aren't the same
  arr2 = [...arr1];
  arr1[0] = 'potato'
})

console.log(arr2);
```

## Use Destructuring Assignment to Assign Variables from Objects
```Javascript

var voxel = {x:3.6, y:7.4, z:6.54};
var x = voxel.x; //x = 3.6
var y = voxel.y; //y = 7.4
var z = voxel.z; //z = 6.54

//this is the other form to create variables and assign the values from the array voxel instead of the previously
const {x:a, y:b z: c} = voxel; //a:3.6, b:7.4, c:6.54

const AVG_TEMPERATURES = {
  today: 77.5,
  tomorrow: 79
};

function getTempOfTmrw(avgTemperatures){
  //const tempOfTomorrow = undefined; 
  //inteasd of the previously i put the curly braces and colon, and now
  // AVG_TEMPERATURES.tomorrow has the value avgTemperatures
  const {tomorrow: tempOfTomorrow} = avgTemperatures; 

  return tempOfTomorrow;
}

console.log(getTempOfTmrw(AVG_TEMPERATURES));
```
## Destructuring Assignment with Nested Objects
```Javascript
const LOCAL_FOREST = {
  today: {min: 72, max:83},
  tomorrow: {min:73.3, max:84.6}
}

function getMaxOfTmrw(forecast){

  //when i put the following sintaxis i say that maxOfTomorrow is equal to tomorrow.max, if y run this function i will get the value 84.6 of the object
  const { tomorrow: {max : maxOfTomorrow} } =  forecast;

  return maxOfTomorrow;
}

console.log(getMaxOfTmrw(LOCAL_FOREST));
```
## Use Destructuring Assignment to Asign variables from arrays
```Javascript
//when I put the comma without nothing in the middle and the following is a variable, then my array take the next value from the other array, then z is equal to 1, x is equal to 2 and y is equal to 4, because I used the comma without nothing in the middle
const [z, x, ,y] = [1,2,3,4,5,6];
console.log(z, x, y);

let a = 8, b = 6;
(() => {
  /*the following destructuring is about to switch a with b, when I assign [a,b] with the following array [b, a] I change the order of the values, and then I print a and b, and the variables are change*/
  [a,b] =  [b,a]
})();

console.log(a); // it's going to print 6
console.log(b); // it's going to print 8
```
## Use Destructuring Assignment with the Rest Operator
```Javascript
//I have the elements array with the numbers from one to ten
const source = [1,2,3,4,5,6,7,8,9,10];

function removeFirstTwo(list){

//when I put the brackets and in the middle two commas without any value and followed by ...arr, I say to the program, copy all elements from the list without the first and second elements
  const [, , ...arr] = list;
  return arr;
}

const arr = removeFirstTwo(source);
console.log(arr); // it's going to print [1,2,3,4,5,6,7,8,9,10]
console.log(source); // it's going to print [3,4,5,6,7,8,9,10]

```

## Use Destructuring Assignment to pass an object as a function's parameters
```Javascript
const stats = {
  max: 56.78,
  standard_deviation: 4.34,
  median: 34.54,
  mode: 23.87,
  min: -0.75,
  average: 35.85
}

const half = (function() {
  /*
  return function half(stats) {
    return (stats.max + stats.min) / 2.0;
  };*/
  
  return function half({max, min}) {
    //instead of the above, I used the following, I put curly braces and the variables of the object that I needed, in this case, max and min from the object, and then I remove stat.max and put only max and the same for the other, I remove stat.min and put only min
    return(max + min) / 2.0;
  };
})();
console.log(stats);
console.log(half(stats));
```
# Create String using Template Literals
```Javascript
const person = {
  name: "Zodiac Hasbro",
  age:56
};

const greeting = `Hello, mi name is ${person.name}! 
I am ${person.age} years old`;

console.log(greeting);

const result = {
  succes : ["max-length", "non-amd", "prefer-arrow-functions"],
  falure : ["no-var", "var-on-op", "linebreak"],
  skipped : ["id-blacklist", "non-dup-keys"],
};

function makeList(arr){
  const resultDisplayRrray = [];
  for (let i = 0; i < arr.length; i++){
    resultDisplayArray.push(`<li class="text-warning">${arr[i]} </li>`);
  }
  return resultDisplayArray;
}

const resultDisplayArray = makeList(result.falure);
console.log(resultDisplayArray);
```

# Write Concise Object Literal Declarations Using Simple Fields
```JavaScript
const createPerson = (name, age, gender) => {

  return {
    name: name,
    age:age.
    gender: gender
  };
};
//instead of the above, I rewriting the code more simple because this change does the same thing the above and then i receive  an object
const createPerson = (name, age, gender) => ({name, age, gender});

console.log(createPerson("Zodiac Hasbro",56,"Male"));
```
# Write Concise Object Declarations Functions
```JavaScript
const bicycle = {
  gear:2.
  setGear: function(newGear){
    this.gear = newGear;
  }
};
//instead of the previous code, in an object, we can put a function, but I can rewrite the function without the function clause
const bicycle = {
  gear:2.
  setGear(newGear){
    this.gear = newGear;
  }
};

console.log(createPerson("Zodiac Hasbro",56,"Male"));
```

# Use Class Syntax to Define a Constructor Function
```JavaScript

//old way to creatte a contructor function
var SpaceShuttle = function(targetPlanet){
  this.targetPlanet = targetPlanet;
}

//instead of the previous code, I use the next one and does the same thing as the previous one
class SpaceShuttle{
  constructor(targetPlanet){
    this.targetPlanet = targetPlanet;
  }
}

var zeus = new SpaceShuttle('Jupiter');

console.log(zeus.targetPlanet);


//another example
function makeClass(){
  class Vegetable {
    constructor(name){
      this.name = name;
    }
  }
  return Vegetable;
}

const Vegetable = makeClass();
const carrot = new Vegetable('carrot');
console.log(carrot.name);
```
# Use getter and setter to Control Access to an Object
```Javascript
class Book{
  constructor(author){
    this._author = author;
  }

  //getter
  get writer(){
    return this._author;
  }
  
  //setter
  set writer(updateAuthor){
    this._author =  updatedAuthor;
  }
}

function maskeClass(){
  class Thermostat{
    constructor(temp){
      this._temp = 5/9 * (temp - 32);
    }

    get temperature(){
      return this._temp;
    }

    set temperature(updatedTemp){
      cthis._temp = updatedTemp;
    }


  } 
  return Thermostat;
}

const Thermostat = makeClass();
const thermos = new Thermostat(76);
let temp = thermos.temperature; //this line means that we use the getter
thermos.temperature = 26; //this line means that we use the setter
temp = thermos.temperature;

console.log(temp);
```
# Understand the Differences Between import and require
```Javascript
//String_functions.js
//export this function and then we can use it in other files
export const capitalizeString = str => str.tpUpperCase();

//index.js

//we import the function we needed
import { capitalizeString } from  "./String_functions"
const cap = capitalizeString("Hello");

console.log(cap);
```
# Use export to Reuse a Code Block
```Javascript
//index.js

const capitalizeString = (string) => {
  return string.charAt(0).toUpperCase() + string.slice(1);
}

export { capitalizeString };

export const foo = "bar";
export const bar = "foo";
```
# Use * to Import Everything from a File
```Javascript

//first, write import and then asterisk which means that I import all from the destine file 
import * as capitalizeStrings from "capitalize_strings";
```

# Create an Export Fallback with export default
```Javascript
//math_function.js
export default function subtract(x,y) {return x-y;}
```
# Import a defacult Export
```Javascript
import subtract from "math_function";
subtract(7,4);
```
