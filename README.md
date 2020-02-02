# what-i-learned-in-week-2

## Intro to Javascript and basic concepts of programming

* various types of variables and its types of values
* operators
* functions and how they input and output/methods 



### Variables

We start by using declare "word" to create a variable. _let_ is easily changable,
_const_ stands for constant and is less easily changable.  
ie.  
```
let randomNumberForExampleBe = 94724792;

const randomStrThatIsHardToChange = 'Linux/'s packaging systems are different for each distro';
```


There is no need to declare a type of value for a variable since it's automatically determined by the language,  
unlike other programming languages where you need to explicitly provide the type of value.

There are types of variable:
* Strings: '  ' in single or double quotations marks are characters that represent some text and can include any character  
  as long as we use '/' to escape some special characters.  
  example 'Bogdan/'s weekend was spent studying'
* Boolean: it is either _True_  or _False_ . example Q: 'do I have an apple/?' A: 'No' that means value _False_
* Number: could be _integers_ (whole numbers) ie, 5, 6 123,etc;  and _float_ decimal numbers ie, 87.24241123 , 33.333, etc
* NaN: is Not A Number . basically this will return that in case where type of variable other than a number and  
  is not changable to number
* Undefined: type variable is not declared
* Null: doesn't exists in a universe

### Operators

There are two types of operators in programming that we have covered so far and they are Arithmetic and Relational operators

#### Arithmetic Operators

| Symbol | Operation | description |
| ------ | :-------: | ----------: |
| + | addition |  x + y or 2 + 2 equals 4 |
| - | subtraction | x - y or 3 - 2 equals 1 |
| * | multiplication | x * y or 4 * 2 equals 8 |
| / | division | x / y or 6 / 3 equals 2 |
| % | modulus | x % y or 10 % 3 equals 1, divides a number and returns remainder |


#### Relational Operators 

| Symbol | Operation | description |
| ------ | :-------: | ----------: |
| == | equal | x == y checks if both variables are same |
| != | no equal | x != y checks if both variable are different
| > | greater than | x > y checks x greater than y |
| < | less than | x < y checks x less than y |
| >= | greather than or equal | x >= y checks x greater or equal y |
| <= | less than or equal | x <= y checks x less than or equal y |

For arithmetic or any other operators there follows a precedence which you can get a cheatshet table 
[Mozilla Reference Precedence table for Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)

### Function and methods

Let's start with example below:
``` 
function initials (fullName) {
  return fullName[0] + '.' + fullName[fullName.indexOf(' ') + 1] + '.';
}
```

"word" function creates a function that can use input and output some kind of a result. "word" return "returns" a result of some kinda of operations after it is done. Function can take a parameter ``` function nameOfFunction (parameter) ``` then we can use that paramater inside of a function. Once we create a parameter or use a variable then we can call inbuilt method like .indexof .toUpperCase .splice .split , etc.
