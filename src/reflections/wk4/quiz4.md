# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code refers to code that follows one after another and is dependent upon the prior function.

Aynchronous code refers to code that is all happening at once but you are able to make a "Promise" (async/await) to allow the function to run but still wait for a possible response from another function to finish running.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener usually("ProxyState.on("AppState variable, _draw)) watches a specific variable to change and then updates the result after that function has ran.. 

A SUBSCRIBE method event listener would similar, to a ProxyState.on, to select the observed events and push a new item into an array to then be called back thru a function.

UNSUBSCRIBE method counter to that will then remove these events from the array to be "observed"

BROADCAST method will iterate thru all of the observed events to then further execute all the callbacks in the array. (using data as the parameter makes the callback data bound)

```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-Closed Principle refers to code that should be able to be added on to but the functionality and intended purpose itself should stay relatively the same not break other code that may be dependent upon that code.

```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A CALLBACK function is in essence a function that will take time to produce your result instead of immediately returning it, depending on if it may rely on on another functions result to then run itself or even to help with processing speed to not have everything process at once. (Promises:async/await)
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a callback function that uses async and await to help with delaying a functions result if there is an order that is necessary for funcitonality of a program, but typically these may be contained between try{}catch(error){console.error} functions incase a function is not able to complete which will prevent your whole site from crashing and will console.log your error but keep functionality everywhere else.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
CRUD methods:

POST : Create
GET : Retrieve
PUT : Update
DELETE: Delete

```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface

```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service.js is responsible for calling to APIs because it is the one that handles all of the CRUD requests and other business functionality. 
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is useful for organizing code to know where you may need to debug but also to keep certain information private from other functions or information to help not just with security but functionality.

```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 error is a general error that there was something wrong with a websites server and was not able to be more specific.
```