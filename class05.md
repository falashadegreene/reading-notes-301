
## Think in React 

1. What is the single responsibility principle and how does it apply to components? A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application? It takes your data model and renders the UI but has not interactivity.

3. Once you have a static application, what do you need to add? to build componets that reuse other components and pass data using props.

4. What are the three questions you can ask to determine if something is state?
 - Is it passed in from a parent via props?
 - does it remain unchanged over time?
 - can you compile it based on any other state or props in you componenent?

5. How can you identify where state needs to live? Identify every component that renders somthing based on that states.

## Higher-Order Functions

1. What is a “higher-order function”? functions that operate on other functions, either by taking them as arguments or returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? returning the (n) that was passed in the greater than function.

3. Explain how either map or reduce operates, with regards to higher-order functions. The method transforms an array by applying a function to all of its elements and building a new array from returned values.