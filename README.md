# Interview-questions


<details>
  <summary><h2>JS Interview Questions</h2></summary>
  1.What is Javascript?

* Javascript is a programming language that is used for converting static web pages to interactive and dynamic web pages.

2.What are the data types in Javascript?

```js
  1. Primitive
    1. Numbers
    2. Strings
    3. Boolean
    4. Undefined
    5. Null

  2. Non-Primitive
    1. Object
    2. Array
    3. Function
    4. Date
    5. RegExp
```

3.Diff between primitive & non-primitive data types?

| SI.No     | Primitive Data Types      | Non Primitive Data Types  
| ------------- | ------------- | --------    |
| `1`        | `Primitive data types can hold only single value` | `Non primitive data types are mutable and their values can be changed`.   |
| `2`         | `Primitive data types are immutable and their values cannot be changed` | `Non primitive data types are mutable and their values can be changed` |
| `3`         | `Simple data types` | `Complex data types` |


Primitive Data Types:
```js
    Ex:
      let variable = "temp"

    Real time Ex: Tv, Only watching
```
Non Primitive Data Types

```js
    Ex: 
      let object = {
        name: "Hello",
        phone: 123
        click: function() {
          console.log("***)
        }
      }

    Real time Ex: Computer, Watching, browsing,.. etc
```

4.What are arrays, functions and objects?

Arrays:

* An array in is used to store a collection of values, such as a list of numbers or names.

Functions:

* Function is a block of code that performs a specific task or returns a value.

Objects:

* Object is a non primitive data type which can hold multiple values or a combination of values and functions.


5.What is scope in Javascript?
  
I).Local Scope 

  * Variables declared inside a function have local scope,
  * They can be accessed within the function not outside.
```js
  Ex: 
    function myFunction() {
      let a = 1;
      console.log(a)
      // => 1
    }
    myFunction()
    console.log(a)
    // => Error: a is no defined
```

II)Global Scope
  * Variables declared outside any function have global scope,
  * They can be accessed from anywhere within a program.

```js
  Ex:
    let b = 2;

    function myFunction() {
      console.log(b)
      // => 2
    }

    myFunction()
    console.log(b)
    // => 2
```

</details>

<details>
  <summary><h2>JS Coding</h2></summary>

  Coding
</details>