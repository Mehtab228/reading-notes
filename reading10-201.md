# Reading 10 #

## It's important to know whats breaking your javascript when you have complex functions that are responsible for multiple things. It can be difficult without debugging tools. Also, learning about different types of error can help so you're more aware of what can go wrong when writing your code ##

### *Name some key differences between a Syntax Error and a Logic Error* ###

- Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!

- Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

### *List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them* ###

- Ive come across syntax errors quite a few times, luckily VScode highlights them and tells you what it was expecting, it is similar to logic errors in the sense that VScode tells you what it was expecting. From there its easier to troubleshoot what the problem might be

### *How will this topic continue to influence your long term goals?* ###

- Studying why errors occur and how to efficiently fix them using a consistent workflow can save tons of time

### *How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?* ###

- The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly

### *Define what a breakpoint is* ###

- When a programmer creates code they can add what is known as a breakpoint. A breakpoint is a point in the program where the code will stop executing

### *What is the call stack?* ###

- The Call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse click, and that the code is currently paused on the breakpoint