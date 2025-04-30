1. values added:  20
2. final result:  20
3. "Var" has no block scope, tolerates redeclarations, hoisting and uninitialized state.
4. values added:  20
5. ReferenceError: result is not defined
   Explanation: Because result was declared with let inside the {…} of the if block, it does not exist outside that block. The console.log on line 13 is trying to read a block-scoped variable that’s out of scope.
6. TypeError: Assignment to constant variable
   Explanation: The code declared result with const, which makes it read-only after its initial assignment. Because of this exception, execution stops, so nothing ever reaches the line 9.
7. ReferenceError: result is not defined
   Explanation: Result was declared with const inside the if (add){…} block and so does not exist in the outer scope where line 13 resides.
8. 