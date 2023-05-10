# Putting it all together  

## Thinking in React  

1. The single responsibility principle is that a component should ideally only do one thing. It applies to components in that each component should ideally have one task that it performs. [reactjs.org](https://reactjs.org/docs/thinking-in-react.html)  

2. A 'static' version of an app is the UI laid out with no interactivity.  

3. Once the 'static' version is built, add the minimal set of mutable 'state' that the app needs.

4. Three questions to determine if something needs state: "Is it passed in from a parent via props? If so, It probably isn't state." "Does it remain unchanged over time? If so, it probably isn't state." "Can you compute it based on any other state or props in your component? If so, it isn't state."  

5. Any information that can change over time (ie: user input)  

## Higher Order Functions

1. Higher order functions are functions that operate on other functions, either by taking them as arguments or by returning them. [eloquentjavascript.net](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)  

2. Line 2 is returning a function comparing is 'm' greater than 'n'  

3. `.map()` is a function that allows us to map through an array and create a new function that does something with select information within said array, thus making a higher order function.

## Things I want to know more about
