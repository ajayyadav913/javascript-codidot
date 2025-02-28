# JavaScript-basic Notes
### Variable Declaration
In JavaScript, variables are declared using the let, const, or var keywords.

#### Let
- let is used to declare a variable that can be reassigned.
- let variables are block-scoped, meaning they are only accessible within the block they are declared in.
- Example: let name = 'John';

#### Const
- const is used to declare a constant variable that cannot be reassigned.
- const variables are also block-scoped.
- Example: const PI = 3.14;

#### Var
- var is used to declare a variable that can be reassigned.
- var variables are function-scoped, meaning they are accessible throughout the function they are declared in.
- Example: var age = 30;
- Note: var is generally considered outdated and should be avoided in favor of let and const.

#### Variable Assignment
Variables can be assigned a value using the assignment operator (=).

#### Assignment Operator
- The assignment operator (=) is used to assign a value to a variable.
- Example: let name = 'John';

#### Assignment Operators
- There are several assignment operators in JavaScript, including:
    - = (assignment)
    - += (addition assignment)
    - -= (subtraction assignment)
    - *= (multiplication assignment)
    - /= (division assignment)
    - %= (modulus assignment)

#### Variable Data Types
JavaScript variables can hold different data types, including:

##### Primitive Data Types
- number: a numeric value (e.g. 42)
- string: a sequence of characters (e.g. "hello")
- boolean: a true or false value
- null: a null value
- undefined: an undefined value

#### Complex Data Types
- object: an object (e.g. { name: "John", age: 30 })
- array: an array (e.g. [1, 2, 3])
- function: a function (e.g. function greet(name) { console.log("Hello, " + name); })

#### Variable Scope
Variable scope refers to the region of the code where a variable is defined and accessible.

##### Global Scope
- Variables declared outside of any function or block have global scope.
- Global variables are accessible throughout the code.

##### Local Scope
- Variables declared within a function or block have local scope.
- Local variables are only accessible within the function or block they are declared in.

##### Block Scope
- Variables declared with let or const have block scope.
- Block-scoped variables are only accessible within the block they are declared in.

##### Variable Hoisting
Variable hoisting refers to the behavior of moving variable declarations to the top of their scope.

##### Var Hoisting
- Variables declared with var are "hoisted" to the top of their scope.
- This means that the variable is moved to the top of the scope, regardless of where it is actually declared.

##### Let and Const Hoisting
- Variables declared with let or const are not "hoisted" in the same way as var.
- Instead, they are "hoisted" to the top of their block scope, but are not initialized until they are actually declared.

# Print value in table
``` 
const accountId =12345
let accountEmail ="ajay.yadav913@gmail.com"
var accountPassword ="123458"
accountCity = "Ghaziabad"

// console.log(accountId);

console.table([accountId,accountEmail,accountPassword,accountCity]) 

/* prefer to not used var variable in javascript.
   Because of issue in block scope and functional scope
*/

```
### JavaScript Documentation 
-"https://tc39.es/ecma262/"
 
#### JavaScript:Data Types

1. Number: A numeric value, e.g. 42, 3.14.
2. String: A sequence of characters, e.g. "hello", 'hello'.
3. Boolean: A true or false value.
4. Null: A null or empty value.
5. Undefined: An undefined or uninitialized value.

#### Complex Data Types

1. Object: A collection of key-value pairs, e.g. { name: "John", age: 30 }.
2. Array: A list of values, e.g. [1, 2, 3], ["a", "b", "c"].
3. Function: A block of code that can be executed, e.g. function greet(name) { console.log("Hello, " + name); }.

#### Other Data Types

1. Symbol: A unique and immutable value, introduced in ECMAScript 2015.
2. BigInt: A large integer value, introduced in ECMAScript 2020.