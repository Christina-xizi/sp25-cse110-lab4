1. Line 12 prints "3".
   Explanation: Because i was declared with var, it has function scope, not block scope. After the for loop finishes, i still exists and its final value is the length of the array (3). Therefore, line 12 prints 3 rather than throwing an error.

2. Line 13 prints "150"
    Explanation: Because discountedPrice is declared with var (function-scoped), it survives the loop and holds the last computed value (300 * 0.5).

3. Line 14 prints "150" 
    Explanation: Because finalPrice was declared with var at the top of the function, it’s still in scope after the loop and holds the last computed value (for 300 at 50% off), so console.log(finalPrice) outputs 150.

4. The code will return [50, 100, 150]
    Explanation: Because i was declared with let inside the for loop and so doesn’t exist once the loop finishes, so there is no way to log it afterward.

5. 