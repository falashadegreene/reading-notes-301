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
## How to pass functions between component

1. In the video, what is the first step that the developer does to pass functions between components?
2. In your own words, what does the increment function do? it determines the next or increased level by one.
3. How can you pass a method from a parent component into a child component? by defining the function, function is passed as a prop to child component, next child component then calls the prop.
4. How does the child component invoke a method that was passed to it from a parent component? pass down functionality to children in props and pass back notifications from children in events. 