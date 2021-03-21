Before we talk more about scope, we first need to talk about blocks.

We’ve seen blocks used before in functions and if statements. A block is the code found inside a set of curly braces {}. Blocks help us group one or more statements together and serve as an important structural marker for our code.

A block of code could be a function, like this:

const logSkyColor = () => {
  let color = 'blue'; 
  console.log(color); // blue 
}
Notice that the function body is actually a block of code.

Observe the block in an if statement:

if (dusk) {
  let color = 'pink';
  console.log(color); // pink
}
In the next few exercises, we’ll see how blocks define the scope of variables.

Instructions
1.
At the top of main.js, declare a const variable, named city set equal to 'New York City'. This variable will exist outside of the block.

Checkpoint 2 Passed
2.
Below the city variable, write a function named logCitySkyline.

Checkpoint 3 Passed

Stuck? Get a hint
3.
Inside of the function body of logCitySkyline(), write another variable using let named skyscraper and set it equal to 'Empire State Building'.

Checkpoint 4 Passed

Stuck? Get a hint
4.
Inside the function, include a return statement like this:

return 'The stars over the ' + skyscraper + ' in ' + city;
Checkpoint 5 Passed

Stuck? Get a hint
5.
Beneath the logCitySkyline() function, use console.log() to log the value of logCitySkyline() to the console.

You’ll notice that the logCitySkyline() function is able to access both variables without any problems. In the next exercise we’ll consider why would it be preferable to have one variable outside of a block and the other inside of a block.