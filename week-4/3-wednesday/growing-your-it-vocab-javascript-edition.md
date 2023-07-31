# Essential Javascript Vocabulary 👨🏽‍💻🟨

Here are 50 essential JavaScript terms that every developer should know.

**1. Variables**: Named containers that store data values.
   - Example: Imagine a variable called "score" to keep track of a player's points in a game: 
   ```let score = 0;```

**2. Data Types**: The classification of data values in JavaScript.
   - Example: JavaScript has data types like strings, numbers, booleans, and objects.

**3. Operators**: Symbols used to perform operations on variables and values.
   - Example: The "+" operator can be used to add two numbers or concatenate two strings.

**4. Functions**: Reusable blocks of code that can be called with specific inputs.
   - Example: A function called "greet" can be used to say hello: 
   ```javascript
   function greet(name) { 
       return `Hello, ${name}!`; 
   }
   ```

**5. Control Flow (if-else, switch)**: Techniques to make decisions in code based on conditions.
   - Example: Using an "if-else" statement to check if a number is positive or negative.

**6. Loops (for, while, do-while)**: Iterative structures to repeat code execution.
   - Example: A "for" loop to print numbers from 1 to 5: 
   ```javascript
   for (let i = 1; i <= 5; i++) { 
       console.log(i); 
   }
   ```

**7. Arrays**: Ordered collections of data, represented by square brackets.
   - Example: An array called "fruits" with multiple elements: 
   ```let fruits = ['apple', 'banana', 'orange'];```

**8. Objects**: Unordered collections of key-value pairs, represented by curly braces.
   - Example: An object called "person" with properties like "name" and "age": 
   ```let person = { name: 'John', age: 30 };```

**9. Classes (ES6)**: Blueprint for creating objects with shared properties and methods.
   - Example: Defining a class "Car" with properties like "make" and "model", and a method "start()".

**10. Arrow Functions (ES6)**: Shorter syntax for writing functions in ES6.
   - Example: An arrow function to double a number: ```let double = (num) => num * 2;```

**11. Promises**: An object representing the eventual completion (or failure) of an asynchronous operation.
   - Example: Creating a promise that resolves after a delay: ```const delay = (ms) => new Promise(resolve => setTimeout(resolve, ms));```

**12. Async/Await**: A more readable way to work with promises in asynchronous code.
   - Example: Using async/await to fetch data from an API: 
   `````````javascript
   async function fetchData() { 
       const response = await fetch(url); 
   }
   `````````

**13. Callbacks**: Functions passed as arguments to another function and executed later.
   - Example: A callback function to log a message after a button click: ```button.addEventListener('click', () => console.log('Button clicked!'));```

**14. Closures**: Functions that "remember" their lexical scope even when executed outside that scope.
   - Example: A closure to create a counter function with private variables: 
   `````````javascript
   function counter() { 
       let count = 0; 
       return () => count++; 
   }
   `````````

**15. Scope (Global, Local)**: Scope refers to the accessibility of variables in different parts of the code.
   - Example: A local variable inside a function can't be accessed from outside, but a global variable can be used throughout the script.

**16. Hoisting**: JavaScript's behavior of moving variable and function declarations to the top of their scope.
   - Example: Even if a variable is declared later in the code, it can be used before its declaration due to hoisting.

**17. Prototypes**: Inheritance in JavaScript is based on prototypes, where objects inherit properties and methods from other objects.
   - Example: Adding a method "toString" to the Array prototype, making it available to all arrays.

**18. DOM (Document Object Model)**: A programming interface for HTML and XML documents, representing their structure as objects.
   - Example: Using the DOM to change the content of an HTML element dynamically.

**19. Event Handling**: Handling events (e.g., clicks, mouse movements) in JavaScript.
   - Example: Adding an event listener to a button to trigger an action when clicked.

**20. AJAX (Asynchronous JavaScript and XML)**: Technique to send and retrieve data from a server without reloading the whole page.
   - Example: Using AJAX to fetch data from a server and update a webpage without refreshing.

**21. JSON (JavaScript Object Notation)**: A lightweight data interchange format used to exchange data between a browser and a server.
   - Example: Storing data in JSON format: 
   
   ```{ "name": "John", "age": 30, "city": "New York" }```.

**22. Fetch API**: A modern JavaScript API to make HTTP requests and handle responses asynchronously.
   - Example: Using Fetch API to fetch data from an API and display it on a webpage.

**23. Template Literals (ES6)**: A way to create strings with embedded expressions in ES6.
   - Example: Writing a multiline string with variable interpolation using template literals.

**24. Modules (ES6)**: Encapsulating code into separate files and exporting/importing functionalities between them.
   - Example: Splitting a large JavaScript application into modules for better organization.

