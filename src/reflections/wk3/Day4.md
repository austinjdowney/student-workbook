## Day 4 = Working in MVC with complex data, array methods

## Afternoon Challenge: 

Daily Journal
Read Advancing with JS > The Observer Pattern and answer the following questions

What problems does the Observer Pattern seek to solve?

Complex linking of certain events to make it easier for client-side driven usability without functionality errors and a plethora of push and pull functions.

What are the three mechanisms of the observer pattern?

Subscribe method: use a push() function to push items into a certain array. Use OBSERVER.SUBSCRIBE to assign a function to an eventObserver as long as the function actually had an item to push into array. Common to use Node assertions in Node or even Chai assertions. Ideal to check length of array after pushing to make certain the array was indeed changed.

Unsubcribe method: use filter() function to draw out any items that you are intending to grab and create a new array list with those items. Use OBSERVER.UNSUBSCRIBE to remove the event observer from that function so it doesn't continue to watch the intended event. If there are no items within that call back time then everything stays the same. 

Broadcast method: start with const (variable)= and then for the variables that will be changed use let= to signal to yourself and other programmers that the variable inside of the callback fxn will be changing at some point. The broadcast method is good for iterating over all of the callbacks and executes all of them after passing in the (data) parameter or whatever parameter you intended to insert inside of your fxn to see if it changes the subscribed method. 

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

ProxyState.on is definitely efficient in being able to call out to _draw fxns easily between files (after importing/exporting) without having to do a plethota of draw fxns and push fxns. ProxyState variables are especially nice for similar reasons for making a copy of a variable especially when you know its going to change.