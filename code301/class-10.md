# Reading notes class-10

Understanding errors and their causes can show the changes that need to be made to fix them.

## Understanding the JavaScript Call Stack

1. A Call is a function invocation.
2. One call can be executed at a time in a synchronous stack.
3. LIFO Last In Firs Out is the general rule when dealing with a stack.
4. [Top][3][2][1] funct1(){funct2(){funct3(){functTop()}}}
5. If the call stack exceeds the environment's maximum call stack most likely from recursive calls without an exit, effectively the memory alloted for the stack runs out and causes the environment to crash, like the end of a game of Jenga.

## JavaScript error messages

1. A reference error is an error that occurs when a variable has not yet been declared is called.
2. A syntax error is an error that occurs when something cannot be parsed.
3. A range error is an error that occurs when dealing with a range and trying to access a value outside the range.
4. A type error is an error that occurs when a value of a certain type is expected and a different type is passed in.
5. A break point is placed on a line in the code to mark that the debugger should stop there and wait.
6. Using the debugger statement has a similar effect to the break point
