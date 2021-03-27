# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let
cons
var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Functions are "subprograms" to help define how and if a particular task should be performed.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility: A class should habe only have one reason to change and one job.

Open-Closed: Objects should be open to add more data, but closed to change the objects or classes themselves.

Liskov Substition: All sub or derived classes should be able to be substituted for their parent class.

Interface Segregation: Make a variety of client-specific interfaces if needed rather than one general-purpose interface.

Dependency Inversion: High-level modules should not depend on low-level modules, but both depended on abstractions, (i.e., interfaces). Additonally, concrete implementations should be dependent on abstractions (or interfaces), for the optimal user experience.

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
'pineapple' is at the [2] index position because [] start at a 0 index, which means 'apple' is [0], 'banana' is [1], and so on.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
let you[3].friends = them {name:'Them'}.push()
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
let x=10
if(x>5){
  console.log ('I DID IT')
} else if (x<9){
  console.log ('OH SO CLOSE')
}

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
That is the incrementer space where to increase 'i' by 1 would be i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. Index.HTML is typically the first file accessed to determine the type of DOM you are intending. HTML tags tell the document that is the type of document that will be rendered.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Data types (Primitives):
1. undefined: not assigned a value
2. null (Structural Root Primitive): intentionally assigned a Null value to a nonexistent or invalid object
3. Boolean: true or false
4. Number: any numeric value assigned to an object
5. BigInt: Optimal for large integers(or numbers) behaves like a number and      can be  a assigned by adding an n to the end of a number or by using BigInt(). Can not be used in a Math() method but can be used with operaters because considered to loosely have both NUMERIC (integer) and string (n) value.
6. String: 'represents textual data'
7. Symbols: Unique and immutable primitive value that may be used as a key in an Object.

Structural Type:

8. Objects: Collection of properties (i.e., keys= string or symbol value). Two different types of properties, data properties and accessor properties (associates a key with 2 different accessor functions (get or set certain values of data ))

9. Functions: regular objects that are also callable


```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameter are the variables found in the function definition... 

function example(x>10){
  console.log('RIGHT')
}

Arguments are what are called through the function to determine the result of the function 

let x=20
function example(x>10){
  console.log('RIGHT)== TRUE
}


```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values (see Primitive data types) are more singular and are stored in a Stack's memory

Reference values are typically objects or arrays that store memory in a Heap and are more dynamic than primitive values.
```