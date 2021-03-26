## Day2 W2= JS Functions, Objects, and Loops

## Afternoon challenge:https://austinjdowney.github.io/js-tests-loops-and-arrays/.

Daily Journal
Read Intro to JS > JavaScript Functions and answer the following questions

1. What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

FUNCTION DECLARATION is a named function that has the name of the function after the function keyword (function name()).. the function definition is hoisted above the function name so you are able to use the function before it is definied if that is your intention.

FUNCTION EXPRESSIONS are what define named and anonymous functions. One difference between a FUNCTION EXPRESSION and a FUNCTION DECLARATION are that because a FUNCTION DECLARATION is hoisted and a FUNCTION EXPRESSION is not.. a FUNCTION EXPRESSION and can not be used until it is defined 

<!--anonymous function= let name= function(parameters){

}>-->

ARROW FUNCTION EXPRESSION is just a short-hand version of a FUNCTION EXPRESSION.

<!-- let name = (parameters)=> {}-->

2. What is the difference between Parameters and Arguments?

A parameter is what is inputted into the function when it is declared and are commonly used as variables within the function's body. An argument is the value that the parameter receives or invokes after the function is executed.

3. What are higher order functions? Can you provide an example?

Higher-order functions infer that function is more than just directly gathering a value. There is usually some inference that there is an action within a function, such as the greaterThan for example:

<!--function greaterThan(n) {
    return m=> m>n;
}
let greaterThan5 = greaterThan(5);
console.log(greaterThan5(7));
//true-->

or there are also conditional "control flow" changes that include if, else, else if, and swithc statements that provide different parameters/actions to perform depending on different conditions.

let x=10
if (x < 10){
    greeting = "goodbye";
} else if (x > 10){
    greeting = "see you later";
} else {
    greeting = "hello";
}

Return>