# Objects in JavaScript
###What are Objects in JavaScripts

>An object in JavaScript is a collection of key-value pair. Each key-value pair is called as a property. 
>A property can be a function, an object itself or any primitive data type i.e. integer, string, array etc.
>Functions are called as methods. Consider a simple object:

```javascript
var human = {
	firstName: "Virat",
	lastName: "Kohli",
	age: 30,
	fullName: function(){
		return this.firstName + " " + this.lastName		
	}
}
```
>Here firstName, lastName, and fullName are properties of the same object i.e. Human.
>Every human will have these properties but their values may be different i.e. firstName, lastName may 
have different value for different human.
2. How java 
