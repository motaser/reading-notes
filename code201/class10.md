# Error Handling & Debugging

JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

**EXECUTION CONTEXTS**
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

Each time a script enters a new execution context, there are two phases
of activity:

1. PREPARE
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined

2. EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements

**ERROR OBJECTS**


Error objects can help you find where your mistakes are
and browsers have tools to help you read them.


* Syntax Error: This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.

* Ref erenceError:This is caused by a variable that is not declared or is out of scope.

* EvalError:The eva l () function evaluates text through the
interpreter and runs it as code (it is not discussed
in this book). It is rare that you would see this type
of error, as browsers often throw other errors when
they are supposed to throw an Eva 1 Error.

* URI Error:If these characters are not escaped in URls, they will cause an error: / ? & I : ;

* Type Error:This is often caused by trying to use an object or method that does not exist.

* RangeError: If you call a function using numbers outside of its accepted range.

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSW9QHGZIWXRaLmYpttq9us_vo5KJ5R0bHAaQ&usqp=CAU)

* If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
* Debugging is the process of finding errors. It involves a
process of deduction.
* The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
* JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
* If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.
