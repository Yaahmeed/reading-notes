# Functional Programming  

## Functional Programming Concepts  

1. Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — [Wikipedia](https://en.wikipedia.org/wiki/Functional_programming) [medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)  

2. A pure is a function that returns the same result if given the same arguments; it does not cause any observable side effects.  
Imagine we want to implement a function that calculates the area of a circle. An impure function would receive radius as the parameter, and then calculate radius *radius* PI:  Why is this an impure function? Simply because it uses a global object that was not passed as a parameter to the function. [medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)  

3. Some benefits of pure functions: the code is easier to test. We don't need to mock anything. [medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)  

4. Immutability: Unchanging over time or unable to be changed. Its state cannot change after it is created. [medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)  

5. Referential transparency = pure functions + immutable data [medium.com](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)  

## Node JS Tutorial for Beginners #6 - Modules and require()  

1. A module is a reusable piece of code that can be included in other parts of our application. [youtube](https://www.youtube.com/watch?v=xHLd36QoS4k)  

2. The word 'require' is used to include a module in our code.  

3. We use `let module = require('./module');` and `module.export = module;` on the corresponding requiring and exporting pages.  

4. We have to use a `module.export = module;` on our exporting page.  

## Things I want to know more about  
