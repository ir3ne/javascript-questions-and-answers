<div align="center">
	<a href="https://www.buymeacoffee.com/ir3ne" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-green.png" alt="Buy Me A Coffee" style="height: 46px !important;width: auto !important;" ></a>
</div>

# Welcome to JavaScript Questions and Answers

![js-header](https://github.com/ir3ne/javascript-questions-and-answers/assets/23403047/4e5c178b-224d-4e71-8f40-ac8233b65211)

This is a collection of the concepts I have encountered throughout my career's path and the questions I have asked about them. Some questions might seem redundant but the purpose of this is to investigate, where present, the connections between different concepts that make this language so interesting and flexible. There are also practical examples of topics whose definition is known but perhaps have never been used in practice.
These questions and answers can be used to prepare for an interview or for personal study and lecture.

In writing the answers I was helped by AI and the book "JavaScript: The Definitive Guide" by David Flanagan.

---

<a name="questions"></a>
|Questions|
:--
|1. [What is JavaScript and what is the meaning of "interpreted" language?](#what-is-javascript-and-what-is-the-meaning-of-interpreted-language?)|
|2. [What is the lexical scope?](#what-is-the-lexical-scope?)|
|3. [What is the difference between scope and context?](#what-is-the-difference-between-scope-and-context?)|
|4. [What is enum and is it available in JavaScript?](#what-is-enum-and-is-it-available-in-javascript?)|
|5. [What are JavaScript accessors?](#what-are-javascript-accessors?)|
|6. [What is the prototype chain?](#what-is-the-prototype-chain?)|
|7. [What is a pure function?](#what-is-a-pure-function?)|
|8. [What is a callback?](#what-is-a-callback?)|
|9. [What is a promise?](#what-is-a-promise?)|
|10. [What is a closure?](#what-is-a-closure?)|
|11. [What does it mean that JavaScript has First-class functions?](#what-does-it-mean-that-javascript-has-first-class-functions?)|
|12. [What is a higher-order function?](#what-is-a-higher-order-function?)|
|13. [Are concepts of higher-order function and closure connected?](#are-concepts-of-higher-order-function-and-closure-connected?)|
|14. [What is the difference between arrow functions and the regular functions?](#what-is-the-difference-between-arrow-functions-and-the-regular-functions?)|
|15. [What is the difference between call, apply and bind?](#what-is-the-difference-between-call,-apply-and-bind?)|
|16. [What is a proxy and what are some practical uses?](#what-is-a-proxy-and-what-are-some-practical-uses?)|
|17. [What is the event flow and what are its phases?](#what-is-the-event-flow-and-what-are-its-phases?)|
|18. [What's the difference between event propagation and event bubbling?](#what's-the-difference-between-event-propagation-and-event-bubbling?)|
|19. [What is an event loop?](#what-is-an-event-loop?)|
|20. [What is a CustomEvent and what is the dispatchEvent() method?](<#what-is-a-customevent-and-what-is-the-dispatchevent()-method?>)|
|21. [What are the possible ways to create objects in JavaScript?](#what-are-the-possible-ways-to-create-objects-in-javascript?)|
|22. [What is the difference between Object and Map?](#what-is-the-difference-between-object-and-map?)|
|23. [What are the mutable and immutable array's methods?](#what-are-the-mutable-and-immutable-array's-methods?)|
|24. [What does array-like mean?](#what-does-array-like-mean?)|
|25. [What is the difference between for...of and for...in loop?](#what-is-the-difference-between-for...of-and-for...in-loop?)|
|26. [What are asynchronous operations?](#what-are-asynchronous-operations?)|
|27. [What are async and await?](#what-are-async-and-await?)|
|28. [What is JSON and what are its common operations?](#what-is-json-and-what-are-its-common-operations?)|
|29. [What is Response json() method?](<#what-is-response-json()-method?>)|
|30. [What is strict mode?](#what-is-strict-mode?)|
|31. [What is the difference between ReferenceError and TypeError?](#what-is-the-difference-between-referenceerror-and-typeerror?)|
|32. [What is a polyfill?](#what-is-a-polyfill?)|
|33. [What is the Temporal Dead Zone?](#what-is-the-temporal-dead-zone?)|
|34. [What is tree shaking?](#what-is-tree-shaking?)|
|35. [What is TypeScript?](#what-is-typescript?)|
|36. [What is BOM?](#what-is-bom?)|
|37. [What is same-origin policy?](#what-is-same-origin-policy?)|
|38. [What is IndexedDB?](#what-is-indexeddb?)|
|39. [What is a module?](#what-is-a-module?)|
|40. [What is a Web API?](#what-is-a-web-api?)|
|41. [How does destructuring work in javascript, and what are its use cases?](#how-does-destructuring-work-in-javascript-and-what-are-its-use-cases?)|
|42. [What are template literals, and how do they differ from string concatenation?](#what-are-template-literals-and-how-do-they-differ-from-string-concatenation?)|
|43. [Understanding the difference between event.preventDefault() and event.stopPropagation() in JavaScript](#understanding-the-difference-between-eventpreventdefault-and-eventstoppropagation-in-javascript)|
|44. [Understanding microtasks vs. macrotasks in JavaScript](#understanding-microtasks-vs-macrotasks-in-javascript)|
---

<a name="what-is-javascript-and-what-is-the-meaning-of-interpreted-language?"></a>

## 1 . What is JavaScript and what is the meaning of interpreted language?

JavaScript is a high-level, interpreted, versatile, and dynamic programming language primarily used for creating interactive and dynamic content on websites. It is one of the core technologies of the World Wide Web, alongside HTML (Hypertext Markup Language) and CSS (Cascading Style Sheets).

Here are some key aspects of JavaScript:

1. **Client-Side Scripting:** JavaScript is mainly employed for client-side scripting, meaning it runs in the user's web browser. This allows developers to enhance the interactivity and responsiveness of web pages.
2. **Object-Oriented:** JavaScript is an object-oriented language, utilizing objects to structure and organize code. Objects in JavaScript can represent real-world entities, complete with properties and methods.
3. **Event-Driven Programming:** JavaScript is often used for event-driven programming, where scripts respond to specific events triggered by user actions, like clicks or form submissions.
4. **Asynchronous Programming:** JavaScript supports asynchronous programming, allowing certain operations to occur in the background without blocking the main program execution. This is crucial for tasks such as fetching data from servers.
5. **Cross-Platform Compatibility:** JavaScript is supported by all major web browsers, ensuring that code works consistently across different browsers and platforms.
6. **Libraries and Frameworks:** JavaScript has a rich ecosystem of libraries and frameworks, such as jQuery, React, Angular, and Vue.js, which streamline development by providing pre-built functionalities.
7. **Server-Side Development:** With the advent of technologies like Node.js, JavaScript can also be used for server-side development, enabling developers to use a single language for both client and server-side scripting.

JavaScript plays a central role in modern web development, enabling the creation of dynamic and interactive user interfaces. It continues to evolve with new ECMAScript specifications and is widely used for building a variety of web applications, ranging from simple websites to complex single-page applications (SPAs).

#### What's the meaning of "interpreted" language?

In the context of programming languages, "interpreted" refers to a type of language execution where instructions are executed directly by an interpreter, as opposed to being compiled into machine code before execution. Here are the key characteristics of interpreted languages:

1. **No Compilation Step:** In interpreted languages, there is no separate compilation step. The source code is directly executed by an interpreter.
2. **Execution:** Interpreters typically don’t execute line by line, and the various JavaScript interpreters for sure don’t. Compilers and interpreters both have the same first step: process all the textual source code and convert it to an intermediate representation. That intermediate representation might be a syntax tree or might be a bytecode.
3. **Platform Independence:** Since the source code is executed by an interpreter, the same code can run on different platforms without the need for platform-specific compilation.
4. **Slower Execution:** Interpreted languages generally have a slower execution speed compared to languages that are compiled into machine code. This is because the interpretation process adds an extra layer of execution overhead.

Popular interpreted languages include JavaScript, Python, Ruby, and PHP. In contrast, compiled languages like C++ or Java are translated into machine code or an intermediate code before execution, and the resulting executable file is then run by the computer's hardware. Each approach (interpreted vs. compiled) has its own advantages and trade-offs, influencing factors such as development speed, execution speed, and platform independence.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-lexical-scope?"></a>

## 2. What is the lexical scope?

In JavaScript, lexical scope refers to the scope of a variable or a function based on its placement in the source code during the authoring phase. In other words, the visibility and accessibility of variables and functions are determined by their location within the code structure.

JavaScript language uses a lexical scoping model, which means that the scope of a variable is determined by where it is declared and not where it is executed. This is in contrast to dynamic scoping, where the scope is determined by the calling context at runtime.

Here's a simple example to illustrate lexical scope in JavaScript:

```javascript
function outerFunction() {
  let outerVariable = "I am in the outer function";

  function innerFunction() {
    let innerVariable = "I am in the inner function";
    console.log(outerVariable); // Accessing outerVariable from the outer scope
    console.log(innerVariable); // Accessing innerVariable from the current scope
  }

  innerFunction();
}

outerFunction();
```

In this example, **`outerVariable`** is defined in the outer function, and **`innerVariable`** is defined in the inner function. The inner function has access to both its own variables and the variables declared in the outer function. This is an example of lexical scope, where the scope is determined by the physical structure of the code.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-difference-between-scope-and-context?"></a>

## 3. What is the difference between scope and context?

In JavaScript, "scope" and "context" are related concepts but refer to different aspects of the language.

1. **Scope:**

   - **Definition:** Scope refers to the region of the code where a variable is defined and can be accessed.
   - **Types of Scope:**
     - **Global Scope:** Variables declared outside any function or block have global scope and can be accessed from anywhere in the code.
     - **Function Scope:** Variables declared inside a function have function scope and are only accessible within that function.
     - **Block Scope:** Introduced in ECMAScript 6 (ES6), block scope refers to the region within curly braces **`{}`** in constructs like **`if`**, **`for`**, and **`while`**.

   **Example:**

   ```javascript
   // Global scope
   const globalVar = 10;

   function exampleFunction() {
     // Function scope
     const functionVar = 20;

     if (true) {
       // Block scope (ES6 and later)
       let blockVar = 30;
     }
   }
   ```

2. **Context:**

   - **Definition:** Context refers to the value of the **`this`** keyword within a particular execution context (function or object).
   - **Types of Context:**
     - **Global Context:** When **`this`** is used outside of any function or object, it refers to the global object (e.g., **`window`** in a browser environment).
     - **Function Context:** The value of **`this`** inside a function depends on how the function is called. It can be the global object or an object that the function is a method of.
     - **Object Context:** When a function is a method of an object, **`this`** refers to that object.

   **Example:**

   ```javascript
   const globalVar = 10;

   function exampleFunction() {
     console.log(this); // Global context (in a browser, it may refer to the window object)
   }

   const obj = {
     prop: 42,
     method: function () {
       console.log(this.prop); // Object context
     },
   };

   exampleFunction(); // Global context
   obj.method(); // Object context
   ```

In summary, scope deals with the visibility and accessibility of variables, while context deals with the value of **`this`** and its binding within a particular execution context. Understanding both concepts is crucial for writing effective and bug-free JavaScript code.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-enum-and-is-it-available-in-javascript?"></a>

## 4. What is enum and is it available in JavaScript?

An enumeration, or enum, is a symbolic name for a set of values. Enums are commonly used to represent a fixed set of constants in programming. They make the code more readable and maintainable by providing meaningful names to values.

JavaScript itself did not have built-in support for enums. However, there are ways to simulate enums using various approaches.

### Simulating Enums in JavaScript:

1. **Object Literal:**

   ```javascript
   const Days = {
     Monday: "Monday",
     Tuesday: "Tuesday",
     // ... other days
   };
   ```

   Usage:

   ```javascript
   let today = Days.Monday;
   ```

2. **Array:**

   ```javascript
   const Days = ["Monday", "Tuesday" /*... other days*/];
   ```

   Usage:

   ```javascript
   let today = Days[0]; // Monday
   ```

### With TypeScript

Using TypeScript (a superset of JavaScript that adds static typing), enums are more explicitly supported.

```tsx
enum Days {
  Monday,
  Tuesday,
  // ... other days
}

let today: Days = Days.Monday;
```

In this TypeScript example, **`Days`** is an enum, and **`today`** can only be assigned values from the **`Days`** enum.

It's important to note that if you're working purely with JavaScript, you might use one of the simulation approaches mentioned earlier. If you're using TypeScript or planning to adopt it, enums are part of the language and provide more robust support for enumerations.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-are-javascript-accessors?"></a>

## 5. What are JavaScript accessors?

Accessors are special methods that allow you to get and set the values of an object's properties. Accessors are defined using the **`get`** and **`set`** keywords and are often used in conjunction with properties to control how values are retrieved and assigned.

There are two types of accessors in JavaScript:

1. **Getter:**

   A getter is a method that is used to retrieve the value of a property. It is defined using the **`get`** keyword followed by the property name. When you access the property, the getter function is invoked.

   ```javascript
   const person = {
     firstName: "John",
     lastName: "Doe",
     get fullName() {
       return `${this.firstName} ${this.lastName}`;
     },
   };

   console.log(person.fullName); // Calls the getter function and logs "John Doe"
   ```

2. **Setter:**

   A setter is a method that is used to set the value of a property. It is defined using the **`set`** keyword followed by the property name. When you assign a value to the property, the setter function is invoked.

   ```javascript
   const person = {
     firstName: "John",
     lastName: "Doe",
     set fullName(name) {
       const [first, last] = name.split(" ");
       this.firstName = first;
       this.lastName = last;
     },
   };

   person.fullName = "Jane Smith"; // Calls the setter function to set firstName and lastName
   console.log(person.firstName); // Logs "Jane"
   console.log(person.lastName); // Logs "Smith"
   ```

Accessors provide a way to encapsulate the logic associated with getting and setting property values. They allow you to perform custom actions or calculations when properties are accessed or modified.

It's important to note that a property cannot have both a getter and a setter with the same name. If you define a getter for a property, attempting to define a setter with the same name will result in an error, and vice versa.

Another interesting use of the accessors is you can access them without invoking them and this sometimes increase readability.

Look at this example:

```javascript
function robot() {
  return {
    name: "Jack",
    age: "infinite",
    speak() {
      return "hey you human";
    },
    get favColor() {
      return "green";
    },
  };
}

const robot_1 = robot();

robot_1.speak(); // "hey you human"
robot_1.favColor; // "green"
```

Accessors are commonly used in classes, objects, and other contexts where you want to control the behaviour of property access and assignment. They are especially useful when you need to perform additional actions beyond simple property retrieval or assignment.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-prototype-chain?"></a>

## 6. What is the prototype chain?

In JavaScript, the prototype chain is a mechanism that allows objects to inherit properties and methods from other objects through a prototype linkage. Each object in JavaScript has an associated prototype object, and this forms a chain of prototypes.

Here's how the prototype chain works:

1. **Prototype Object:**

   Every object in JavaScript has a prototype object, which is another object that the current object inherits properties and methods from.

2. **Object Creation:**

   Every object you create in JavaScript, whether it's created using object literals ({}), constructor functions, or ES6 classes, is an instance of Object. So these objects inherit properties and methods from their prototype, and ultimately, they inherit from Object.prototype.

   ```javascript
   const person = {
     name: "John",
     age: 30,
   };

   // The person object has Object.prototype as its prototype
   ```

3. **Accessing Properties and Methods:**

   When you try to access a property or method on an object, JavaScript first looks for that property/method on the object itself. If it doesn't find it, it looks at the object's prototype, and so on, forming a chain.

   ```javascript
   console.log(person.name); // Outputs: John
   console.log(person.toString()); // Outputs: [object Object]
   ```

4. **Prototype Chain:**
   If the property or method is not found in the immediate object, JavaScript looks up the prototype chain until it finds the property/method or reaches the end of the chain (where the prototype is **`null`**).
5. **`Object.prototype`:**

   At the top of the prototype chain is the built-in **`Object.prototype`** object. All objects in JavaScript inherit from this prototype, which provides a set of common methods like **`toString()`**, **`hasOwnProperty()`**, and others.

   ```javascript
   const obj = {};
   console.log(obj.toString()); // Outputs: [object Object]
   ```

6. **Custom Prototypes:**

   You can also create custom prototypes using constructor functions or the **`Object.create()`** method.

   ```javascript
   function Person(name, age) {
     this.name = name;
     this.age = age;
   }

   Person.prototype.sayHello = function () {
     console.log("Hello, my name is " + this.name);
   };

   const person = new Person("John", 30);
   person.sayHello(); // Outputs: Hello, my name is John
   ```

Understanding the prototype chain is crucial in JavaScript, especially when working with object-oriented programming and inheritance. It allows you to create a hierarchy of objects, promoting code reuse and providing a flexible way to structure your programs.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-pure-function?"></a>

## 7. What is a pure function?

A pure function is a function that, given the same input, will always produce the same output and has no observable side effects. The concept of a pure function is a fundamental concept in functional programming and has several characteristics:

1. **Deterministic:**

   A pure function should produce the same output for the same input every time it is called. The result is entirely determined by its input parameters, and there is no reliance on external state or randomness.

2. **No Side Effects:**

   A pure function should not cause any observable side effects, such as modifying external variables or data structures, performing I/O operations, or altering the state of the system in any way. It only computes a result based on its inputs.

3. **Referential Transparency:**

   If a function is pure, it is referentially transparent, meaning that its output can be replaced with its computed value without affecting the program's behavior. This property allows for easy reasoning about the code.

4. **Immutable Data:**

   Pure functions typically operate on immutable data. They do not modify the input parameters but instead return a new result based on the input. Immutability is often encouraged to prevent unintended side effects.

Here's an example of a pure function:

```javascript
// Pure function example
function add(a, b) {
  return a + b;
}

// Impure function with side effect (console.log)
function impureAdd(a, b) {
  console.log("Adding:", a, b);
  return a + b;
}
```

In the example above, **`add`** is a pure function because it takes two parameters and returns their sum without causing any side effects. On the other hand, **`impureAdd`** is not pure because it logs a message to the console, which is an observable side effect.

Pure functions are desirable in functional programming because they make code more predictable, testable, and maintainable. They can be easily reasoned about, and their properties contribute to the development of more reliable and scalable software.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-callback?"></a>

## 8. What is a callback?

A callback is a function that is passed as an argument to another function and is intended to be executed after the completion of some asynchronous operation or at a later point in time. Callbacks are a fundamental concept in JavaScript, especially in scenarios where you need to work with asynchronous code.

Here's a simple example to illustrate the concept of a callback:

```javascript
function doSomethingAsync(callback) {
  // Simulating an asynchronous operation, like fetching data from a server
  setTimeout(function () {
    console.log("Async operation completed");
    // Call the callback function
    callback();
  }, 1000);
}

// Define a callback function
function afterAsyncOperation() {
  console.log("Callback function executed");
}

// Call the function with the callback
doSomethingAsync(afterAsyncOperation);
```

In this example, **`doSomethingAsync`** is a function that simulates an asynchronous operation using **`setTimeout`**. It takes a callback function (**`afterAsyncOperation`**) as an argument. When the asynchronous operation is completed (after 1000 milliseconds in this case), the callback function is executed.

Callbacks are commonly used in JavaScript for handling asynchronous operations like fetching data from a server, reading files, or handling user input. They help in managing the flow of code and ensuring that certain actions are taken after an asynchronous task completes. However, as code grows in complexity, callback-based code can become hard to manage, leading to the development of other patterns like Promises and async/await in modern JavaScript.

### Is there another way to handle asynchronous operations?

Yes, promises. Let see some key advantage of promises over callbacks.

- **Callbacks**: Callbacks are functions that are passed as arguments to another function and are typically used to handle asynchronous operations. While they are functional, they can lead to a coding pattern known as "callback hell" or "Pyramid of Doom." This occurs when you have multiple nested callbacks, making the code difficult to read and maintain.

- **Promises**: Promises are a more modern approach to handling asynchronous operations in JavaScript. They provide a cleaner and more structured way to work with asynchronous code. A promise represents the eventual completion or failure of an asynchronous operation and allows you to attach callbacks to handle the success or failure of the operation.

Unlike the callbacks the promises are more powerful because they are **composable**.

- **Composable:** In the context of promises, "composable" means that promises can be easily combined and chained together. You can create sequences of asynchronous operations in a more readable and maintainable way. Each step in the sequence returns a new promise, allowing you to chain additional operations or handle errors more gracefully.

Here's a simple example to illustrate the composability of promises:

```javascript
// Using callbacks
function fetchData(callback) {
  setTimeout(function () {
    callback(null, "Data fetched");
  }, 1000);
}

function processData(data, callback) {
  setTimeout(function () {
    callback(null, "Processed data: " + data);
  }, 1000);
}

fetchData(function (err, result) {
  if (err) {
    console.error(err);
    return;
  }
  processData(result, function (err, finalResult) {
    if (err) {
      console.error(err);
      return;
    }
    console.log(finalResult);
  });
});

// Using promises
function fetchDataPromise() {
  return new Promise(function (resolve) {
    setTimeout(function () {
      resolve("Data fetched");
    }, 1000);
  });
}

function processDataPromise(data) {
  return new Promise(function (resolve) {
    setTimeout(function () {
      resolve("Processed data: " + data);
    }, 1000);
  });
}

fetchDataPromise()
  .then(processDataPromise)
  .then(function (finalResult) {
    console.log(finalResult);
  })
  .catch(function (err) {
    console.error(err);
  });
```

In the promises example, the **`fetchDataPromise`** and **`processDataPromise`** functions return promises, which can be easily chained using the **`.then`** method. This chaining of promises makes the code more readable and avoids the callback hell problem often associated with callbacks. This is why the sentence suggests that promises are more powerful because they are composable.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-promise?"></a>

## 9. What is a promise?

In JavaScript, a Promise is an object that represents the eventual completion or failure of an asynchronous operation and its resulting value. Promises provide a more structured and flexible way to work with asynchronous code compared to traditional callback functions. They are a core feature introduced in ECMAScript 6 (ES6) to address the "Callback Hell" problem and improve the readability and maintainability of asynchronous code.

A Promise can be in one of three states:

1. **Pending:**

   The initial state when the asynchronous operation is still ongoing and has not completed.

2. **Fulfilled (Resolved):**

   The state when the asynchronous operation has completed successfully, and the promise has a resulting value.

3. **Rejected:**

   The state when the asynchronous operation has encountered an error or failed, and the promise has a reason for the failure.

A Promise is typically created using the **`Promise`** constructor, which takes a function (often called an executor) with two arguments: **`resolve`** and **`reject`**. The **`resolve`** function is called when the asynchronous operation succeeds, and the **`reject`** function is called when it fails.

Here's a simple example of using a Promise:

```javascript
const myPromise = new Promise((resolve, reject) => {
  // Simulating an asynchronous operation (e.g., fetching data)
  setTimeout(() => {
    const success = true; // Change to false to simulate rejection
    if (success) {
      resolve("Operation completed successfully!");
    } else {
      reject("Operation failed!");
    }
  }, 2000); // Simulating a 2-second delay
});

// Handling the promise's resolution or rejection
myPromise
  .then((result) => {
    console.log("Success:", result);
  })
  .catch((error) => {
    console.error("Error:", error);
  });
```

In this example, **`myPromise`** is created, simulating an asynchronous operation with a delay of 2 seconds. The **`then`** method is used to handle the successful resolution of the promise, and the **`catch`** method is used to handle any rejection.

Promises provide a more readable and structured way to work with asynchronous code and avoid callback nesting. They also facilitate better error handling through the **`catch`** method and chaining of multiple asynchronous operations using **`then`**. Promises have become a fundamental building block for handling asynchronous operations in modern JavaScript, and they are commonly used in conjunction with other features like **`async/await`**.

<div align="right">

[back to Questions](#questions)

</div>

---

<!-- TODO: currying to add -->

<a name="what-is-a-closure?"></a>

## 10. What is a closure and what is currying?

### Closure

In JavaScript, a closure is a function or the ability of a function that retains access to variables from its outer (enclosing) scope even after the outer function has finished executing. So every function is a closure.

A closure is created, or better, activated when a function is defined within another function, and it "closes over" the outer function's variables, in fact it's important to clarify that not every function necessarily behaves like a closure in the sense of capturing and preserving its surrounding lexical scope.

Lexical scope in JavaScript refers to the scope of a variable being determined by its location within the source code. In other words, the scope of a variable is defined by where it is declared in the code. Also a function object needs not only the code inside but also it needs a reference to the lexical scope.

Here's a simple example to illustrate lexical scope:

```javascript
function outer() {
  let outerVariable = "I am in the outer function";

  function inner() {
    let innerVariable = "I am in the inner function";
    console.log(outerVariable); // Accessing outerVariable from the outer scope
  }

  inner();
}

outer();
```

In this example, **`outerVariable`** is declared in the **`outer`** function, and it is accessible both in the **`outer`** function and the **`inner`** function because of lexical scope.

The closure here is activated and allow function to "remember" the environment in which it was created.

So, to sum up, lexical scope in JavaScript determines the visibility and accessibility of variables based on their location in the source code. Closures, on the other hand, allow functions to retain access to variables from their outer scope even after the outer function has completed its execution. Closures are closely related to lexical scope because they rely on it to capture and remember the enclosing scope's variables.

Let's see a more useful example:

```javascript
function greetingLang(greeting) {
  return function (name) {
    return `${greeting} ${name}`;
  };
}

const greetingSpanish = greetingLang("Hola");
greetingSpanish("Alice"); // Hola Alice
```

In this case `greetingSpanish` is something it's possible to apply to all the names I want and the function will always remember the `greeting` value added. So even we are no longer in the scope of `greetingLang` which is already finished to run this is possible because JavaScript supports the concept of closures and `greetingSpanish` retains the values of that scope.
This feature is really useful because it allow us to break a big function in smaller functions applying them partially.

### Currying

Currying is the process of taking a multi-argument function and breaking it up into a series of single argument functions which successfully remember the outer scope. So it's possible to partially apply those arguments creating more reusable functions that I can use to create more complex program.

Based on the previous example which using currying, the example without using it is something like:

```javascript
function greet(greeting, name) {
  return `${greeting} ${name}`;
}
```

In this example if I want to greet more people with the same `Hola` I have to pass `Hola` every time.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-does-it-mean-that-javascript-has-first-class-functions?"></a>

## 11. What does it mean that JavaScript has First-class functions?

In programming language design, a language is said to have first-class functions if it treats functions as any other variable. This means that functions can be:

1. **Assigned to variables:**

   You can assign a function to a variable, making the function referenceable by that variable.

   ```javascript
   const myFunction = function () {
     console.log("Hello, world!");
   };
   ```

2. **Passed as arguments to other functions:**

   You can pass a function as an argument to another function.

   ```javascript
   function higherOrderFunction(callback) {
     callback();
   }

   higherOrderFunction(myFunction);
   ```

3. **Returned from other functions:**

   A function can return another function.

   ```javascript
   function createFunction() {
     return function () {
       console.log("I am a returned function!");
     };
   }

   const generatedFunction = createFunction();
   generatedFunction();
   ```

4. **Stored in data structures:**

   Functions can be stored in data structures, such as arrays or objects.

   ```javascript
   const functionArray = [myFunction, () => console.log("Another function")];
   functionArray[0](); // Calls myFunction
   functionArray[1](); // Calls the second function
   ```

The concept of first-class functions is a key feature of languages that support functional programming paradigms. JavaScript is an example of a language with first-class functions. This characteristic allows for more expressive and flexible programming styles, enabling the use of functions as modular units of behavior that can be manipulated and composed in different ways.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-higher-order-function?"></a>

## 12. What is a higher-order function?

A higher-order function is a concept in functional programming where functions can accept other functions as arguments and/or return functions as results. In other words, a higher-order function either takes one or more functions as arguments or returns a function as its result. This ability to treat functions as values allows for powerful and flexible programming paradigms, such as functional composition and abstraction.

Here are examples of higher-order functions:

1. **Functions that take functions as arguments:**

   ```javascript
   // Example 1: Array method - forEach
   const numbers = [1, 2, 3, 4, 5];

   numbers.forEach(function (element) {
     console.log(element);
   });

   // Example 2: Custom higher-order function
   function applyOperation(x, operation) {
     return operation(x);
   }

   function double(x) {
     return x * 2;
   }

   const result = applyOperation(5, double); // Passes the double function as an argument
   console.log(result); // Outputs: 10
   ```

2. **Functions that return functions:**

   ```javascript
   // Example 1: Function factory
   function multiplier(factor) {
     return function (x) {
       return x * factor;
     };
   }

   const double = multiplier(2);
   const triple = multiplier(3);

   console.log(double(5)); // Outputs: 10
   console.log(triple(5)); // Outputs: 15

   // Example 2: Higher-order function returning a function
   function createGreeter(greeting) {
     return function (name) {
       return `${greeting}, ${name}!`;
     };
   }

   const greetInEnglish = createGreeter("Hello");
   const greetInSpanish = createGreeter("Hola");

   console.log(greetInEnglish("John")); // Outputs: Hello, John!
   console.log(greetInSpanish("Juan")); // Outputs: Hola, Juan!
   ```

Higher-order functions are a fundamental concept in functional programming and are commonly used for abstraction, composition, and creating more reusable and expressive code. They are an integral part of languages like JavaScript, which supports functional programming features.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="are-concepts-of-higher-order-function-and-closure-connected?"></a>

## 13. Are concepts of higher-order function and closure connected?

Yes, in JavaScript, the concepts of higher-order functions and closures are closely connected and often go hand in hand.

**Higher-order functions:**

A higher-order function is a function that can take other functions as arguments or return them as results.
JavaScript supports higher-order functions, allowing functions to be treated as first-class citizens.

**Closures:**

A closure is created when a function is defined inside another function, allowing the inner function to access variables from the outer (enclosing) function's scope even after the outer function has finished executing.
Closures "close over" the variables they reference, preserving their values.
The connection between higher-order functions and closures is often seen when a function returns another function. The inner function forms a closure over the variables of the outer function, capturing the state of those variables. This enables the inner function to access and manipulate the variables even after the outer function has completed its execution.

Here's a simple example:

```javascript
function outerFunction(x) {
  // Inner function forms a closure over the 'x' parameter
  function innerFunction(y) {
    return x + y; // Inner function can access 'x' from the outer scope
  }

  return innerFunction;
}

const closureExample = outerFunction(10);
console.log(closureExample(5)); // Outputs 15
```

In this example, outerFunction returns innerFunction, and when you later invoke closureExample(5), it can still access the x value (which is 10) from the outer scope, demonstrating the concept of closures.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-difference-between-arrow-functions-and-the-regular-functions?"></a>

## 14. What is the difference between arrow functions and the regular functions?

Arrow functions differ from functions defined in other ways in one fundamental aspect: they inherit the value of the reserved word `this` from the scope in which they are defined, instead of defining their own calling context, as happens to functions defined in other ways.

Here are the key differences:

1. **Syntax:**

   **Function Declaration:**

   ```javascript
   function regularFunction(arg1, arg2) {
     // function body
   }
   ```

   **Function Expression:**

   ```javascript
   const regularFunction = function (arg1, arg2) {
     // function body
   };
   ```

   **Arrow Function:**

   ```javascript
   const arrowFunction = (arg1, arg2) => {
     // function body
   };
   ```

2. **`this` Binding:**
   - **Function:**
     Regular functions have their own **`this`** context, which is dynamically scoped based on how the function is called. The value of **`this`** depends on how the function is invoked.
   - **Arrow Function:**
     Arrow functions do not have their own **`this`** context. They inherit the **`this`** value from the enclosing scope, which makes them lexically scoped.
3. **Arguments Object:**
   - **Function:**
     Regular functions have their own **`arguments`** object, which is an array-like object containing all the arguments passed to the function.
   - **Arrow Function:**
     Arrow functions do not have their own **`arguments`** object. Instead, they inherit the **`arguments`** object from the enclosing scope.
4. **Use of `new`:**
   - **Function:**
     Regular functions can be used as constructor functions with the **`new`** keyword to create instances of objects.
   - **Arrow Function:**
     Arrow functions cannot be used as constructor functions. They do not have their own **`this`**, and using **`new`** with an arrow function will result in a runtime error.
5. **Binding of `this` in Methods:**
   **Function:**
   In regular functions used as methods (i.e., as properties of objects), the value of **`this`** is dynamically bound to the object on which the method is called.
   **Arrow Function:**
   Arrow functions do not have their own **`this`**, so they don't create a new **`this`** context. If used as methods, they inherit the **`this`** value from the enclosing scope, often resulting in unexpected behavior.

Here are examples illustrating some of these differences:

```javascript
// Regular Function
function regularFunction() {
  console.log(this); // refers to the calling context
}

// Arrow Function
const arrowFunction = () => {
  console.log(this); // inherits the this value from the enclosing scope
};

const obj = {
  regularMethod: function () {
    console.log(this); // refers to the object (obj) when called as a method
  },
  arrowMethod: () => {
    console.log(this); // inherits the this value from the enclosing scope (not obj)
  },
};

regularFunction(); // this refers to the global object (or undefined in strict mode)
arrowFunction(); // this inherits from the enclosing scope

obj.regularMethod(); // this refers to the obj
obj.arrowMethod(); // this inherits from the enclosing scope (not obj)
```

In summary, the choice between regular functions and arrow functions depends on the specific requirements of your code, especially regarding the handling of **`this`** and other functional aspects. Arrow functions are concise and convenient for certain scenarios, while regular functions offer more flexibility in terms of **`this`** binding and can be used as constructors.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-difference-between-call,-apply-and-bind?"></a>

## 15. What is the difference between call, apply and bind?

**`call`**, **`apply`**, and **`bind`** are methods in JavaScript that are used to manipulate the **`this`** value inside a function and, in the case of **`call`** and **`apply`**, to invoke functions. Here's a brief explanation of each:

1. **`call` method:**

   The **`call`** method is used to invoke a function with a specified **`this`** value and individual arguments passed explicitly.

   ```javascript
   function sayHello() {
     console.log("Hello, " + this.name);
   }

   const person = { name: "John" };
   sayHello.call(person); // Outputs: Hello, John
   ```

2. **`apply` method:**

   The **`apply`** method is similar to **`call`**, but it accepts arguments as an array or an array-like object.

   ```javascript
   function sayHello(greeting) {
     console.log(greeting + ", " + this.name);
   }

   const person = { name: "John" };
   sayHello.apply(person, ["Good morning"]); // Outputs: Good morning, John
   ```

3. **`bind` method:**

   The **`bind`** method creates a new function with a specified **`this`** value and initial arguments. However, it doesn't invoke the function immediately; instead, it returns a new function that can be called later.

   ```javascript
   function sayHello() {
     console.log("Hello, " + this.name);
   }

   const person = { name: "John" };
   const sayHelloToJohn = sayHello.bind(person);
   sayHelloToJohn(); // Outputs: Hello, John
   ```

   **`bind`** is often used when you want to create a function with a fixed **`this`** value that can be called later, especially in event handlers or when passing functions as callbacks.

In summary:

- **`call` and `apply`** are used to invoke a function immediately, with **`call`** accepting individual arguments, and **`apply`** accepting arguments as an array.
- **`bind`** is used to create a new function with a specified **`this`** value, without invoking it immediately.

These methods are particularly useful in scenarios where you want to control the context (**`this`** value) of a function or when working with functions that expect different argument types.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-proxy-and-what-are-some-practical-uses?"></a>

## 16. What is a proxy and what are some practical uses?

A **`Proxy`** is an object that serves as an intermediary or wrapper for another object: the target. It allows you to intercept and customize fundamental operations for the target object, such as reading properties, writing properties, and executing functions.
Proxies provide a powerful mechanism for creating flexible and transparent abstractions over objects.

The `Proxy` object allows you to create an object that can be used in place of the original object, but which may redefine fundamental `Object` operations like getting, setting, and defining properties. Proxy objects are commonly used to log property accesses, validate, format, or sanitize inputs, and so on.

You create a `Proxy` with two parameters:

- `target`: the original object which you want to proxy
- `handler`: an object that defines which operations will be intercepted and how to redefine intercepted operations.

For example, this code creates a proxy for the `target` object.

```javascript
const target = {
  message1: "hello",
  message2: "everyone",
};

const handler1 = {};

const proxy1 = new Proxy(target, handler1);
```

Because the handler is empty, this proxy behaves just like the original target:

```javascript
console.log(proxy1.message1); // hello
console.log(proxy1.message2); // everyone
```

To customize the proxy, we define functions on the handler object:

```javascript
const target = {
  message1: "hello",
  message2: "everyone",
};

const handler2 = {
  get(target, prop) {
    if (prop === "message1") {
      return "world";
    }
    // For other properties, return the original target value
    return target[prop];
  },
};

const proxy2 = new Proxy(target, handler2);

console.log(proxy2.message1); // Output: "world"
console.log(proxy2.message2); // Output: "everyone"
```

### Common use cases of Proxies

1. **Object Virtualization:** Proxies can be used to create virtual objects that don't necessarily exist in memory, allowing you to handle property access dynamically.
2. **Validation and Security:** Proxies enable you to validate or restrict certain operations on objects, enhancing security by controlling access to sensitive data or operations.
3. **Logging and Profiling:** You can use proxies to log or profile object interactions, gaining insights into how your code is working or identifying performance bottlenecks.
4. **Reactive Programming:** Proxies can be leveraged in reactive programming to build systems where changes to one part of the application automatically trigger updates in other parts.

In summary, proxies are valuable when you need fine-grained control over object interactions, dynamic behavior, or additional features that traditional object manipulation doesn't provide.

While proxies offer powerful capabilities, it's important to use them judiciously, as they introduce additional complexity and can impact performance.

### Practical usage: using a proxy for validation

This is a simple example of using a proxy for validation. Imagine you want to ensure that the values stored in an object's properties are always numbers. You can use a proxy to intercept property assignments and validate the values:

```javascript
// Create an object with a proxy
const numberValidator = new Proxy(
  {},
  {
    set: function (target, key, value) {
      // Check if the assigned value is a number
      if (typeof value !== "number") {
        console.error(`Error: ${key} must be a number`);
        return false; // Prevent the assignment
      }

      // If it's a number, set the value in the object
      target[key] = value;
      return true; // Allow the assignment
    },
  }
);

// Use the proxy object
numberValidator.age = 25; // Valid
numberValidator.salary = "50000"; // Error: salary must be a number
```

In this example, the proxy intercepts the **`set`** operation and checks if the assigned value is a number. If not, it logs an error and prevents the assignment. This way, you can enforce specific rules or validations when interacting with objects.

### Practical usage: creating a store

it's possible to create a store-like object using a **`Proxy`** in JavaScript. A store is a common pattern used in state management for applications. The **`Proxy`** object can be used to intercept and customize operations on the store, allowing you to implement features like getter/setter methods, validation, logging, and more.

Here's a simple example of creating a basic store with a **`Proxy`**:

```javascript
// Define initial store data
const initialStoreData = {
  counter: 0,
  message: "Hello, world!",
};

// Create a handler for the proxy
const storeHandler = {
  get(target, prop, receiver) {
    // You can add custom logic for getting properties here
    console.log(`Getting ${prop}`);
    return target[prop];
  },
  set(target, prop, value, receiver) {
    // You can add custom logic for setting properties here
    console.log(`Setting ${prop} to ${value}`);
    target[prop] = value;
    // Trigger a custom event or update the UI, etc., as needed
    return true; // Indicates success
  },
};

// Create a proxy for the store
const store = new Proxy(initialStoreData, storeHandler);

// Usage
console.log(store.counter); // Output: "Getting counter" and the initial value
console.log(store.message); // Output: "Getting message" and the initial value

store.counter = 42; // Output: "Setting counter to 42"
console.log(store.counter); // Output: "Getting counter" and the updated value
```

In this example, the **`storeHandler`** object defines two traps: **`get`** and **`set`**. The **`get`** trap is triggered when accessing properties, and the **`set`** trap is triggered when setting properties. You can customize these traps to implement specific behavior for your store, such as validation, logging, triggering events, or updating the UI.

Keep in mind that this is a basic example, and in a real-world application, you might want to add more sophisticated features and consider additional aspects like immutability, asynchronous actions, and state listeners.

### Practical usage: when using a proxy is the most suitable choice

Let's consider a scenario where you want to implement a mechanism to track changes made to an object dynamically. In this case, using a proxy is more suitable than traditional approaches because it allows you to intercept property changes easily.

```javascript
// Function to create a tracked object with a proxy
function createTrackedObject(initialObject, onChange) {
  return new Proxy(initialObject, {
    set: function (target, key, value) {
      // Update the original object
      target[key] = value;

      // Notify the change to a callback function
      onChange(key, value);

      return true; // Allow the assignment
    },
  });
}

// Example usage
const trackedPerson = createTrackedObject(
  { name: "John", age: 30 },
  (key, value) => console.log(`Property '${key}' changed to '${value}'`)
);

trackedPerson.age = 31; // Logs: Property 'age' changed to '31'
```

In this example, the **`createTrackedObject`** function uses a proxy to intercept property assignments and notify a callback function (**`onChange`**) whenever a change occurs. Achieving the same functionality without a proxy would require manually updating the object and triggering notifications each time a property is modified, which can be error-prone and harder to maintain. Proxies provide a cleaner and more efficient solution for such dynamic behavior.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="#what-is-the-event-flow-and-what-are-its-phases?"></a>

## 17. What is the event flow and what are its phases?

In JavaScript, the event flow refers to the order in which events are processed in the Document Object Model (DOM) hierarchy. The DOM is a tree-like structure that represents the elements on a web page, and events are interactions or occurrences that happen in the browser, such as user actions or changes to the document.

### **Event phases:**

1. **Capturing Phase:**

   - In the capturing phase, the browser starts from the root of the DOM and traverses down to the target element.
   - Event listeners with the capture option set to **`true`** will be triggered during this phase.
   - To add an event listener with capturing, you can pass **`true`** as the third parameter in **`addEventListener`**:

     ```javascript
     element.addEventListener("click", handlerFunction, true);
     ```

2. **Target Phase:**

   - Once the capturing phase reaches the target element, the event enters the target phase.
   - Event listeners without a specified phase or with the capture option set to **`false`** will be triggered during this phase.
   - You can omit the third parameter or pass **`false`** for the bubbling phase:

     ```javascript
     element.addEventListener("click", handlerFunction);
     // or
     element.addEventListener("click", handlerFunction, false);
     ```

3. **Bubbling Phase:**

   - After the target phase, the event begins to bubble up from the target element to the root of the DOM.
   - Event listeners with the capture option set to **`false`** will be triggered during this phase.
   - You can explicitly specify the bubbling phase:

     ```javascript
     element.addEventListener("click", handlerFunction, false);
     ```

During capturing and bubbling phases, event handlers (functions associated with the event) can be executed. The default behavior is to follow the event flow from capturing to bubbling, but event propagation can be stopped at any point using methods like `event.stopPropagation()`.

### **Event Listener Options:**

When adding an event listener, you can provide an options object as the third parameter. Here are some common options:

- **capture (boolean):** Specifies whether the listener should be triggered during the capturing phase. Default is **`false`** (bubbling phase).

  ```javascript
  element.addEventListener("click", handlerFunction, { capture: true });
  ```

- **once (boolean):** If **`true`**, the listener will be automatically removed after being invoked once.

  ```javascript
  element.addEventListener("click", handlerFunction, { once: true });
  ```

- **passive (boolean):** If **`true`**, indicates that the listener will not call **`preventDefault()`**. This can be used for performance optimization.

  ```javascript
  element.addEventListener("touchstart", handlerFunction, { passive: true });
  ```

Putting it all together, here's an example that adds an event listener with capturing, once, and passive options:

```javascript
element.addEventListener("click", handlerFunction, {
  capture: true,
  once: true,
  passive: true,
});
```

This event listener will be triggered during the capturing phase, execute only once, and not prevent the default action.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what's-the-difference-between-event-propagation-and-event-bubbling?"></a>

## 18. What's the difference between event propagation and event bubbling?

Event propagation and event bubbling are two phases of the event flow in the DOM (Document Object Model). Understanding these concepts is crucial for handling events effectively in a web application.

**Event Propagation:**

- Definition: Event propagation refers to the process of an event being propagated from the target element to the root of the DOM or vice versa.
- Two Phases: There are two phases of event propagation:
  - Capturing Phase: The event travels down from the root of the DOM hierarchy to the target element.
  - Bubbling Phase: The event travels back up from the target element to the root.
- Methods: You can use the addEventListener method with the third parameter set to true to register an event listener during the capturing phase.

```javascript
element.addEventListener("click", myFunction, true); // true for capturing phase
```

**Event Bubbling:**

- Definition: Event bubbling is a specific type of event propagation where the event starts from the target element and bubbles up to the root of the DOM.
- Default Behavior: By default, most events in the DOM follow the bubbling phase.
- Methods: You can use the addEventListener method without specifying the third parameter or with false to register an event listener during the bubbling phase (which is the default).

```javascript
element.addEventListener("click", myFunction); // equivalent to bubbling phase
```

Example:

```html
<div id="outer">
  <div id="middle">
    <div id="inner">Click me!</div>
  </div>
</div>
```

```javascript
document.getElementById("outer").addEventListener(
  "click",
  function () {
    console.log("Outer div clicked!");
  },
  true
);

document.getElementById("middle").addEventListener(
  "click",
  function () {
    console.log("Middle div clicked!");
  },
  true
);

document.getElementById("inner").addEventListener(
  "click",
  function () {
    console.log("Inner div clicked!");
  },
  true
);
```

In this example, if you click the "Inner div," the output will be:

```bash
Inner div clicked!
Middle div clicked!
Outer div clicked!
```

This demonstrates the capturing phase, where the event starts from the root and goes down to the target element.

If you were using the default behavior (without specifying the third parameter or with false), it would follow the bubbling phase, going from the target element up to the root.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-an-event-loop?"></a>

## 19. What is an event loop?

The event loop is a fundamental concept in asynchronous programming, particularly in the context of JavaScript and web development. It is the mechanism that allows JavaScript to handle asynchronous operations, such as user input, network requests, and timers, in a non-blocking way.

Here's a high-level overview of how the event loop works:

1. **Call Stack:**
   - JavaScript is single-threaded, meaning it has one call stack, which is a data structure that keeps track of the function calls in your code. When you execute a function, it gets added to the top of the call stack.
2. **Callback Queue:**
   - In addition to the call stack, there is a callback queue that holds tasks to be executed. These tasks include events like user clicks, HTTP responses, or timer completions.
3. **Event Loop:**

   - The event loop is a continuous process that constantly checks two things:
     - Is the call stack empty? If it is, it takes the first task from the callback queue and pushes it onto the call stack.
     - Is there any synchronous code to execute? If so, it executes that code.

This process ensures that asynchronous tasks are handled when the call stack is empty, preventing the program from blocking while waiting for asynchronous operations to complete.

Here's a simplified example:

```javascript
console.log("Start");

setTimeout(function () {
  console.log("Timeout callback");
}, 2000);

console.log("End");
```

In this example, the output will be:

```sql
Start
End
Timeout callback

```

Here's how it works:

1. **`console.log('Start')`** is added to the call stack and executed.
2. **`setTimeout`** is encountered. It schedules the callback to be executed after 2000 milliseconds but doesn't block the execution of the next line of code.
3. **`console.log('End')`** is added to the call stack and executed.
4. The event loop detects that the call stack is empty, so it checks the callback queue and finds the **`setTimeout`** callback. It is then added to the call stack and executed.

This way, the program doesn't wait for the timer to complete before moving on to the next line of code, demonstrating the non-blocking nature of the event loop in handling asynchronous tasks.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-customevent-and-what-is-the-dispatchevent()-method?"></a>

## 20. What is a CustomEvent and what is the dispatchEvent() method?

The `CustomEvent` interface represents events initialized by an application for any purpose.
The `CustomEvent()` constructor creates a new `CustomEvent` object.
Events in the DOM are a way for different parts of a web page to communicate with each other. The DOM provides a set of predefined events like click, mouseover, etc. However, sometimes you may need to create custom events to handle specific scenarios in your application.

After creating a custom event you can then use the `dispatchEvent` method to dispatch the custom event on a DOM element. Event listeners can be set up to handle this custom event, allowing different parts of your application to react to it. When the custom event is dispatched, the associated event listener will be called, and you can access the additional data, if present, in it.

Let see the structure:

```javascript
new CustomEvent(type);
new CustomEvent(type, options);
```

`type`
A string providing the name of the event. Event names are case-sensitive.

`options` Optional
An object that, in addition of the properties defined in `Event()`, can have the following properties:

`detail` Optional
An event-dependent value associated with the event. This value is then available to the handler using the `CustomEvent.detail` property. It defaults to null.

The `dispatchEvent()` method of the `EventTarget` sends an Event to the object, (synchronously) invoking the affected event listeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with `dispatchEvent()`.

Calling `dispatchEvent()` is the last step to firing an event. The event should have already been created and initialized using an `Event()` constructor.
Unlike "native" events, which are fired by the browser and invoke event handlers asynchronously via the event loop, `dispatchEvent()` invokes event handlers synchronously. All applicable event handlers are called and return before `dispatchEvent()` returns.

### Practical case: Event bubbling

It is often desirable to trigger an event from a child element, and have an ancestor catches it, optionally, with data:

```html
<form>
  <textarea></textarea>
</form>
```

```javascript
const form = document.querySelector("form");
const textarea = document.querySelector("textarea");

// Create a new event, allow bubbling, and provide any data you want to pass to the "detail" property
const eventAwesome = new CustomEvent("awesome", {
  bubbles: true,
  detail: { text: () => textarea.value },
});

// The form element listens for the custom "awesome" event and then consoles the output of the passed text() method
form.addEventListener("awesome", (e) => console.log(e.detail.text()));

// As the user types, the textarea inside the form dispatches/triggers the event to fire, and uses itself as the starting point
textarea.addEventListener("input", (e) => e.target.dispatchEvent(eventAwesome));
```

### Practical example: communication between components

Imagine you have a component-based architecture in your web application. You have a button component that, when clicked, triggers some action, and you want other components to be aware of this action. Instead of tightly coupling these components, you can use custom events for communication.

Let's consider a practical example where dispatching a custom event is a suitable choice.

```html
<button id="myButton">Click me</button>
<div id="output"></div>
```

```javascript
// Button component
const button = document.getElementById("myButton");

button.addEventListener("click", function () {
  // When the button is clicked, dispatch a custom event
  const customEvent = new CustomEvent("buttonClicked", {
    bubbles: true,
    detail: { message: "Button clicked!" },
  });

  button.dispatchEvent(customEvent);
});

// Output component
const output = document.getElementById("output");

// Listen for the custom event
document.addEventListener("buttonClicked", function (event) {
  // Update the output when the button is clicked
  output.textContent = event.detail.message;
});
```

In this example, when the button is clicked, a custom event (buttonClicked) is dispatched with some additional data (a message). The output component listens for this custom event and updates its content accordingly. This way, the button component and the output component are loosely coupled, and you can easily change or extend their behavior without directly modifying each other.

This pattern is particularly useful in larger applications where different components need to communicate without being tightly coupled. Custom events provide a flexible and decoupled way for components to interact.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-are-the-possible-ways-to-create-objects-in-javascript?"></a>

## 21. What are the possible ways to create objects in JavaScript

In JavaScript, there are several ways to create objects. Here are some of the common approaches:

1. **Object Literal:**
   The simplest way to create an object is using an object literal.

   ```javascript
   const person = {
     name: "John",
     age: 30,
     gender: "male",
   };
   ```

1. **Object Constructor:**
   You can use a constructor function with the **`new`** keyword to create objects.

   ```javascript
   function Person(name, age, gender) {
     this.name = name;
     this.age = age;
     this.gender = gender;
   }

   const person = new Person("John", 30, "male");
   ```

1. **Class Syntax (ES6 and later):**
   With the introduction of classes in ECMAScript 2015 (ES6), you can use the class syntax to create objects. This is syntactic sugar for Object constructor.

   ```javascript
   class Person {
     constructor(name, age, gender) {
       this.name = name;
       this.age = age;
       this.gender = gender;
     }
   }

   const person = new Person("John", 30, "male");
   ```

1. **Object.create():**
   The **`Object.create()`** method allows you to create a new object with the specified prototype object.

   ```javascript
   const personPrototype = {
     greet: function () {
       console.log("Hello!");
     },
   };

   const person = Object.create(personPrototype);
   person.name = "John";
   person.age = 30;
   person.greet(); // "Hello!"
   ```

1. **Factory Functions:**

   You can create objects using factory functions, which are functions that return new objects.

   ```javascript
   function createPerson(name, age, gender) {
     return {
       name: name,
       age: age,
       gender: gender,
     };
   }

   const person = createPerson("John", 30, "male");
   ```

1. **Singleton Pattern:**

   You can use the Singleton pattern to ensure a class has only one instance.

   ```javascript
   const singleton = {
     instance: null,
     getInstance: function () {
       if (!this.instance) {
         this.instance = {
           /* object properties */
         };
       }
       return this.instance;
     },
   };

   const object = singleton.getInstance();
   ```

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-difference-between-object-and-map?"></a>

## 22. What is the difference between Object and Map?

Both objects and maps in JavaScript are used to store key-value pairs, but they have some differences in terms of their use cases, behavior, and features. Here are the key differences between objects and maps:

1. **Key Type:**

   - **Objects:** The keys in objects are always strings or symbols. If you use a non-string or non-symbol key, it will be implicitly converted to a string.

     ```javascript
     const obj = {};
     const key = 42;

     obj[key] = "value";
     console.log(obj); // { "42": "value" }
     ```

   - **Maps:** The keys in maps can be of any data type, including primitive values, objects, and functions.

     ```javascript
     const map = new Map();
     const key = {};

     map.set(key, "value");
     console.log(map.get(key)); // "value"
     ```

2. **Key Order:**
   - **Objects:** The order of keys in objects is not guaranteed. The iteration order may vary across different JavaScript engines.
   - **Maps:** The order of keys in maps is guaranteed to be the order in which they were added. Iterating over a map will always produce the key-value pairs in the order they were inserted.
3. **Size Property:**

   - **Objects:** To get the number of properties in an object, you need to manually track the count.

     ```javascript
     const obj = { a: 1, b: 2, c: 3 };
     const size = Object.keys(obj).length; // size: 3
     ```

   - **Maps:** Maps have a **`size`** property that directly gives you the number of key-value pairs in the map.

     ```javascript
     const map = new Map();
     map.set("a", 1);
     map.set("b", 2);
     map.set("c", 3);
     const size = map.size; // size: 3
     ```

4. **Iteration:**

   - **Objects:** Iterating over the keys of an object can be achieved using **`for...in`** or **`Object.keys()`**.

     ```javascript
     const obj = { a: 1, b: 2, c: 3 };
     for (const key in obj) {
       console.log(key, obj[key]);
     }
     ```

   - **Maps:** Maps provide dedicated methods for iteration, such as **`forEach`**, **`entries`**, **`keys`**, and **`values`**.

     ```javascript
     const map = new Map();
     map.set("a", 1);
     map.set("b", 2);
     map.set("c", 3);

     map.forEach((value, key) => {
       console.log(key, value);
     });
     ```

5. **Inheritance:**
   - **Objects:** Objects have a prototype chain, which means they inherit properties from the **`Object.prototype`**. This can lead to unintentional name clashes if not used carefully.
   - **Maps:** Maps do not have a prototype chain, making them more straightforward and avoiding unintentional clashes.
6. **Performance:**
   - **Objects:** Objects may have a slight performance advantage for small and simple key-value pairs. However, the performance difference is often negligible.
   - **Maps:** Maps are designed to handle scenarios where keys can be of any data type and offer more features, making them suitable for a wider range of use cases.

In general, if you need simple key-value pairs and the keys are strings or symbols, objects are sufficient. If you need more flexibility in terms of key types, order, and built-in methods for manipulation, maps are a better choice. The choice between objects and maps depends on the specific requirements of your use case.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-are-the-mutable-and-immutable-array's-methods?"></a>

## 23. What are the mutable and immutable array's methods?

In JavaScript, arrays are mutable, meaning you can modify their contents by adding or removing elements, or by changing the values of existing elements. However, certain methods operate on arrays without modifying the original array and instead return a new array or a new value. These methods are associated with immutability. Let's categorize some common array methods:

**Mutable Array Methods:**

1. **Adding Elements:**

   - **`push()`**: Adds one or more elements to the end of an array.
   - **`unshift()`**: Adds one or more elements to the beginning of an array.

   ```javascript
   const fruits = ["apple", "banana"];
   fruits.push("orange"); // fruits: ['apple', 'banana', 'orange']
   fruits.unshift("grape"); // fruits: ['grape', 'apple', 'banana', 'orange']
   ```

2. **Removing Elements:**

   - **`pop()`**: Removes the last element from an array.
   - **`shift()`**: Removes the first element from an array.
   - **`splice()`**: Changes the contents of an array by removing or replacing existing elements and/or adding new elements.

   ```javascript
   const fruits = ["grape", "apple", "banana", "orange"];
   fruits.pop(); // fruits: ['grape', 'apple', 'banana']
   fruits.shift(); // fruits: ['apple', 'banana']
   fruits.splice(1, 1); // fruits: ['apple']
   ```

3. **Changing Elements:**

   - Directly modifying array elements.

   ```javascript
   const fruits = ["apple", "banana", "orange"];
   fruits[1] = "cherry"; // fruits: ['apple', 'cherry', 'orange']
   ```

**Immutable Array Methods:**

1. **Creating a New Array:**

   - **`concat()`**: Combines two or more arrays, returning a new array without modifying the existing ones.
   - **`slice()`**: Returns a shallow copy of a portion of an array into a new array.

   ```javascript
   const fruits = ["apple", "banana"];
   const moreFruits = fruits.concat("orange"); // moreFruits: ['apple', 'banana', 'orange']
   const slicedFruits = fruits.slice(0, 1); // slicedFruits: ['apple']
   ```

2. **Transforming Elements:**

   - **`map()`**: Creates a new array with the results of calling a provided function on every element in the array.
   - **`filter()`**: Creates a new array with all elements that pass the test implemented by the provided function.

   ```javascript
   const numbers = [1, 2, 3, 4, 5];
   const doubled = numbers.map(function (num) {
     return num * 2;
   }); // doubled: [2, 4, 6, 8, 10]

   const evens = numbers.filter(function (num) {
     return num % 2 === 0;
   }); // evens: [2, 4]
   ```

3. **Reducing:**

   - **`reduce()`**: Applies a function against an accumulator and each element in the array (from left to right) to reduce it to a single value.

   ```javascript
   const numbers = [1, 2, 3, 4, 5];
   const sum = numbers.reduce(function (acc, num) {
     return acc + num;
   }, 0); // sum: 15
   ```

These methods can be useful in situations where immutability is preferred, especially in functional programming paradigms or when working with state management libraries like Redux. They don't modify the original array but instead create a new one.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-does-array-like-mean?"></a>

## 24. What does array-like mean?

An "array-like" object in JavaScript refers to an object that has some characteristics of arrays, such as having indexed elements and a **`length`** property, but it may not necessarily be a true instance of the **`Array`** type. Array-like objects have properties and methods similar to arrays, allowing them to be treated like arrays in certain situations.

Characteristics of array-like objects include:

1. **Indexed Elements:**
   Array-like objects have elements that are accessed using numerical indices, just like arrays.
2. **`length` Property:**
   Array-like objects have a **`length`** property that indicates the number of elements in the collection.
3. **Presence of Numerical Indices:**
   They typically have numeric indices, starting from 0, but they may also have additional non-numeric properties.
4. **No Array Methods:**
   While they have numeric indices and a **`length`** property, array-like objects may not have the full set of array methods (e.g., **`push`**, **`pop`**, **`slice`**) that are available on true arrays.

Examples of array-like objects include:

- **Arguments Object:**

  ```javascript
  function exampleFunction() {
    console.log(arguments); // Arguments object is array-like
  }

  exampleFunction(1, 2, 3);
  ```

- **DOM NodeList:**

  ```javascript
  const elements = document.querySelectorAll("p"); // NodeList is array-like
  ```

- **String:**

  ```javascript
  const myString = "Hello"; // Strings are array-like
  ```

While array-like objects share some similarities with arrays, they lack the full functionality and methods provided by true arrays. To convert an array-like object to a real array, you can use methods like **`Array.from()`** or the spread operator (**`[...arrayLike]`**).

```javascript
const arrayLike = { 0: "a", 1: "b", 2: "c", length: 3 };

const realArray = Array.from(arrayLike);
// or
const realArraySpread = [...arrayLike];

console.log(realArray); // ['a', 'b', 'c']
console.log(realArraySpread); // ['a', 'b', 'c']
```

In summary, "array-like" refers to objects that resemble arrays in terms of having indexed elements and a **`length`** property but may not have all the methods and features of true arrays.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-difference-between-for...of-and-for...in-loop?"></a>

## 25. What is the difference between for...of and for...in loop?

The **`for...of`** and **`for...in`** loops in JavaScript are both used for iteration, but they have different use cases and behaviors.
Here are the key differences between the two:

### **`for...of` Loop:**

1. **Use Case:**
   The **`for...of`** loop is specifically designed for iterating over iterable objects, such as arrays, strings, sets, maps, etc. It iterates over the values of the iterable.
2. **Iteration Order:**
   It iterates over the elements of the iterable in the order they appear.
3. **Properties and Methods:**
   It only iterates over the values and does not include non-numeric properties or methods of the object.
4. **Example:**

   ```javascript
   const iterableArray = [1, 2, 3];

   for (const value of iterableArray) {
     console.log(value);
   }
   ```

### **`for...in` Loop:**

1. **Use Case:**
   The **`for...in`** loop is used to iterate over the enumerable properties of an object. While it can be used for arrays, it's generally not recommended due to potential issues with inherited properties.
2. **Iteration Order:**
   It iterates over the enumerable properties of an object in an arbitrary order. It's not guaranteed to iterate in the order properties were defined.
3. **Properties and Methods:**
   It iterates over all enumerable properties, including both numeric indices and other properties/methods. This includes inherited properties, which can be a source of unexpected behavior.
4. **Example:**

   ```javascript
   const myObject = { a: 1, b: 2, c: 3 };

   for (const key in myObject) {
     console.log(key, myObject[key]);
   }
   ```

### **Summary:**

- Use **`for...of`** when you specifically want to iterate over the values of an iterable object, and you're not concerned about non-numeric properties or inherited properties.
- Use **`for...in`** when you want to iterate over the properties of an object (including inherited ones), but be cautious about using it with arrays due to potential issues with iteration order and inherited properties.

In modern JavaScript, **`for...of`** is generally preferred for iterating over iterable objects, and **`for...in`** is often used in situations where you need to iterate over an object's properties. It's important to choose the loop that best fits the use case to avoid unexpected behavior.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-are-asynchronous-operations?"></a>

## 26. What are asynchronous operations?

Asynchronous operations allow code to execute independently of the main program flow, meaning that the program can continue to run while waiting for certain operations to complete. Asynchronous operations are crucial for tasks that involve waiting for external resources like network requests, file I/O, or timers.

JavaScript is inherently single-threaded, meaning it can only execute one piece of code at a time in a single thread. Asynchronous operations enable non-blocking behavior, allowing the program to initiate tasks and continue with other operations while waiting for the completion of those tasks.

There are several mechanisms for handling asynchronous operations in JavaScript:

1. **Callbacks**: Traditionally, asynchronous operations were managed using callbacks, which are functions passed as arguments to other functions. Callbacks are executed once the asynchronous operation completes.

   ```javascript
   setTimeout(() => {
     console.log("Async operation completed.");
   }, 1000);
   ```

2. **Promises**: Promises provide a cleaner and more structured way to handle asynchronous operations and their results. A promise represents a value that might be available now, in the future, or never.

   ```javascript
   const promise = new Promise((resolve, reject) => {
     setTimeout(() => {
       resolve("Async operation completed.");
     }, 1000);
   });

   promise.then((result) => {
     console.log(result);
   });
   ```

3. **Async/Await**: Introduced in ECMAScript 2017 (ES8), async functions and the await keyword provide a more synchronous-like syntax for working with promises, making asynchronous code easier to read and write.

   ```javascript
   async function myAsyncFunction() {
     const result = await someAsyncOperation();
     console.log(result);
   }

   myAsyncFunction();
   ```

Asynchronous operations are essential for building responsive and efficient JavaScript applications, especially in scenarios where tasks involve I/O operations or interactions with external services. By using asynchronous patterns effectively, JavaScript programs can handle multiple tasks concurrently without blocking the main thread, ensuring smooth user experiences and better performance.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-are-async-and-await?"></a>

## 27. What are async and await?

In JavaScript, **`async`** and **`await`** are features introduced in ECMAScript 2017 (ES8) that provide a more concise and readable syntax for writing asynchronous code, particularly code that relies on promises.

The **`async`** keyword is used to define an asynchronous function. An asynchronous function returns a promise implicitly, allowing you to use **`await`** within it. An async function can contain zero or more **`await`** expressions.

The **`await`** keyword can only be used within an **`async`** function. It pauses the execution of the **`async`** function until the promise is resolved. It effectively waits for the promise to resolve, and then it returns the resolved value.

Here's a simple example to illustrate how **`async`** and **`await`** work:

```javascript
function resolveAfter2Seconds() {
  return new Promise((resolve) => {
    setTimeout(() => {
      resolve("resolved");
    }, 2000);
  });
}

async function asyncCall() {
  console.log("Calling async function...");
  const result = await resolveAfter2Seconds();
  console.log(result);
}

asyncCall();
```

In this example:

- The **`resolveAfter2Seconds`** function returns a promise that resolves after 2 seconds.
- The **`asyncCall`** function is defined as an **`async`** function.
- Inside **`asyncCall`**, **`await`** is used to pause the execution until the promise returned by **`resolveAfter2Seconds`** is resolved.
- While waiting for the promise to resolve, other code outside the **`await`** expression can continue to execute.
- Once the promise is resolved, the execution resumes, and the resolved value is assigned to the **`result`** variable.
- The result is then logged to the console.

Using **`async`** and **`await`** simplifies the syntax for dealing with asynchronous operations and makes asynchronous code look more like synchronous code, improving readability and maintainability.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-json-and-what-are-its-common-operations?"></a>

## 28. What is JSON and what are its common operations?

**JSON (JavaScript Object Notation):**

JSON is a lightweight data interchange format that is easy for humans to read and write and easy for machines to parse and generate. It is a text format that is completely language-independent but uses conventions that are familiar to programmers of the C family of languages, including C, C++, C#, Java, JavaScript, Python, and many others.

JSON data is represented as key-value pairs and is often used to transmit data between a server and a web application, as well as to store configuration data.

**Common Operations with JSON:**

1. **Serialization:**

   Serialization is the process of converting a data structure or object into a format that can be easily stored or transmitted, such as converting an object into a JSON string. This is done using the **`JSON.stringify()`** method in JavaScript.

   ```javascript
   const person = { name: "John", age: 30, city: "New York" };
   const jsonString = JSON.stringify(person);
   console.log(jsonString);
   // Outputs: {"name":"John","age":30,"city":"New York"}
   ```

2. **Deserialization:**

   Deserialization is the process of converting a serialized JSON string back into a data structure. This is done using the **`JSON.parse()`** method in JavaScript.

   ```javascript
   const jsonString = '{"name":"John","age":30,"city":"New York"}';
   const person = JSON.parse(jsonString);
   console.log(person);
   // Outputs: { name: "John", age: 30, city: "New York" }
   ```

3. **Accessing Data:**

   Once JSON data is deserialized, you can access the values using the standard dot notation or square bracket notation.

   ```javascript
   const person = { name: "John", age: 30, city: "New York" };
   console.log(person.name); // Outputs: John
   console.log(person["age"]); // Outputs: 30
   ```

4. **Modifying Data:**

   You can modify the values in a JSON object like any other JavaScript object.

   ```javascript
   const person = { name: "John", age: 30, city: "New York" };
   person.age = 31;
   person["city"] = "San Francisco";
   console.log(person);
   // Outputs: { name: "John", age: 31, city: "San Francisco" }
   ```

5. **Nested JSON:**

   JSON can represent nested structures, allowing you to create more complex data hierarchies.

   ```javascript
   const company = {
     name: "TechCo",
     employees: [
       { name: "Alice", age: 28 },
       { name: "Bob", age: 35 },
     ],
   };
   ```

These are some of the basic operations you might perform when working with JSON data in JavaScript. JSON is a versatile format, and its simplicity and ease of use make it a popular choice for data interchange in various applications.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-response-json()-method?"></a>

## 29. What is Response json() method?

The **`json()`** method of the [Response](https://developer.mozilla.org/en-US/docs/Web/API/Response) interface takes a `Response` stream and reads it to completion. It returns a promise which resolves with the result of parsing the body text as [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON).

Note that despite the method being named `json()`, the result is not JSON but is instead the result of taking JSON as input and parsing it to produce a JavaScript object.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-strict-mode?"></a>

## 30. What is strict mode?

Strict mode is a feature introduced in ECMAScript 5 (ES5) that allows developers to opt into a set of rules and restrictions to make their JavaScript code more robust and less error-prone. When strict mode is enabled, the JavaScript interpreter applies a stricter set of parsing and runtime behaviour rules, helping to catch common coding errors and prevent the usage of certain "unsafe" features.

To enable strict mode, you add the following line at the beginning of a script or a function:

```javascript
"use strict";
```

When strict mode is enabled:

1. **Variable Declaration:**
   Variables must be declared with **`const`**, **`let`**, or **`const`** before being used. Assigning a value to an undeclared variable or a variable that is a property of a non-writable global object (e.g., **`window`**) is not allowed.

   ```javascript
   "use strict";

   // This will throw an error
   x = 10; // ReferenceError: x is not defined
   ```

2. **Assignment to Read-Only Properties:**
   Assignment to read-only properties (such as global object properties) will result in a **`TypeError`**.

   ```javascript
   "use strict";

   // This will throw an error
   undefined = 10; // TypeError: Cannot assign to read-only property 'undefined' of object '#<Window>'
   ```

3. **Deletion of Variables or Functions:**
   Deleting variables, functions, or function arguments is not allowed.

   ```javascript
   "use strict";

   // This will throw an error
   delete x; // SyntaxError: Delete of an unqualified identifier in strict mode.
   ```

4. **Octal Literal Syntax:**
   Octal literals (e.g., **`0123`**) are not allowed.

   ```javascript
   "use strict";

   // This will throw an error
   const num = 0123; // SyntaxError: Octal literals are not allowed in strict mode.
   ```

5. **Function Parameters with Duplicate Names:**
   Function parameters with duplicate names are not allowed.

   ```javascript
   "use strict";

   // This will throw an error
   function sum(x, x) {
     // SyntaxError: Duplicate parameter name not allowed in this context
     return x + x;
   }
   ```

6. **`with` Statement:**
   The **`with`** statement is not allowed in strict mode.

   ```javascript
   "use strict";

   // This will throw an error
   with (obj) {
     // SyntaxError: Strict mode code may not include a with statement
     console.log(prop);
   }
   ```

These are just a few examples of the behaviors influenced by strict mode. Enabling strict mode is generally considered a good practice as it helps catch common programming errors and encourages the use of a safer subset of JavaScript features.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-difference-between-referenceerror-and-typeerror?"></a>

## 31. What is the difference between ReferenceError and TypeError?

In JavaScript, both **`ReferenceError`** and **`TypeError`** are error types that can be thrown during the execution of a program. However, they occur in different situations and indicate distinct issues in the code.

### **ReferenceError:**

- **Cause:**

  A **`ReferenceError`** occurs when you try to reference a variable or function that has not been declared or is not in scope.

- **Common Scenarios:**
  - Referencing an undeclared variable.
  - Referencing a variable or function before it is defined.
  - Trying to access a property or method on an undefined or null object.
- **Example:**

  ```javascript
  console.log(myVariable); // ReferenceError: myVariable is not defined
  ```

### **TypeError:**

- **Cause:**

  A **`TypeError`** occurs when an operation is performed on a value of an inappropriate type.

- **Common Scenarios:**
  - Calling a non-function as a function.
  - Attempting to access a property or method on a non-object (e.g., **`null`** or **`undefined`**).
  - Using an operator or method on a value that does not support that operation.
- **Example:**

  ```javascript
  let num = 42;
  num(); // TypeError: num is not a function
  ```

### **Summary:**

- **`ReferenceError`** is related to issues with variable or function references, typically involving undeclared or out-of-scope variables.
- **`TypeError`** is related to issues with the types of values and the operations performed on them, indicating that a value is not of the expected type for a given operation.

In practice, understanding the specific error message and the context in which it occurs is crucial for diagnosing and fixing issues in your JavaScript code. Both errors provide valuable information to help developers identify and resolve problems during development.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-polyfill?"></a>

## 32. What is a polyfill?

A polyfill is a piece of code that provides the functionality of features that are not natively supported by a web browser. Polyfills are used to fill the "gaps" or "holes" in browser support, enabling developers to use modern features in environments where those features might be lacking.

Here are the key points about polyfills:

1. **Feature Support:**
   Polyfills are commonly used to provide support for new ECMAScript (JavaScript) features or APIs that are not yet implemented in all browsers.
2. **Cross-Browser Compatibility:**
   Browsers may implement new features at different paces, leading to inconsistencies in terms of feature support across different browsers. Polyfills help ensure a consistent experience by bringing missing features to browsers that lack native support.
3. **Implementation:**
   Polyfills are typically implemented as JavaScript scripts that can be included in a web page. When a polyfill is loaded, it checks whether the targeted features are supported by the browser. If not, the polyfill provides the necessary code to emulate the missing functionality.
4. **Usage:**
   Developers include polyfills in their web projects to extend support for modern features to older browsers or browsers that haven't yet implemented certain features. This allows developers to write code using the latest standards without worrying about compatibility issues.

Here's a simplified example of a polyfill for the **`Array.prototype.includes`** method, which was introduced in ECMAScript 2016 (ES7):

```javascript
// Polyfill for Array.prototype.includes
if (!Array.prototype.includes) {
  Array.prototype.includes = function (searchElement, fromIndex) {
    // Implementation logic to mimic the behavior of includes
  };
}
```

In this example, the polyfill checks if the **`includes`** method is already defined on the **`Array.prototype`**. If not, it provides an implementation to mimic the behavior of the **`includes`** method. This ensures that the **`includes`** method is available on arrays in all environments, regardless of native support.

Developers often use tools like Babel and core-js to automatically include necessary polyfills based on the target environments specified in their project configuration. This helps streamline the process of handling compatibility issues across different browsers.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-the-temporal-dead-zone?"></a>

## 33. What is the Temporal Dead Zone?

The Temporal Dead Zone (TDZ) is a concept in JavaScript that refers to the time span between the entering of a scope (such as a function or block) and the point where a variable is declared. During this period, attempting to access the variable results in a **`ReferenceError`**.

This behavior is primarily associated with variables declared using **`let`** and **`const`** declarations. Unlike variables declared with **`var`**, which are hoisted to the top of their scope and initialized with **`undefined`**, variables declared with **`let`** and **`const`** are also hoisted but remain uninitialized in the TDZ until their actual declaration is encountered.

Here's an example to illustrate the Temporal Dead Zone:

```javascript
console.log(x); // ReferenceError: Cannot access 'x' before initialization
console.log(y); // undefined

const x = 10; // Declaration and initialization are hoisted
let y = 20; // Declaration is hoisted, but initialization is not

console.log(x); // Outputs: 10
console.log(y); // Outputs: 20
```

In this example, the reference to **`x`** before its declaration is allowed because variables declared with **`const`** are hoisted and initialized with **`undefined`**. On the other hand, attempting to access **`y`** before its declaration results in a **`ReferenceError`** due to the Temporal Dead Zone.

The Temporal Dead Zone helps catch potential issues related to variable access before their declaration, promoting cleaner and more predictable code. It is important to be aware of this behavior, especially when working with **`let`** and **`const`** declarations, and to declare variables at the beginning of the scope to avoid unexpected behavior.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-tree-shaking?"></a>

## 34. What is tree shaking?

Tree shaking is a technique used in modern JavaScript build tools to eliminate dead (unused) code from the final bundled code, specifically in the context of ES6 module systems (such as those using **`import`** and **`export`** statements). The goal of tree shaking is to reduce the size of the JavaScript bundle that is delivered to the browser by removing any code that is not actually used or referenced in the application.

Here's how tree shaking typically works:

1. **Module System:**
   Tree shaking is most effective when using ES6 modules, which have a static structure that allows the build tools to analyze and understand the dependencies between modules.
2. **Dead Code Elimination:**
   During the build process, the tool analyzes the application code and identifies parts of the code that are not reachable or not used based on the entry point of the application.
3. **Marking Unused Code:**
   Unused or dead code is marked for removal by the build tool. This involves creating a dependency graph of the modules and their dependencies.
4. **Removing Unused Code:**
   The build tool then removes the marked unused code from the final bundled output. This results in a smaller, more optimized bundle that only includes the code necessary for the application to function.

Tree shaking is particularly beneficial in large-scale applications or libraries where developers might include multiple modules but only use a subset of their functionality. By eliminating the unused code, tree shaking helps reduce the overall file size of the JavaScript bundle, leading to faster load times and improved performance.

It's important to note that successful tree shaking relies on the code being written in a way that allows for static analysis. Dynamic imports or other runtime-dependent code structures may limit the effectiveness of tree shaking.

Tools like Webpack, Rollup, and Parcel are commonly used in the JavaScript ecosystem, and they often include built-in support for tree shaking as part of their optimization features. Additionally, developers can configure their build tools to enable or enhance tree shaking based on the specific needs of their projects.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-typescript?"></a>

## 35. What is TypeScript?

[TypeScript](https://www.typescriptlang.org/) is a programming language that extends JavaScript by adding static types. It is a superset of JavaScript, which means that any valid JavaScript code is also valid TypeScript code. However, TypeScript introduces additional features and syntax that enable developers to write more maintainable and scalable code.

Key features of TypeScript include:

1. **Static Typing:** TypeScript introduces static typing, allowing developers to define and enforce types for variables, function parameters, and return values at compile-time. This helps catch type-related errors early in the development process.

   ```tsx
   function add(x: number, y: number): number {
     return x + y;
   }

   let result: number = add(3, 5);
   ```

2. **Interfaces:** TypeScript supports the definition of interfaces, which allow developers to define contracts for object shapes. This helps in achieving better code organization and type checking.

   ```tsx
   interface Person {
     name: string;
     age: number;
   }

   function greet(person: Person): string {
     return `Hello, ${person.name}!`;
   }
   ```

3. **Classes:** TypeScript supports class-based object-oriented programming with features like inheritance, encapsulation, and abstraction.

   ```tsx
   class Animal {
     constructor(public name: string) {}

     makeSound(): string {
       return "Some generic sound";
     }
   }

   class Dog extends Animal {
     makeSound(): string {
       return "Woof! Woof!";
     }
   }

   const myDog = new Dog("Buddy");
   console.log(myDog.makeSound()); // Outputs: Woof! Woof!
   ```

4. **Generics:** TypeScript allows the creation of generic functions and classes, providing flexibility in working with different types while maintaining type safety.

   ```tsx
   function identity<T>(value: T): T {
     return value;
   }

   let result: number = identity(42);
   ```

5. **Modules:** TypeScript supports the organization of code into modules, making it easier to manage and structure large codebase.

   ```tsx
   // math.ts
   export function add(x: number, y: number): number {
     return x + y;
   }

   // app.ts
   import { add } from "./math";

   let result: number = add(3, 5);
   ```

6. **Compatibility with JavaScript:** Existing JavaScript code can be gradually migrated to TypeScript, as TypeScript allows JavaScript code and TypeScript code to coexist in the same project.

To use TypeScript, you need to install the TypeScript compiler (**`tsc`**) and create a **`tsconfig.json`** file to configure the compiler settings. The TypeScript code is then transpiled into standard JavaScript, which can be executed in any JavaScript runtime.

TypeScript is widely used in large-scale web development projects and is particularly popular with frameworks like Angular, which is developed using TypeScript. It helps developers catch errors early in the development process, enhances code readability, and provides a more robust development experience compared to plain JavaScript.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-bom?"></a>

## 36. What is BOM?

BOM stands for Browser Object Model, which is a part of the web browser's environment that provides additional objects and interfaces beyond the Document Object Model (DOM). While the DOM deals with the structure and content of web documents, the BOM provides a way to interact with the browser itself and some aspects of the user's environment.

Key components of the Browser Object Model (BOM) include:

1. **Window Object:**

   - The **`window`** object is the top-level object in the BOM hierarchy and represents the browser window. It serves as the global object in client-side JavaScript and provides various properties and methods for interacting with the browser environment.

   ```javascript
   // Examples of window properties and methods
   window.alert("Hello, world!"); // Display an alert dialog
   let width = window.innerWidth; // Get the inner width of the browser window
   ```

2. **Navigator Object:**

   - The **`navigator`** object provides information about the user's browser and its capabilities. It includes properties such as browser name, version, and platform.

   ```javascript
   // Example of navigator properties
   let browserName = navigator.userAgent; // Get the user agent string
   ```

3. **Location Object:**

   - The **`location`** object represents the current URL of the browser. It provides properties and methods to work with the URL.

   ```javascript
   // Example of location properties and methods
   let currentURL = location.href; // Get the current URL
   location.assign("https://example.com"); // Navigate to a new URL
   ```

4. **Screen Object:**

   - The **`screen`** object provides information about the user's screen, such as screen dimensions and color depth.

   ```javascript
   // Example of screen properties
   let screenWidth = screen.width; // Get the screen width
   ```

5. **History Object:**

   - The **`history`** object represents the user's navigation history. It allows navigation to previous or next pages in the history.

   ```javascript
   // Example of history methods
   history.back(); // Go back one page in the history
   history.forward(); // Go forward one page in the history
   ```

It's important to note that the Browser Object Model is not standardized, and its features can vary between different browsers. While some properties and methods are common, developers should be cautious when relying on specific BOM features for cross-browser compatibility. In modern web development, the focus is often on using standardized features provided by the Document Object Model (DOM) and other web APIs.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-same-origin-policy?"></a>

## 37. What is same-origin policy?

The Same-Origin Policy is a security feature implemented by web browsers to prevent web pages from making requests to a different domain than the one that served the original web page. The policy helps protect users from potentially malicious actions, such as cross-site request forgery (CSRF) and cross-site scripting (XSS) attacks.

The Same-Origin Policy enforces that:

1. **Same Protocol:**
   The protocol (e.g., HTTP or HTTPS) of the requesting page and the requested resource must be the same.
2. **Same Domain:**
   The domain (including subdomains) of the requesting page and the requested resource must be the same.
3. **Same Port:**
   The port number of the requesting page and the requested resource must be the same.

If any of these conditions are not met, the browser restricts the web page's ability to interact with the content from a different origin. This prevents malicious websites from making unauthorized requests on behalf of a user and accessing sensitive data.

For example, consider the following scenarios:

**Allowed by Same-Origin Policy:**

```
https://example.com/page1.html can make a request to https://example.com/api/data
```

**Blocked by Same-Origin Policy:**

```
https://example.com/page1.html cannot make a request to https://api.example.net/data
```

To overcome the Same-Origin Policy restrictions, web developers often use techniques such as:

1. **Cross-Origin Resource Sharing (CORS):**
   Servers can include specific HTTP headers to allow or deny cross-origin requests. This is known as CORS, and it allows controlled access to resources on a different domain.
2. **JSONP (JSON with Padding):**
   JSONP is a technique for overcoming the Same-Origin Policy by using **`<script>`** tags to make cross-origin requests. While it has limitations, it is a workaround used in certain scenarios.
3. **Proxy Servers:**
   Web developers may set up server-side proxies to forward requests from the same origin, avoiding Same-Origin Policy issues.

It's essential for web developers to be aware of the Same-Origin Policy and understand how to work within its constraints or use appropriate techniques to enable cross-origin communication when necessary. Properly handling cross-origin interactions helps maintain the security and integrity of web applications.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-indexeddb?"></a>

## 38. What is IndexedDB?

IndexedDB (Indexed Database) is a low-level, JavaScript-based database API for web browsers. It provides a way for web applications to store and retrieve large amounts of data, persistently, and efficiently on the client side. Unlike cookies or local storage, IndexedDB is designed to handle more complex data storage needs and is suitable for applications that require storing structured data, such as offline web applications or those dealing with large datasets.

Key features of IndexedDB include:

1. **Asynchronous API:**
   IndexedDB operations are asynchronous, meaning that they do not block the main thread, helping to maintain a smooth user experience. This is crucial for handling large datasets without causing the application to become unresponsive.
2. **Object-Oriented Storage:**
   Data is stored in object stores, where each object store holds key-value pairs. Objects can be complex structures, and the data is indexed based on keys, allowing for efficient retrieval.
3. **Indexed Access:**
   IndexedDB allows developers to create indexes on properties of stored objects, enabling efficient querying and retrieval of data based on these indexes.
4. **Transaction-Based:**
   Operations in IndexedDB are grouped into transactions. A transaction is a unit of work that may involve multiple operations, ensuring data consistency.
5. **Large Data Support:**
   IndexedDB is designed to handle large amounts of data, making it suitable for applications that require local storage of significant datasets, such as document editing or offline applications.
6. **Security:**
   IndexedDB follows the same-origin policy, meaning that a web application can only access its own data. This helps ensure security and prevents malicious websites from accessing or modifying data stored by other websites.

Here's a simple example of using IndexedDB to open a database, create an object store, and add data:

```javascript
// Open or create a database
const dbRequest = indexedDB.open("myDatabase", 1);

// Handle database opening success
dbRequest.onsuccess = function (event) {
  const db = event.target.result;

  // Create an object store
  const objectStore = db.createObjectStore("myObjectStore", { keyPath: "id" });

  // Add data to the object store
  objectStore.add({ id: 1, name: "John Doe", age: 30 });
};

// Handle errors
dbRequest.onerror = function (event) {
  console.error("Error opening database:", event.target.error);
};
```

IndexedDB is a powerful tool for web developers to build web applications with more sophisticated data storage requirements. However, it also comes with a steeper learning curve compared to simpler storage mechanisms like local storage or cookies. Libraries and frameworks may be used to simplify the usage of IndexedDB in web applications.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-module?"></a>

## 39. What is a module?

A module is a self-contained unit of code that can be reused and imported into other parts of a program. Modules help in organizing and structuring code, making it more manageable, scalable, and maintainable, especially in large applications.

Prior to the introduction of ES6 (ECMAScript 2015), JavaScript lacked built-in support for modules. However, with ES6, the language introduced a standard module system via the import and export keywords.

Here's a basic example of how modules work:

```javascript
// In a file named module1.js
export function greet(name) {
  console.log(`Hello, ${name}!`);
}

// In another file
import { greet } from "./module1.js";

greet("John"); // Output: Hello, John!
```

In this example:

- The **`greet`** function is defined in a module called **`module1.js`**.
- The **`export`** keyword is used to make the **`greet`** function available for use outside of the module.
- In another file, the **`import`** statement is used to bring the **`greet`** function into the current scope from the **`module1.js`** module.
- Finally, the **`greet`** function is invoked with a name parameter, resulting in the message "Hello, John!" being logged to the console.

Modules in JavaScript help improve code organization, encapsulation, and reusability, making it easier to build and maintain complex applications.

Modules are a type of design pattern which is a group of ways to organize the code.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-is-a-web-api?"></a>

## 40. What is a Web API?

A web API (Application Programming Interface) is a set of rules and protocols that allows different software applications to communicate with each other over the internet. It defines the methods and data formats that applications can use to request and exchange data or services.

A web API is typically accessed through HTTP requests, making it accessible from any programming language or platform that supports HTTP. It enables developers to build new applications or integrate existing ones by leveraging the functionality provided by the API.

There are different types of web APIs, including:

1. **RESTful APIs**: REST (Representational State Transfer) APIs follow the principles of RESTful architecture, which uses standard HTTP methods (GET, POST, PUT, DELETE) to perform CRUD (Create, Read, Update, Delete) operations on resources. RESTful APIs are widely used due to their simplicity, scalability, and statelessness.
2. **SOAP APIs**: SOAP (Simple Object Access Protocol) APIs use XML-based messaging protocol for communication between applications. SOAP APIs provide a more structured and rigid approach compared to RESTful APIs, often used in enterprise-level systems where strict security and transaction management are required.
3. **GraphQL APIs**: GraphQL is a query language and runtime for APIs developed by Facebook. GraphQL APIs allow clients to request only the data they need, enabling more efficient data fetching and reducing over-fetching or under-fetching of data compared to traditional RESTful APIs.
4. **JSON-RPC and XML-RPC APIs**: These are remote procedure call (RPC) protocols that allow clients to invoke methods or procedures on remote servers and receive the results over HTTP. JSON-RPC uses JSON as the data format, while XML-RPC uses XML.

Web APIs are commonly used for various purposes, such as accessing data from external sources (e.g., social media platforms, weather services), integrating with third-party services, building client-server architectures, and enabling communication between different components of a distributed system. They play a crucial role in enabling interoperability and building interconnected applications in the modern web ecosystem.

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="how-does-destructuring-work-in-javascript-and-what-are-its-use-cases?"></a>

## How does destructuring work in javascript, and what are its use cases?

When you're writing code in JavaScript, you might have to deal with how things happen in the background—which is called "asynchronous" behavior. JavaScript uses something called an **event loop** to manage how and when different parts of code get executed. The event loop decides the order in which things happen, and here is where we meet two important types of tasks: **microtasks** and **macrotasks**. Let’s explore the differences between them!

### What Are Tasks in JavaScript?
To get the idea of microtasks and macrotasks, imagine JavaScript as a teacher managing a to-do list for a classroom. Some things are urgent and need to be taken care of quickly, while others can wait just a little longer. The event loop is like this teacher, deciding what gets done next. Microtasks and macrotasks are two kinds of "to-do" items that JavaScript has to handle.

### What Are Macrotasks?
**Macrotasks** (sometimes just called "tasks") are bigger, and they represent things that take a bit more time or need to wait for something else to happen. Examples of macrotasks include events like **setTimeout()**, **setInterval()**, or user interactions like clicking a button. These tasks go into a queue called the **task queue**.

For example, if you tell JavaScript to wait for 1 second before running a piece of code (using `setTimeout`), that task goes into the macrotask queue. Once JavaScript finishes all the important work it’s doing, it will check the queue and handle the macrotask.

### What Are Microtasks?
**Microtasks** are smaller and considered more urgent. They include things like **promises** (a way to handle asynchronous operations) and **MutationObserver** (used to monitor changes in the DOM—which is how web pages are structured). Microtasks go into a different queue called the **microtask queue**.

Microtasks always get priority over macrotasks. This means that whenever JavaScript is done with its current work, it will first check to see if there are any microtasks waiting before moving on to any macrotasks.

Imagine a teacher with a bunch of papers to grade: microtasks are like quick yes/no questions that need to be answered right away, while macrotasks are like full essays that the teacher can grade after those quick questions are handled.

### How Does This Affect the Event Loop?
The **event loop** is responsible for deciding what JavaScript will do next. Here’s the usual order:
1. JavaScript runs the current piece of code (like a function).
2. It checks the **microtask queue** and handles everything there first.
3. After all the microtasks are done, it moves on to the **macrotask queue** and handles the next macrotask.
4. The event loop repeats this process over and over again.

This means that **microtasks** get priority and will run before **macrotasks**, even if the microtasks are added later. If a promise is resolved, JavaScript will make sure to handle that promise’s microtask before moving on to a macrotask, like executing code from `setTimeout()`.

### Example to Make It Clearer
Here’s a quick example to illustrate:
```javascript
setTimeout(() => {
  console.log('This is a macrotask');
}, 0);

Promise.resolve().then(() => {
  console.log('This is a microtask');
});

console.log('This is regular code');
```
In this example, the output will be:
1. **This is regular code** (the main synchronous code runs first).
2. **This is a microtask** (because promises are microtasks and get handled before macrotasks).
3. **This is a macrotask** (the `setTimeout()` is a macrotask, so it runs last).

### Quick Summary
- **Microtasks**: Smaller, urgent tasks that happen right after the current code finishes. Examples are promises.
- **Macrotasks**: Bigger tasks that can wait a little longer. Examples are `setTimeout()` and other delayed code.
- **Event Loop**: The system that keeps everything moving, making sure microtasks get priority before macrotasks.

Understanding this difference helps when you're trying to figure out why some parts of your JavaScript code run before others—it's all about how the event loop manages microtasks and macrotasks!

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="what-are-template-literals-and-how-do-they-differ-from-string-concatenation?"></a>

## What are template literals, and how do they differ from string concatenation?

Imagine you need to write a sentence using pieces of information that change, like someone's name or age. In programming, you use "strings" to represent text, but how you put those pieces together can be done in different ways. Two common methods for doing this in JavaScript are **template literals** and **string concatenation**. Let’s dive in and see what these are, and how they’re different from each other.

### String Concatenation

**String concatenation** is a fancy way of saying you're combining pieces of text together. Imagine you want to say, "Hello, my name is Alex and I am 16 years old." If you use string concatenation, you would do something like this:

```javascript
let name = "Alex";
let age = 16;
let message = "Hello, my name is " + name + " and I am " + age + " years old.";
console.log(message);
```

Here, you’re using the **+** sign to glue the different parts together. While this works, it can get messy when you have a lot of text to connect, especially if the sentence is long. You have to keep adding **+** and make sure all the quotes are in the right places. This can be hard to read and easy to mess up.

### Template Literals

**Template literals** are a newer and easier way to build strings in JavaScript. Instead of using **+** to connect different pieces, you use a special type of quotes called **backticks** (`). With template literals, you can directly include variables in your text by using **${}**. Here's how you could write the same sentence with a template literal:

```javascript
let name = "Alex";
let age = 16;
let message = `Hello, my name is ${name} and I am ${age} years old.`;
console.log(message);
```

Notice that we used backticks instead of regular quotes, and we put **${name}** and **${age}** right where we want the values to go. This way, you don’t need to use **+** signs, and the whole thing is easier to read. It’s like filling in the blanks in a sentence.

### Key Differences

1. **Ease of Use**: Template literals are much easier to read and write, especially for long sentences or when you have lots of variables to include.
2. **Formatting**: With template literals, you can easily add line breaks or even create multi-line strings without needing any extra symbols. For example:
   
   ```javascript
   let poem = `Roses are red,
   Violets are blue,
   JavaScript is awesome,
   And so are you!`;
   ```

   In string concatenation, you’d have to add special characters for line breaks, which can make it confusing.
3. **Readability**: Template literals are often more readable because you don’t have all the **+** symbols everywhere. The variables are just placed directly into the text, making it look like a normal sentence.

### Conclusion

Template literals make writing strings in JavaScript simpler and clearer compared to string concatenation. They help make your code easier to understand, especially when you're working with a lot of variables. Instead of worrying about all the **+** symbols and quotes, you can use backticks and just put your variables inside **${}**. It’s like filling in blanks in a mad-lib, and it’s one of the reasons why many programmers prefer using template literals today.

So next time you’re writing some JavaScript and need to create a message, give template literals a try—they might just make your code a lot more fun to write!

<div align="right">

[back to Questions](#questions)

</div>

---

<a name="understanding-the-difference-between-eventpreventdefault-and-eventstoppropagation-in-javascript"></a>

## Understanding the difference between event.preventDefault() and event.stopPropagation() in JavaScript

JavaScript is used to make websites interactive, and it often has to respond to different actions a user takes, like clicking a button or filling out a form. To do this, JavaScript listens to "events" on a webpage, and sometimes developers use special commands to control these events. Two of those commands are **event.preventDefault()** and **event.stopPropagation()**. Although they sound similar, they do different things. Let's explore each one!

### What Does event.preventDefault() Do?

**event.preventDefault()** is used when you want to stop the browser from doing something that it would normally do. For example, when you click on a link, the browser usually takes you to a new webpage. But sometimes, you might want to stop this from happening. Imagine you click on a link, but instead of going to a new page, you want a pop-up message to show. This is where **event.preventDefault()** comes in.

Here are a few examples of when you might use **event.preventDefault()**:
- Stopping a link from opening a new webpage.
- Preventing a form from being submitted before all the fields are filled out.

In short, **event.preventDefault()** blocks the browser's default behavior for an event.

### What Does event.stopPropagation() Do?

**event.stopPropagation()** is used when you want to stop an event from "bubbling" up to other elements. Let me explain what "bubbling" means. In HTML, elements are often nested inside each other. For instance, a button might be inside a div, and that div might be inside a larger section. When you click on the button, JavaScript sees that click event not only on the button but also on all the elements around it, like the div and the section. This process is called "event bubbling."

Sometimes, you want to stop this bubbling. For example, if you click on a button, you may want only the button to react, not the whole page. By using **event.stopPropagation()**, you can make sure that the event stays only with the button and doesn't affect the other elements.

Here are a few examples of when you might use **event.stopPropagation()**:
- Preventing a click on a button from also triggering a click event on its parent element.
- Making sure only one specific part of the page reacts to an event without affecting other parts.

In short, **event.stopPropagation()** stops an event from spreading out to other elements.

### Summary: The Key Difference
- **event.preventDefault()** stops the browser’s default action for an event. It’s like telling the browser, "Don’t do what you usually do!"
- **event.stopPropagation()** stops an event from moving up the chain of elements. It’s like telling the event, "Stay here, don’t tell anyone else!"

Knowing the difference between these two commands can help you better control how your webpage behaves, making it more interactive and user-friendly!


<div align="right">

[back to Questions](#questions)

</div>

---

<a name="understanding-microtasks-vs.-macrotasks-in-javascript"></a>

## Understanding microtasks vs. macrotasks in JavaScript

When you're writing code in JavaScript, you might have to deal with how things happen in the background—which is called "asynchronous" behavior. JavaScript uses something called an **event loop** to manage how and when different parts of code get executed. The event loop decides the order in which things happen, and here is where we meet two important types of tasks: **microtasks** and **macrotasks**. Let’s explore the differences between them!

### What Are Tasks in JavaScript?
To get the idea of microtasks and macrotasks, imagine JavaScript as a teacher managing a to-do list for a classroom. Some things are urgent and need to be taken care of quickly, while others can wait just a little longer. The event loop is like this teacher, deciding what gets done next. Microtasks and macrotasks are two kinds of "to-do" items that JavaScript has to handle.

### What Are Macrotasks?
**Macrotasks** (sometimes just called "tasks") are bigger, and they represent things that take a bit more time or need to wait for something else to happen. Examples of macrotasks include events like **setTimeout()**, **setInterval()**, or user interactions like clicking a button. These tasks go into a queue called the **task queue**.

For example, if you tell JavaScript to wait for 1 second before running a piece of code (using `setTimeout`), that task goes into the macrotask queue. Once JavaScript finishes all the important work it’s doing, it will check the queue and handle the macrotask.

### What Are Microtasks?
**Microtasks** are smaller and considered more urgent. They include things like **promises** (a way to handle asynchronous operations) and **MutationObserver** (used to monitor changes in the DOM—which is how web pages are structured). Microtasks go into a different queue called the **microtask queue**.

Microtasks always get priority over macrotasks. This means that whenever JavaScript is done with its current work, it will first check to see if there are any microtasks waiting before moving on to any macrotasks.

Imagine a teacher with a bunch of papers to grade: microtasks are like quick yes/no questions that need to be answered right away, while macrotasks are like full essays that the teacher can grade after those quick questions are handled.

### How Does This Affect the Event Loop?
The **event loop** is responsible for deciding what JavaScript will do next. Here’s the usual order:
1. JavaScript runs the current piece of code (like a function).
2. It checks the **microtask queue** and handles everything there first.
3. After all the microtasks are done, it moves on to the **macrotask queue** and handles the next macrotask.
4. The event loop repeats this process over and over again.

This means that **microtasks** get priority and will run before **macrotasks**, even if the microtasks are added later. If a promise is resolved, JavaScript will make sure to handle that promise’s microtask before moving on to a macrotask, like executing code from `setTimeout()`.

### Example to Make It Clearer
Here’s a quick example to illustrate:
```javascript
setTimeout(() => {
  console.log('This is a macrotask');
}, 0);

Promise.resolve().then(() => {
  console.log('This is a microtask');
});

console.log('This is regular code');
```
In this example, the output will be:
1. **This is regular code** (the main synchronous code runs first).
2. **This is a microtask** (because promises are microtasks and get handled before macrotasks).
3. **This is a macrotask** (the `setTimeout()` is a macrotask, so it runs last).

### Quick Summary
- **Microtasks**: Smaller, urgent tasks that happen right after the current code finishes. Examples are promises.
- **Macrotasks**: Bigger tasks that can wait a little longer. Examples are `setTimeout()` and other delayed code.
- **Event Loop**: The system that keeps everything moving, making sure microtasks get priority before macrotasks.

Understanding this difference helps when you're trying to figure out why some parts of your JavaScript code run before others—it's all about how the event loop manages microtasks and macrotasks!

<div align="right">

[back to Questions](#questions)

</div>

---
