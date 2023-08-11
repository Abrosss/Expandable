# Recursion
Recursion is a programming technique where a function calls itself to solve a problem. It's like a loop, but instead of repeating a set of instructions, the function calls itself with modified input. 
</br>
Here's how recursion works:

- Base Case: A recursive function always starts with a base case (where to stop?)
- Recursive Case: What to do next iteration?
- Termination: As the function calls itself, the problem size decreases until it reaches the base case.

# Factorial
Factorial is a mathematical operation that represents the product of all positive integers from 1 to a given positive integer "n." It is denoted by the symbol "n!".
```
function factorial(n) {
    if (n === 0 || n === 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}
const result = factorial(5);
console.log("Factorial of 5:", result); // Output: Factorial of 5: 120
```

# Fibonacci Sequence
 Fibonacci Sequence is a set of numbers, following the rule that each number is equal to the sum of the two preceding numbers. Fibonacci 
 </br>
- F(0) = 0
- F(1) = 1
- F(n) = F(n-1) + F(n-2) for n > 1
```
function fibonacci(n) {
    if (n === 0) {
        return 0;
    } else if (n === 1) {
        return 1;
    } else {
        return fibonacci(n - 1) + fibonacci(n - 2);
    }
}
```
# Memoization
Memoization is a technique used in computer programming to optimize the execution of functions by caching or storing the results of expensive function calls and returning the cached result when the same inputs occur again. 
</br>
Here's how memoization works:
1. Function Call: When a function is called with certain arguments, the program first checks if the result for those arguments is already stored in a cache or memoization table.
2. Cache Check: If the result is found in the cache, the stored result is returned immediately without re-executing the function. This saves computation time.
3. Cache Miss: If the result is not found in the cache, the function is executed as usual to compute the result. After calculating the result, it is stored in the cache for future reference.
   
Memoization is particularly effective for recursive functions where the same inputs are used multiple times during computation. Without memoization, recursive functions might end up recalculating the same values many times, leading to unnecessary computational overhead.
</br>
In programming, memoization can be implemented using data structures like arrays, hash maps, or dictionaries to store the cached results. Modern programming languages and libraries often provide built-in tools for memoization to simplify its implementation and usage.
```
function fibonacciMemoization(n, memo = {}) {
    if (n in memo) {
        return memo[n];
    }
    if (n === 0) {
        return 0;
    } else if (n === 1) {
        return 1;
    } else {
        memo[n] = fibonacciMemoization(n - 1, memo) + fibonacciMemoization(n - 2, memo);
        return memo[n];
    }
}

```
