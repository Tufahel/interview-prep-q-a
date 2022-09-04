#### What is JavaScript?
> JavaScript
  - JavaScript is an object-oriented programming languages that commonly use to create interactive effects within browsers.
  - It allows to build into otherwise static HTML pages.
  - This langauage has been embedded in Netscape, Internet explorer and other web browsers.

#### Difference betwenn Java and JavaScript?
> Java vs JavaScript
  - Java is a complete programming language whereas JavaScript is coded program that can be introduced to HTML pages.
  - Java is an object oriented or structured programming language like c, c++ whereas JavaScript is a client-side scripting language.

#### What are the data types supported by JavaScript?
> There are 2 different kind of data in JavaScript.
  1. Primitive types: A primitive is simply a data type that is not an object and has no methods. 6 primitive types in JavaScript are: `Undefined`, `Null`, `Boolean`, `String`, `Symbol` and `Number`.
  2. Objects

#### What are the features of JavaScript?
> Features
  - It is a lightweight, interpreted programming language.
  - It is designed for creating network centric applications.
  - It is complementary to and integrated with Java.
  - It is complementary to and integrated with HTML.
  - JavaScript is open an cross-platform.

#### Is JavaScript a case-sensitive language?
> Yes, JavaScript is a case sensitive language. The language keywords, variables, function names, and any other identifiers must always be typed with a consistent capitalization of letters.

#### What are the advantages of JavaScript?
> Advantages:
  - Less Server Interaction: We can always validate user input before sending of to the server, this saves server traffic that means less loads on our server.
  - Immediate feedback to the visitors: Visitors don't have to wait for page reload to see if they forgotten to enter something. There is always an immediate feedback.
  - Increased interactivity: We can always create interfaces that react on the user hovers over them with the mouse and activate them via the keyboard.
  - Richer interfaces: Drag and drop components and sliders can be added by JavaScript for richer interfaces to the visitors.

#### How can you create an object in JavaScript?
> Object creation:
  - JavaScript supports Object concept very well.
    - ` var emp = { name: "Daniel", age: 23 }; `

#### How can you create an Array in JavaScript?
> Array creation:
  - Array can be defined using the array literals in the following way:
    - ` var x = []; var y = [1, 2, 3, 4]; `

#### What is a `name` function in JavaScript & how to define it?
> A named function has a name when it is defined. It can be defined using function keyword as:
  - ` function named(){}; `

#### Can you assign an anonymous function to a variable and pass it as an argument to another function?
> Yes! An anonymous function can be assigned to a variable and also pass it as an argument to another function.

#### What is argument objects in JavaScript and how to get the type of arguments passed to a function?
> JavaScript variable arguments are the arguments passed to a function.
  - ` function func(x){ `
    -   `console.log(typeof x, arguments.length);`
  -   `}`
  -   `func();   // ==> "undefined", 0`
  -  ` func(1);  // ==> "number", 1`
  -   `func("1", "2", "3"); // ==> "string", 3 `

#### What are the scopes of a variable in JavaScript?
> The scope of a variable is the region of your program in which it is defined. JavaScript variable will have only two scopes.
  - Global Variable- It is visible everywhere in your JavaScript code.
  - Local Variable - It will be visible only within a function where it is defined.

#### What is the purpose of `this` operator in JavaScript?
> In JavaScript, the `this` keyword refers to an object. Which object depends on how `this` is being invoked(used or called). The `this` keyword refers to different objects depending on how it is used:
  - In an object method, `this` refers to the object.
  - Alone, `this` refers to the global object.
  - In a function, `this` refers to the global object.
  - In a function, in strict mode, `this` is `undefined`.
  - In an event, `this` refers to the element that recieved the event.
  - Methods like `call()`, `apply()`, and `bind()` can refer `this` to any object.