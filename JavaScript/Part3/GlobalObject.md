# Global Object function

>JavaScript runtime has so many global objects and functions.
Global object function is a function in JavaScript which is called as **Object**

Let's see an example:

```javascript
console.log(Object); //Global constructor function with name as Object
```
>Image

Let's check the prototype object of the constructor fucntion
```javascript
console.log(Object.prototype); //Global constructor function with name as Object
```
Image

This is an object which is inherited by all the other objets in JavaScript by default

Above statement gives the definition of the *Object* function. 
Let's call this function
```javascript
console.log(Object()); //Outputs: Empty object with __proto__ prperty
```
Object() output is empty with __proto__ property

__proto__ property points to the prototype object of the constructor function
```javascript
var a = Object()
console.log(a.__proto__); //Outputs: An object with some properties
console.log(a.__proto__ === Object.prototype) //true
```
Object() is inherited by all the all other objects in JavaScripts




