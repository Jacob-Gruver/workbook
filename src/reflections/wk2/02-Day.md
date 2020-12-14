# Day 2 of Week 2 at Codeworks
__12/8/2020__

## What are the three different ways to write a function and what are the differences of each?

There are three different ways to write out a function, function declaration, anonymous functions, & arrow functions. A function declaration is the most common (that ive seen anyway) way to make a function. It writes out declaring a name to the function and it is hoisted allowing it to be defined wherever even before its defined. The second is the function expression which defines both an anonymous function and a function declaration. It cannot be hoisted. The third is arrow function which really is a fancier way to define a function except they dont create their own "this" value.

## What is parameters and what is arguments?

Parameters help define a function name while arguements are the value each function.

## What is a higher order function, and what does one look like?

Higher order functions either internalizes or returns another whole function. This allows for code to be clean and more simple and contain fewer bugs. They are easy to test and debug. A higher order function can look like,

    function funcWithinfunc() {
        return 12 % 3;
    }

    function  mathIt(math1, math2, funcWithinFunc) {
        let myMath = funcWithinFunc + math1 / math2;
        return myMath;
    }