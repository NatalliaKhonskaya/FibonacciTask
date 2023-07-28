// A function that prints Fibonacci numbers.
// limit - an integer number of Fibonacci numbers the user wants
// Check line 34 that reffers to this code - number can be changed.
function printFibonacciNumbers(limit: number) {

// Array of Fibonacci numbers the function will print.
// We will store Fibonacci numbers in this array
// The formula I reffered to: F(N) = F(N - 2) + F(N - 1)
// To calculate the current number, we need to access two previous numbers, which are stored in this array.
  var result: number[] = [];

// already known Fibonacci numbers; push adds the new element to the end of array.
  result.push(0);
  result.push(1);
  

// Now, we will loop through remaining Fibonacci nmubers and append them to the result
// Note: index starts from 1. (First element, second element, etc)
  for (let i = 2; i < limit; i++) {
  let previous2 = result[i - 2];
  let previous1 = result[i - 1];

 // Current i-th Fibonacci number; F(N) = F(N - 2) + F(N - 1)
    let current = previous2 + previous1;

// Now we append it to the result
  result.push(current);
  }

  console.log(result);
}

// Calling the function to print the numbers
printFibonacciNumbers(10);
