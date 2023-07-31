# Programming Fundamentals 🔠🏆

🚀 As students embark on their journey into the world of coding and software development, understanding the essential programming fundamentals is crucial to build a solid foundation. This list has around 20 key terms that every aspiring programmer should become familiar with when learning how to code. 📚

From the basics of data types, variables, and constants to the power of loops, conditionals, and functions, these concepts form the building blocks of programming. Additionally, students will encounter the significance of arrays, strings, and numeric data types, which are fundamental for handling and manipulating data. 💻

Understanding the concept of scope and how functions work with parameters, arguments, and return values is vital to create reusable and efficient code. Furthermore, recursion and iteration, as highlighted in this list, demonstrate different approaches to solve problems and perform repetitive tasks. ♻️

Whether creating algorithms, designing programs, or delving into the complexities of software development, grasping these programming fundamentals will empower students to write code that is both functional and efficient. So let's dive into this list and discover the key terminology that will pave the way to becoming proficient developers. 🚀🌟

60. **A Program**:
   - Definition: A set of instructions written in a programming language to perform a specific task or solve a problem.
   - Example (JavaScript): 
     ```javascript
     console.log("Hello, world!");
     ```

61. **Algorithm**:
   - Definition: A step-by-step procedure or set of rules used to solve a particular problem or accomplish a specific task.
   - Example: A sorting algorithm like Bubble Sort or Merge Sort.

62. **Variables**:
   - Definition: Containers that hold data values and can change their values during the program's execution.
   - Example (JavaScript):
     ```javascript
     let age = 25;
     ```

63. **Constants**:
   - Definition: Similar to variables but with a fixed value that cannot be changed after initialization.
   - Example (JavaScript):
     ```javascript
     const PI = 3.14159;
     ```

64. **Data Types**:
   - Definition: The classification of data in a programming language, determining the type of values a variable can hold.
   - Example (JavaScript):
     ```javascript
     let name = "John"; // String data type
     let age = 30;      // Integer data type
     let isStudent = true; // Boolean data type
     ```

65. **Functions**:
   - Definition: Blocks of reusable code designed to perform a specific task or calculation.
   - Example (JavaScript):
     ```javascript
     function add(a, b) {
       return a + b;
     }
     ```

66. **Loops**:
   - Definition: Control structures used to execute a block of code repeatedly until a specified condition is met.
   - Example (JavaScript):
     ```javascript
     for (let i = 1; i <= 5; i++) {
       console.log("Iteration " + i);
     }
     ```

67. **Conditionals**:
   - Definition: Control structures used to make decisions in the code based on specified conditions.
   - Example (JavaScript):
     ```javascript
     let age = 18;
     if (age >= 18) {
       console.log("You are an adult.");
     } else {
       console.log("You are a minor.");
     }
     ```

68. **Arrays**:
    - Definition: Data structures that hold a collection of elements, each identified by an index or key.
    - Example (JavaScript):
      ```javascript
      let numbers = [1, 2, 3, 4, 5];
      ```

69. **Strings**:
    - Definition: A sequence of characters used to represent text data.
    - Example (JavaScript):
      ```javascript
      let message = "Hello, JavaScript!";
      ```

70. **Integers**:
    - Definition: Data type representing whole numbers without fractional parts.
    - Example (JavaScript):
      ```javascript
      let count = 10;
      ```

71. **Floats**:
    - Definition: Data type representing numbers with decimal points, allowing for fractional values.
    - Example (JavaScript):
      ```javascript
      let price = 19.99;
      ```

72. **Booleans**:
    - Definition: Data type representing either `true` or `false`, used for logical operations.
    - Example (JavaScript):
      ```javascript
      let isStudent = true;
      ```

73. **Null**:
    - Definition: A special value that represents the intentional absence of any object value.
    - Example (JavaScript):
      ```javascript
      let noValue = null;
      ```

74. **Undefined**:
    - Definition: A value automatically assigned to variables that are declared but not initialized.
    - Example (JavaScript):
      ```javascript
      let uninitializedVariable;
      console.log(uninitializedVariable); // Output: undefined
      ```

75. **Parameters**:
    - Definition: Variables listed in a function's declaration and used to receive arguments.
    - Example (JavaScript):
      ```javascript
      function greet(name) {
        console.log("Hello, " + name + "!");
      }
      ```

76. **Arguments**:
    - Definition: Values passed to a function when it is called, corresponding to the function's parameters.
    - Example (JavaScript):
      ```javascript
      greet("Alice"); // "Alice" is the argument passed to the greet function.
      ```

77. **Return**:
    - Definition: The value or result returned by a function after its execution.
    - Example (JavaScript):
      ```javascript
      function add(a, b) {
        return a + b;
      }
      let result = add(3, 5); // The function returns 8, and it's stored in the variable "result."
      ```

78. **Scope**:
    - Definition: The context in which variables are declared and accessible within the code.
    - Example (JavaScript):
      ```javascript
      function showNumber() {
        let number = 42; // "number" is in the function's local scope.
        console.log(number);
      }
      showNumber();
      ```

79. **Recursion**:
    - Definition: A programming technique where a function calls itself to solve a problem.
    - Example (JavaScript):
      ```javascript
      function factorial(n) {
        if (n === 0) return 1;
        return n * factorial(n - 1);
      }
      ```

80. **Iteration**:
    - Definition: The process of repeatedly executing a block of code using loops or recursion.
    - Example (JavaScript):
      ```javascript
      for (let i = 0; i < 5; i++) {
        console.log("Iteration " + i);
      }
      ```