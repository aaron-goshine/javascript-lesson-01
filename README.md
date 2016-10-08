
# JavaScript lesson 01
---------------------------
Source files in order to conduct an introduction to the JavaScript  workshop


### A Brief History of JavaScript

ooooooooo

##### Further reading
[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction)

### JavaScript Today.
##### es5, es6, esNEXT

### Comments in JavaScript code
JavaScript supports two styles of comments.
Any text between a `//` and the end of a line is treated
as a comment and is ignored by JavaScript.
Any text between the characters `/* and */` is also treated as a comment;
these comments may span multiple lines

```
// This is a single-line comment.

/*
   This is multilined comment
   that can go on forever
 */
```

### Literals
A literal is a data value that appears directly in a program. The following are all literals:

```
12 // The number twelve

1.2 // The number one point two

"hello world" // A string of text
'hello world' // A string of text

true // A Boolean value

false // The other Boolean value

/javascript/gi // A "regular expression" literal (for pattern matching)

null // Absence of an object

[] // An Array initialiser

{} // An Array initialiser

```

### Variables

An identifier is simply a name. In JavaScript, identifiers are used to name variables andfunctions and to provide labels for certain loops in JavaScript code. A JavaScript identifiermust begin with a letter, an underscore (_), or a dollar sign ($). Subsequent characterscan be letters, digits, underscores, or dollar signs. (Digits are not allowed as thefirst character so that JavaScript can easily distinguish identifiers from numbers.) Theseare all legal identifiers:
```i
my_variable_name
v13
_dummy$str
```#### Reserved WordsJavaScript reserves a bunch of keywords that you cannot use as variable names in your programs:
```
break delete function return typeof case do  if  switch  var  catch  else  in  this  void  continue false  instanceof throw  while debugger finally new  true  with default for null try class const enum export extends import super  implements let private public yield interface package protected static
```
Strict mode also imposes restrictions on the use of the following identifiers.
They are not fully reserved, but they are not allowed as variable, function, or parameter names:
``` arguments eval
 ```ECMAScript 3 reserved all the keywords of the Java language, and although this hasbeen relaxed in ECMAScript 5, you should still avoid all of these identifiers if you planto run your code under an ECMAScript 3 implementation of JavaScript:
```
abstract  double  goto native static boolean  enum  implements  package super byte  export import private synchronized char extends int protected throws class final interface public transientconst float long short volatile
```

_exercise checkpoint_

##### Data types

```
// Number
var length = 16;

// String
var lastName = "Johnson";

// Object
var x = {firstName:"John", lastName:"Doe"};

// Boolean
var bool = false;

```
_exercise checkpoint_

##### Statements and Expressions

JavaScript distinguishes expressions and statements. An expression produces a value and can be written wherever a value is expected, for example as an argument in a function call. Each of the following lines contains an expression:

```
myvar
3 + x
myfunc("a", "b")

```
Roughly, a statement performs an action. Loops and if statements are examples of statements. A program is basically a sequence of statements (we’re ignoring declarations here). Wherever JavaScript expects a statement, you can also write an expression. Such a statement is called an expression statement. The reverse does not hold: you cannot write a statement where JavaScript expects an expression. For example, an if statement cannot become the argument of a function.

```

var x;

if (y >= 0) {

  x = y;

} else {

  x = -y;

}

```

_exercise checkpoint_

##### Control flow and branching

_exercise checkpoint_

##### Control flow and branching

_exercise checkpoint_

##### Objects

_exercise checkpoint_


##### Arrays

_exercise checkpoint_


##### Functions

_exercise checkpoint_

##### Scope

_exercise checkpoint_

### JavaScript environments.
