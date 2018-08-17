# Function_Anonymous

## Description
The goal is understanding : 
  * A - function hoisting : 
    * only named function are hoisted
    * anonymous fnction are not hoisted
  * Scope : 
    * var has function scope
        * Variables are defined in the scope wgere they are used.
    * let has block scope
  * Pure function : 
    * Are the arguments in read-only || argument of the function are on the right-end side of the equal;
    * Are all variable param defined in the frame
    
A function : can have information from the arg/param or from global scope.    
    
    
```javascript
var a = 1;

function plusone(){
  a++;
  let result = a; 
  return result
  }

var b = plusone()
// var a = 1;

// var b = function(){
//   a++;
//   let result = a; 
//   return result
//   }
// console.log(b);
```
