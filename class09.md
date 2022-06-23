## Functioning Programing Concepts 

What is functional programming? It is a programing paradigm or a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data.

What is a pure function and how do we know if something is a pure function? it returns the same arguments.

What are the benefits of a pure function?  it is beneifical because it does not cause any observable side effects.

What is immutability? It means unchaning over time or unable to be changed according to the article. When data is immutable its state cannot change after its created.

What is Referential transparency?  A pure function will always have the same output, given the same input. example according to article: Passing `2` as a parameter of the `square function` will always returns 4. Now it can be replaced with `square 2` with 4.


## Module 

What is a module? Another Javascript file
What does the word ‘require’ do? It reads a js file, then executes the file, and then proceeds to return the exports object. (credit. nodejs.org)
How do we bring another module into the file the we are working in? example: `require('./');`
What do we have to do to make a module available? example: `module.exports = counter;`