# Hoisting

Hosting is a mechanism which elevates variables and function declarations to the top of the block scope.

In case of variables or functions expressions, their definition is being hoisted but in case of function declaration, the whole function with content is being hoisted.

  console.log('test');
  const variable = 'value';
  
  function fun() {
    // some logic
  }
