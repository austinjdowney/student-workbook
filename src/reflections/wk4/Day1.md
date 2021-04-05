## Day1: INTRO TO ASYNCHRONOUS CODE

## Afternoon Challenge:

Daily Journal

Read Asynchronous Code > Callback Hell and answer the following questions

1. What are some of the signs and causes of Callback Hell?

Callback Hell is having a plethora of functions that execution happens linearly from top to bottom creating a "pyramid" visual with there typically being a a lot of closing ) or } at the end of your function. 

2. What does the asynchronous mean and how are callbacks involved?

Asychronous means that you can have multiple different functions run that may be related to one another but aren't dependent on another function to still run and can still operate independently.

This is effective when needing to download files and have other things "load" and using callbacks to effectively store the result until it is ready to be called after everything else.

3. Summarize the 3 ways to avoid / fix Callback Hell

    -Keep your code shallow: Name functions properly to make it easier to clarify but function delcarations (typically at the bottom of a page, (function hoisting bc in JS it automatically searches for functions first and then executes file top to bottom)) can be placed/referenced by their name 

    -Modularize: build small modules and assemble them into bigger ones to seperate based off intention and call into other files that may need them

    -Handle every single error: SYNTAX errors by the programmer, RUNTIME errors that are by the programmer but are dicovered once the program runs and causes a bug somewhere, PLATFORM errors typically are invalid file permissions, HARD DRIVE failure, no network connection (TIMEOUT, typically solved with callbacks by the Node.js style of where the first argument is assuming it will fail((if(error){return console.error("OOPS", error)}))