# what-i-learned-week-5

#### flow charts

fizzbuzz function [my first flowchart](fizzbuzzflowchart.png)
**My first function based on logic diagram _flowchart_**

```javascript
function fizzy(num) {
  const fizz = "Fizz";
  const buzz = "Buzz";
  const fBuzz = "FizzBuzz";
  if (num % 3 !== 0 && num % 5 !== 0) {
    return num;
  } else if (num % 3 === 0 && num % 5 === 0) {
    return fBuzz;
  } else if (num % 3 === 0) {
    return fizz;
  } else return buzz;
}
```

format: (this is the format that we used for our front-end/back-end apps that we made this week)

1. get user input

The user interface is what allows the user to enter data; we used the terminal this week as our user interface.

2. run input through function

By using:

```javascript
function getInput(n) {
  return process.argv[n + 1];
}
```

We are able to take the input from the terminal and then by using:

```javascript
module.exports = getInput;
```

We are able to send that data to other files in our app and then by:

```javascript
const getInput = require("./get-input.js");
```

making this constant in a file we can write javascript code to run that "getInput" constant through functions in the current file or by making more _const's_ of functions in other files we can send the user's input elsewhere.

3. print result ---> on user interface.
   Finally, when the input data has run through all the places we want we can make the results display in the terminal with a _console.log_.
