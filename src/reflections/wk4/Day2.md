## Day 2: HTTP REQUESTS CONTINUED

## Afternoon Challenge:  https://austinjdowney.github.io/gregslist2/

Daily Journal
Read Asynchronous Code > JavaScript Promises and answer the following questions

1. What are the three states of a Promise?
Pending: Initial State
Resolved: Completed Promise
Rejected: Failed Promise


2. How do promises seek to resolve the issues of "callback hell"?

Promises seek to clean up code with "chaining" so it is easier to read between .then and .catch statements.. kind of similar to a switch statement withh cases and breaks where you typically chain 
(function (){
.then (){
    return ....}; 
.then(){
    return ...};
.then(){
    return ...};
}).catch ();



3. What is the difference between .then() and .catch()?

.then() is used if the Promise is resolved (typically the if statement portion of the Promise function).

.catch() is used for the Promises that were rejected and get a different response, whether it is an error response or not


## Morning challenge
function mostCommonLetter(str) {
    let mostCommon = ''

    //pain don't need to do that
    //let letter= {a:0, b:0, c:0...}

    for (let i = 0; i < str.legnth; i++) {
        let char = str[i]

        //do this instead of writing all the letters out
        //to iterate over all the pertinent letters
        //if (!letters[char]) {
        //    letters[char] = 1
        //} else {
        //    letters[char]++
        //}
        //can also do
        letters[char] = letters[char] || 0
        letters[char]++
    }

    //move variables up under let char=str[i] and 
    //if statement under for loop to iterate over all the letters
    //and tracking is the largest
    let largest = 0
    let largestChar = ''
    for (let char in letters) {
        if (letters[char] > largest) {
            largest = letters[char]
            largestChar = char
        }
    }

    return largestChar
}