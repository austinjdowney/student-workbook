## Day 3 = Forms and Templates

## Afternoon challenges:

Daily Journal
Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions
1. What are the two common operations that we will set in the handler?

GETters: Which is an object operator to GET the value of a key

SETters: SETS or creates a new key to an object

2. What do you have to make sure you are doing with every Get to insure the value does not become undefined?

GET operator takes 2 perameters, the object itself and the property being accessed to store both the object and the change (called a "trap" bc it's a custom override). The GETter inherently returns the valued stored in that key in the object and overriding it with a console.log for example the value is never actually returned.

3. What are some of the benefits of the proxy object that we are using in our structure for applications?

Proxy objects allows to you "listen" and be notified when other functions will run (usually ("property", _draw)) without actually effecting the functions themselves unless you'd like to make those changes when those functions are called. Proxy creates a copy of the information without effecting the original information themselves (snacks = Proxy.snacks)