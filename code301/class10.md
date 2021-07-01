# The call stak in JS

 interfaces: Frame, which encapsulates the data stored in a single stack frame, such as the operand stack and local variables; FrameSource, which encapsulates the allocation and layout of Frames, controlling such things as the argument-passing mechanism.

 **how many calls will be stored in stack for the recursive method below and why?**

 With an input of 50, the max amount of stack frames at any given moment, including the initial call to fib, will be 50. (So there will be at most 49 recursive calls stored on the stack at any given moment).

The reason there can be at most 50 stack frames is:

The initial call to fib(50) is 1 stack frame.

Then with this statement, return fib( n - 1 ) + fib( n - 2 ); the recursive call to fib on the left will execute first, putting fib(49) on the stack. We'll hit the return line again putting fib(48) on the stack. This will repeat until fib(1) is on the stack hitting the return 1; statement. This will return to fib(2) and allow the right recursive call to execute in the statement return fib( n - 1 ) + fib( n - 2 );.

### What Is LIFO

Last in, first out (LIFO) is a method used to account for inventory that records the most recently produced items as sold first. Under LIFO, the cost of the most recent products purchased (or produced) are the first to be expensed as cost of goods sold (COGS), which means the lower cost of older products will be reported as inventory.

The most-common cause of stack overflow is excessively deep or infinite recursion, in which a function calls itself so many times that the space needed to store the variables and information associated with each call is more than can fit on the stack

# JavaScript error messages


In JavaScript error message property is used to set or return the error message. Return Value: It returns a string, representing the details of the error. More example codes for the above property are as follows: Example 1: This example does not contains any error so it does not display error message.

### Syntax Errors
Syntax errors, also called parsing errors, occur at compile time in traditional programming languages and at interpret time in JavaScript.

For example, the following line causes a syntax error because it is missing a closing parenthesis.

### ReferenceError
Creates an instance representing an error that occurs when de-referencing an invalid reference