# what-i-learned-week-5

- flow charts
- fizzbuzz function [my first flowchart](fizzbuzzflowchart.png)
- my first function based on logic diagram _flowchart_
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

format:

1. get user input
2. run input through function
3. print result ---> this separates user interface from backend.
   ! === not.

- escape character usage
- ```javascript
   \'	single quote
  \"	double quote
  \\	backslash
  \n	newline
  \r	carriage return
  \t	tab
  \b	word boundary
  \f	form feed
  ```

```

```
