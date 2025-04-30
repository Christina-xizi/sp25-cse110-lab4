1. Output: 3
   Explanation: Because i was declared with var, it has function scope, not block scope. After the for loop finishes, i still exists and its final value is the length of the array (3). Therefore, line 12 prints 3 rather than throwing an error.
2. Output: 150
    Explanation: Because discountedPrice is declared with var (function-scoped), it survives the loop and holds the last computed value (300 * 0.5).

