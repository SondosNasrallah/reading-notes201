# Error Handling & Debugging
* If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.

* Debugging is the process of finding errors. It involves a
process of deduction.

* The console helps narrow down the area in which the
error is located, so you can try to find the exact error.


* If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.


* Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

* JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error. 

  1. **Error** : Generic error - the other errors are all based upon this error.
  2. **Syntax Error**: Syntax has not been followed
       
  3. **RefrenceError**: Tried to reference a variable that is not declared/within scope

  4. **TypeError**: An unexpected data type that cannot be coerced

  5. **RangeError**: Numbers not in acceptable range

  6. **URI Error**: encodeURI ().decodeURI(),and similar methods used incorrectly

  7. **EvalError**: eval () function used incorrectly


* HOW TO DEAL WITH ERRORS? 

 1. Look at the error message, it tells you:
    * The relevant script that caused the problem.
    * The line number where it became a problem for the interpreter. 
    * The type of error.

2. Check how far the script is running.
3. Use breakpoints where things are going wrong.

4. When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script.

5. Break down I break out parts of the code to test smaller pieces of the functionality.

6. Check the number of parameters for a function, or the number of items in an array.