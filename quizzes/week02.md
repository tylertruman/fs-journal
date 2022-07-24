# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Code designed to perform a task when it is called or invoked.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
1. Single responsibility
2. Open closed
3. Liskov substitution
4. Interface segregation
5. Dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, because items in an array start from the beginning and the first in line is in position 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them);
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(1 > 0){
  console.log('true')
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
statement 3 belongs inside the empty space. i++ in that space would increase i by one every time after the code block has been executed.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. HTML is the first file that gets accessed to render the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
They only have 8 ECMAScript language types listed unless you count Numeric Types.

1. Undefined
2. Null
3. Boolean
4. String
5. Symbol
6. Number
7. BigInt
8. Object
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Function parameters are listed in the function/method definition. and arguments are the values passed/received by the function/method.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are fixed, you can't add , change, or delete properties to it. But with a reference value you can. 
```