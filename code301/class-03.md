# Notes class-03

techniques for managing data increase the opportunities.

## React Docs - list and keys

1. .map() returns an array of the same length as the array it was called on.
2. You build the component inside the loop.
3. key
4. a unique identifier.

## Spread Operator

1. '...' an operator that splits a lists elements to act as separate arguments.
2. concatinating arrays, adding an item to a list, combining objects, converting NodeList to an array.
3. { const a = [1,2,3]; const b = [...a];const result = {...a,...b} === [1,2,3,1,2,3]
4. { const a = [1,2,3]; const b = [4,5,6,...a];const result = {...a,...b} === [4,5,6,1,2,3]
5. const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂 - https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

## How to Pass Functions Between Components

1. putting it into an object as a prop to be called in the child.
2. The parent version increments a count the child version identifies which needs to be incremented and calls the parent version with that information.
3. Passing it as a prop.
4. Calling it by name through props.

## Things I want to know more about

Was the person that wrote the spread operator article properly punished for the emojis?
