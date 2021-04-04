![img](https://miro.medium.com/max/1024/1*JA57AArvHLn3tulDxJKzEg.jpeg)


# **Whats JS Loops?**

Loops are used to execute the same block of code again and again, as long as a certain condition is met. The basic idea behind a loop is to automate the repetitive tasks within a program to save the time and effort. 

**JavaScript now supports five different types of loops**

1. while — loops through a block of code as long as the condition specified evaluates to true.

2. do…while — loops through a block of code once; then the condition is evaluated. If the condition is true, the statement is repeated as long as the specified condition is true.

3. for — loops through a block of code until the counter reaches a specified number.

4. for…in — loops through the properties of an object.

5. for…of — loops over iterable objects such as arrays, strings, etc.

# **The while Loop**

This is the simplest looping statement provided by JavaScript.

The while loop loops through a block of code as long as the specified condition evaluates to true. As soon as the condition fails, the loop is stopped. The generic syntax of the while loop is:

**while(condition) {
    // Code to be executed
}**


# **The do...while Loop**
The do-while loop is a variant of the while loop, which evaluates the condition at the end of each loop iteration. With a do-while loop the block of code executed once, and then the condition is evaluated, if the condition is true, the statement is repeated as long as the specified condition evaluated to is true. The generic syntax of the do-while loop is:

**do {
    // Code to be executed
}
while(condition);**

# **Difference Between while and do...while Loop**

The while loop differs from the do-while loop in one important way — with a while loop, the condition to be evaluated is tested at the beginning of each loop iteration, so if the conditional expression evaluates to false, the loop will never be executed.

With a do-while loop, on the other hand, the loop will always be executed once even if the conditional expression evaluates to false, because unlike the while loop, the condition is evaluated at the end of the loop iteration rather than the beginning.

![img2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkmvSasCItDhkZscGgGzI7IaNMRAO9BzKL5w&usqp=CAU)

# **What is JS Function?**

A function is a group of statements that perform specific tasks and can be kept and maintained separately form main program. Functions provide a way to create reusable code packages which are more portable and easier to debug. **Here are some advantages of using functions:**

* Functions reduces the repetition of code within a program — Function allows you to extract commonly used block of code into a single component. Now you can perform the same task by calling this function wherever you want within your script without having to copy and paste the same block of code again and again.
* Functions makes the code much easier to maintain — Since a function created once can be used many times, so any changes made inside a function automatically implemented at all the places without touching the several files.
* Functions makes it easier to eliminate the errors — When the program is subdivided into functions, if any error occur you know exactly what function causing the error and where to find it. Therefore, fixing errors becomes much easier.
* The following section will show you how to define and call functions in your scripts.
# **Defining and Calling a Function**
The declaration of a function start with the function keyword, followed by the name of the function you want to create, followed by parentheses i.e. () and finally place your function's code between curly brackets {}. Here's the basic syntax for declaring a function:

**function functionName() {
    // Code to be executed
}**

# **Adding Parameters to Functions**

You can specify parameters when you define your function to accept input values at run time. The parameters work like placeholder variables within a function; they're replaced at run time by the values (known as argument) provided to the function at the time of invocation.

Parameters are set on the first line of the function inside the set of parentheses, like this:

**function functionName(parameter1, parameter2, parameter3) {
    // Code to be executed
}**

# **Default Values for Function Parameters ES6**

With ES6, now you can specify default values to the function parameters. This means that if no arguments are provided to function when it is called these default parameters values will be used. This is one of the most awaited features in JavaScript. Here's an example:
# **Returning Values from a Function**
A function can return a value back to the script that called the function as a result using the return statement. The value may be of any type, including arrays and objects.

The return statement usually placed as the last line of the function before the closing curly bracket and ends it with a semicolon.

# **Working with Function Expressions**
The syntax that we've used before to create functions is called function declaration. There is another syntax for creating a function that is called a function expression.
# **Understanding the Variable Scope**
However, you can declare the variables anywhere in JavaScript. But, the location of the declaration determines the extent of a variable's availability within the JavaScript program i.e. where the variable can be used or accessed. This accessibility is known as variable scope.

By default, variables declared within a function have local scope that means they cannot be viewed or manipulated from outside of that function.


![img3](580b585b2edbce24c47b24c3.png)





