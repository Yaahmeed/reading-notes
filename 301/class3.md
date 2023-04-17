# Passing Functions as Props  

## Lists and Keys  

1. Data types and JSX elements  

2. Use .map() to create a new array then use render() to display the values of the array, usually inside of a component  

3. Key  

4. A key is important to help React identify which items have changed, are added, or are removed. [reactjs.org](https://reactjs.org/docs/lists-and-keys.html)  

## The Spread Operator  

1. The spread operator is syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function's arguments. [medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)  

2. Copy an array, Concatenating or combining arrays, use Math functions, use array as arguments  

3. `let thisArr = ['a', 'b', 'c']`  
`let thatArr = ['d', 'e', 'f']`  
`let finalArr = [...myArray, ...yourArray]`  

4. `let carParts = ['engine', 'shocks', 'wheels']`  
`let moreCarParts = ['tires', 'brakes', ...carParts]`  

5. `let objOne = {hello}`  
`let objTwo = {...objOne, there}`  

## How to Pass Functions Between Components  

1. Create a function to pass in new state.  

2. The `increment` function will update the state count based on the name selected.  

3. In the video, he used `increment = {this.increment}` and `this.props.increment(this.props.name);`

4. In the video he used `this.props.increment(this.props.name);`

## Things I want to know more about  
