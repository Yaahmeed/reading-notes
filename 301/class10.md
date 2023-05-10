# In Memory Storage  

## Understanding the JavaScript Call Stack [freecodecamp.org](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)  

1. A call is function invocation.  

2. 1 Only a single function execution is done at a time, from top to bottom.

3. Last In First Out

4. `function a(){`  
    `function b(){`  
      `function c(){`  
        `console.trace();`  
      `}`  
      `c()`  
    `}`  
    `b()`  
  `}`  
  `a()`  
5. A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error. [freecodecamp.org](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)  

## JavaScript error messages [codeburst.io](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)  

1. A reference error occurs when you try to access or use a variable that has not yet been declared.  

2. A syntax error occurs when the code is not written in a valid format/missing/improper syntax.  

3. A range error occurs if you try to manipulate an object with some length and give it an invalid length.  

4. A type error occurs when a value is used in a way that is not consistent with its data type.  

5. A breakpoint is used to set a place in the code for the to stop running during the debugging process.  

6. Using the word "debugger" will set a breakpoint in our code.  

## Things I want to know more about  
