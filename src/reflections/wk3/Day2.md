## Day 2 = Encapsulation

## Afternoon Challenge: https://austinjdowney.github.io/vendingmachineapp/

Daily Journal
Read Advancing with JS > Encapsulation in JavaScript and answer the following questions
1. What is the purpose of Encapsulation?

Encapsulation protects information from getting out that you may not want other modules getting to and has to be called thru an object's method keeping it private relative to other code.

2. What were some of the problems with closures and the underscore prefix?

Underscore prefixes are just a naming convention to help identify methods that are only intended to be used internally but since they do not have an actual functional purpose just an aesthetic identifier, then unexperienced developers may not know that and the break in that process and identifier wouldnt signify a break in that change. This also increases the possibility or surface area that hackers may be able to exploit.

Encapsulation helps prevent this by isolating certain files and what files have access to.

3. How do we create private variables in a ES6 Class? Why would you do this?

To create a private variable within an ES6 class you can add a # to make it a private static method (can be generator, async or even generator async functions) declarations (private getters and setters ) and are called on the class itself. This assists with encapsulation and hinders using that word outside of the scope.