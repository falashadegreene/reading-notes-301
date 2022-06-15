## React Docs  List and Keys

1. What does .map() return? Returns new array
2. If I want to loop through an array and display each value in JSX, how do I do that in React? Use curly braces
3. Eash list item needs a unique key.
4. what is the purpose of a key? A key is a special string attribute you need to to include when creating a list of elements. Keys help React identify which items have changed are added or are removed.

## The Spread Operator

1. What is the spread operator? to add items to arrays, combining arrays or objects, and spreading and array out into a functions arguments.

2. List 4 things that the spread operator can do.

- Copy an array
- combine arrays
- use an array as arguments
- add an item to a list

3.Give an example of using the spread operator to combine two arrays.

`[..."xxxx"] [..."yyyy"]`


4. Give an example of using the spread operator to combine two objects into one.

 ` let hello = {hello: "xxxx"}
   let world = {world: "yyyy"}

   let helloWorld = {...hello,...world}
   console.log(helloWorld) {hello: "xxxx", world: "yyyy"}`

