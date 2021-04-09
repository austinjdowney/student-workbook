## Day 3: Working with Multiple API's

## Afternoon Challenge: https://austinjdowney.github.io/pokedex-afternoon-challenge/

Date: Wednesday | Apr 7, 2021
WORKING WITH MULTIPLE API'S


Daily Journal
Read Asynchronous Code > Async and Await and answer the following questions

1. What is the purpose of Async/Await?

To add more syntax to Promises to help developers read other code while making code look synchronous but really its asynchronous and non-blocking.

Async prepends a function that will then ultimately return a "promise" and make complex asynch functions easier to chain and read. 

Awaits are required within the Async functions to let the function know what to do when the function stops (whether resolved or rejected)

2. What must you do in order to await a promise inside of a function?

You must define the function as async before assigning await prependage so you can call the function.

3. What are some of the primary benefits of Async/Await?

Async/Await helps make code easier to read and less cluttered, but also makes the code easier to debug because to the compiler it looks like synchronous code.




## Morning Challenge
Factorialize a Number
Create a function that takes a number as its argument and returns an array of all its factors.

// Examples:
// factorize(12) ➞ [1, 2, 3, 4, 6, 12]
// factorize(4) ➞ [1, 2, 4]
// factorize(17) ➞ [1, 17]

function factorize(n) {
<!--:check every number starting at 1
-if the number is a multiple:perfectly divisible (no remainder)
-add to array-->

let factors=[]
    for (let i = 1; i <= n; i ++){
    if (n % i == 0){
        factors.push(i)
    }
return factors
    }
}

<!-- My attempt

for (let i = 1; i <= n; i++){
    if (n % i==0 ){
        map?
    }
}
}-->
