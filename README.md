1. What is the difference between var, let, and const?
   Variables in JavaScript are declared using var, let, and const. The earlier method, var has function scope and permits both redeclaration and reassignment, which might occasionally result in errors. ECMAScript 2015 added let with block scope, which permits reassignment but prohibits redeclaration in the same scope. const has block scope as well, but once specified, its value cannot be changed. In contemporary JavaScript, developers typically avoid using var and instead use const for constant values and let for variables that might change.

2. What is the spread operator (...)?
   The spread operator (...) is used to expand or copy elements of an array or object.
   Example: const arr1 = [1, 2, 3]; const arr2 = [...arr1, 4, 5];

3. What is the difference between map(), filter(), and forEach()?
   These JavaScript array functions include map(), which modifies each element to generate a new array. Only elements that meet a criterion are added to a new array created by filter(). All forEach() does is cycle through the array and take a certain action. A new array is not returned.

4. What is an arrow function?
   JavaScript functions can be written more simply and neatly with an arrow function.
   For instance, const add = (a, b) => { return a + b; };

5. What are template literals?
   Template literals are used to write strings more easily using backticks (`) and ${} to insert variables. Example:   let name = "Arjito"; 

