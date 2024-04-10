## Functions in Detial

Functions are mainly used for reusability of code. We define a function with function keyword, and we can also pass data into a function. 

* We define Functions in three Different Ways
  * **Normal Function Declaration**
    * Example 1
      ```js
      function greetUser(name)  
      { 
              Console.log ('hi'+name); 
      }
      greetUser("john");
    * Example 2
      ```js
      console.log(greeting());
      function greeting(){
        console.log("Hope you're are good?");
    
      }
    * Example 3
      ```js
      console.log(add(2,4));
      function add(a,b){
        return a+b;
    
      }
  * **Function Expression or Anonymous Function**
    * Example 1
      ```js
      var greet=function(name){
          console.log("Hi"+name)
      }
      greet("Joseph");
    * Example 2
      ```js
      var add=function(a,b){
          return a+b;
      }
      add(5,6);
  * **Arrow Functions**
    * Example 1 
      ```js
      const greetings = name => {
        console.log(`Hello, ${name}!`);
      };
      greetings('John');
    * Example 2
      ```js
      let cube=num=>{
        return num**3;
      };
      cube(2);