**25. Spread Operator (ES6)**: An operator that allows elements of an iterable (e.g., array, string) to be expanded into individual arguments or elements.
   - Example: Using the spread operator to concatenate arrays or clone objects.

**26. Destructuring (ES6)**: Extracting values from arrays or objects into distinct variables.
   - Example: Destructuring an array: 
   ```const [first, second, third] = myArray;```

**27. Map**: A built-in object in JavaScript used to store key-value pairs.
   - Example: Using a Map to store user preferences: 
   ```const preferences = new Map(); preferences.set('theme', 'dark');```

**28. Set**: A built-in object in JavaScript used to store unique values.
   - Example: Using a Set to store unique elements in an array: 
   ```const uniqueNumbers = new Set([1, 2, 3, 1, 2]);```

**29. Classes (ES6)**: Blueprint for creating objects with shared properties and methods.
   - Example: Defining a class "Person" with properties like "name" and "age", and methods like "sayHello()".

**30. Inheritance (ES6)**: Mechanism by which a class inherits properties and methods from another class.
   - Example: Creating a "Student" class that inherits from the "Person" class to reuse common functionalities.

**31. Error Handling (try-catch)**: A mechanism to handle and recover from runtime errors.
   - Example: Using a try-catch block to gracefully handle division by zero: 
   ```javascript
   try { 
       result = num1 / num2; 
   } catch { 
       result = "Error: Division by zero"; 
   }
   ```

Sure, here's the renumbered list starting from 32:

**32. Strict Mode**: A way to enforce cleaner syntax and prevent certain errors in JavaScript.
   Example: Enabling strict mode at the beginning of a script:
   ```javascript
   'use strict';
   ```

**33. ES Modules**: A standardized way of creating, exporting, and importing modules in JavaScript.
   - Example: Exporting functions and variables from a module to be used in other files.

**34. Web APIs**: Interfaces provided by browsers to interact with various functionalities.
   - Example: Using the Geolocation API to get the user's current location.

**35. Browser Compatibility**: Ensuring that web applications work consistently across different web browsers.
   - Example: Testing a website on multiple browsers to verify compatibility.

**36. Callback Hell**: A situation where nested callbacks lead to hard-to-read and maintain code.
   - Example: Multiple asynchronous operations nested within each other causing complex code flow.

**37. Event Bubbling and Capturing**: The order in which events are handled when nested elements have event listeners.
   - Example: Understanding the propagation of a click event from a nested element to its ancestors.

**38. Local Storage and Session Storage**: Mechanisms to store data locally in a web browser.
   - Example: Storing user preferences in local storage to remember their theme choice across sessions.

**39. Web Workers**: A way to run JavaScript code in the background without affecting the main UI thread.
   - Example: Using web workers to perform heavy computations without freezing the webpage.

**40. WebSockets**: A protocol that enables bidirectional communication between a web browser and a server.
   - Example: Implementing real-time chat functionality using WebSocket for instant messaging.

**41. Babel**: A tool that transpiles modern JavaScript code to an older version for compatibility with older browsers.
   - Example: Using Babel to convert ES6 code to ES5 so that it can run in older browsers.

**42. Transpilers**: Tools like Babel that convert code from one version of a programming language to another.
   - Example: Transpiling TypeScript code to JavaScript for browser compatibility.

**43. Bundlers (Webpack, Parcel)**: Tools that bundle multiple JavaScript and CSS files into a single file for optimized loading.
   - Example: Using Webpack to bundle an entire JavaScript application into a single bundle file.

**44. Linters (ESLint)**: Tools that analyze code for potential errors and enforce consistent coding styles.
   - Example: Running ESLint to identify and fix coding issues like unused variables and missing semicolons.

**45. Testing Frameworks (Jest, Mocha, Jasmine)**: Tools for writing and executing tests to ensure code correctness.
   - Example: Writing unit tests using Jest to check if a function returns the expected output.

**46. Debugging Tools (Chrome DevTools)**: Built-in browser tools to debug and inspect web applications.
   - Example: Using Chrome DevTools to inspect the DOM, set breakpoints, and debug JavaScript code.

**47. Functional Programming in JavaScript**: A paradigm that treats computation as the evaluation of mathematical functions.
   - Example: Using array methods like map, filter, and reduce for functional programming in JavaScript.

**48. Promises vs. Async/Await**: Different approaches to handle asynchronous operations in JavaScript.
   - Example: Comparing using promises and async/await to fetch data from a server.

**49. The Event Loop**: The mechanism that enables JavaScript to handle asynchronous operations efficiently.
   - Example: Understanding how the event loop works to manage callbacks and asynchronous tasks.

**50. JavaScript Frameworks and Libraries (React, Angular, Vue.js)**: Tools for building complex web applications.
   - Example: Using React to build a dynamic user interface with components and state management.