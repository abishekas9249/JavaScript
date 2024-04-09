### JavaScript
JavaScript is a dynamic, interpreted and weakly typed (datatypes are assumed automatically) programming language which is compiled at runtime.

| Feature                                           | JavaScript                                                 | Java                                                 |
|---------------------------------------------------|------------------------------------------------------------|------------------------------------------------------|
| Type System                                       | Loosely typed language                                      | Strongly typed language                               |
| Primary Use Case                                  | Scripting language used for creating interactive webpages    | Object-oriented language for enterprise applications |
| Execution Environment                            | Can run in both server-side and client-side browsers         | Can run in any virtual machine or browser            |
| Object Model                                     | Prototype-based                                              | Class-based                                          |
| Concurrency Support                              | Does not support multithreading                              | Supports multithreading                              |
| File Extension                                   | .js                                                          | .java                                                |
| Memory Usage                                     | Uses less memory                                             | Uses more memory                                     |

# Variables
Variable is a data container which holds some data and in JavaScript. 
We can create a variable in Three ways: 
* Using let keyword: **ES6 version of JavaScript**
let keywords are mainly used for declaring blocked scoped variables. We cannot declare a variable more than once if we defined that previously in the same scope.
  * Example:
    ```js
    let name='first name';
    

* Using var keyword: **ES5 version of JavaScript**
When we declare a variable with var keyword then that variable declarations are goes to the top of the code, this process is called **Variable Hosting**.
  * Example:
    ```js
    var name='first name';
  
* Using const keyword: **ES6 version of JavaScript**
Once we declared a variable with const keyword then that variable cannot be changed, and it is also used for declaring blocked scoped variables. 
  * Example:
    ```js
    const name='first name';
 
# Operators
Operators are syntax feature in JavaScript and that allows us to manipulate values. 

* Arithmetic operators: +, -, *, /, %, **( ** power operator )**

* Assignment operators: +=, -=, *=, /=, %=, **= 

* Relational operators: <, >, <=,>=, == 

* Comparision operators:
  * **!=(not equals to)**
  * **==(compares only the value not specific to type of the data)**
  * **===(strict equal to)(compares value as well as type of the data)**

* Increment/decrement operators: ++, -- 

* Logical operators: &&, ||, ! 

* Ternary operator: ?:

# Datatypes
Datatypes are the data representation of the objects in javascript and they are of six types
* **Numbers** -it contains all the numeric types which inculdes negative,positive,floating numbers...
* **Strings** -it contains data in specified with single,double and back quotes
  * There is a special way of consoling the output as Strings in the form of **Interpolation Syntax - `${}`** it is well known as ***String Interpolation Syntax***
* **Boolean** -it can only be true or false.
* **Undefined** -Value taken by a variable that hasn't declared or defined a value.
* **Null** -Empty Value.
* **BigInt** -Larger Integers than the number type can Hold.
# Conditional Statements
Conditional Statements are the Condition reason to accept and respond accordingly to the timeline.
* **Simple If**
    ```js
      if(true){
          console.log("Simple If Statement");
      }
    
* **If Else**
    ```js
      if(true){
          console.log("If Statement");
      }else{
          console.log("Else Statement");
      }
    
* **If ElseIf Else**
    ```js
      let val=55;
      if(val<50){
          console.log("Fail");
      }else if(val==50){
          console.log("Just Pass");
      }else{
          console.log("Good Pass");
      }
    
* **Switch**
    ```js
    let a = 2; 
    switch (a) { 
        case 1: 
            a = 'one'; 
            break; 
        case 2: 
            a = 'two'; 
            break; 
        default: 
            a = 'not found'; 
            break; 
    } 
    console.log(`The value is ${a}`); 
    
