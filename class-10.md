# Class-10 Reading Notes

understanding the things that break a program can show you the things that need to be accounted for to prevent them.

## What Went Wrong

1. a syntax error can be identified prior to the program executing often preventing it from running, but a logic error may change the final outcome of the program without any problems running it.
2. Syntax errors relating to a method call, by adding a property to the constructor and setting it's value to the method call I was able to resolve the problem. A null value being read from caused a compiler error, when I changed the constructor so it stored the list I resolved the error by changing what was being called.
3. Understanding failed runs of a program can help to see that type of problem coming and act accordingly.

## The JavaScript Debugger

1. Imagine watching Jurassic Park and deciding you only care about what Jeff Goldblum is doing. Your program is the movie and Jeff is a variable. Using a debugger you can use a tool that allows you to mark the first time he appears on screen, and fast-forward to that point and then let you slowly follow what he does.
2. A break point is a line at which you are telling the debugger to stop so you can look at something. It makes it easier to step through what is happening
3. In a main function a call is made to a second function, and that function calls another, and so on, but after each function is completed it then needs to know where to go from there. It gets this information from the call stack. Each time a function is called its added to the stack and removed once it is complete.
