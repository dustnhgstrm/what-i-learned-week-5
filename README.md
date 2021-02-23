# what-i-learned-week-5
- flow charts
- fizzbuzz function [my first flowchart](fizzbuzzflowchart.png)
- my first function based on logic diagram *flowchart*
  ``` javascript
  function fizzy(num) {
  const fizz = "Fizz"
  const buzz = "Buzz"
  const fBuzz = "FizzBuzz"
  if (num % 3 !== 0 && num % 5 !== 0) {
    return num;
  } else if (num % 3 === 0 && num % 5 === 0) {
    return fBuzz;
  } else if ( num % 3 === 0) {
    return fizz;
  } else return buzz;  
}
 ```
 
