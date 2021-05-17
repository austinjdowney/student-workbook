# Working in a Professional Environment

**1.** What is Inheritance?
<!-- enter you answer in the space below -->
```
<!-- REVIEW -->

What is Inheritance in Object Oriented Programming(OOP)? Inheritance is the procedure in which one class inherits the attributes and methods of another class. The class whose properties and methods are inherited is known as the Parent class. Similar to how one page has a the name at the top level and then you assign all of the styling under that top level class (.home{
  img{

  }
})

```
**2.** What is the `Singleton` design pattern?
<!-- enter you answer in the space below -->
```

In software engineering, the SINGLETON pattern is a software design pattern that restricts the instantiation of a class to one "single" instance

```
**3.** What is the `Observer` design pattern?
<!-- enter you answer in the space below -->
```

<!--- registering an observer --->

Function attach() provides a way we can register or associate an observer (subscriber) with a subject (publisher) 

<!-- removing an observer to a publisher -->

detach() is used to detach a disinterested observer from a publisher. 

<!-- notifigies obervers of a change -->

Method notify() notifies all subscribed observers of state change 

<!-- then actually updates the observer at the right time -->

Then update() on each observer.
```
**4.** What is the `Strategy` design pattern?
<!-- enter you answer in the space below -->
```

The strategy pattern is a behavioral design pattern that enables selecting an algorithm at runtime

  Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it.

  The main feature of this pattern is that the client has a set of algorithms in which a specific algorithm will be selected for use during runtime. These algorithms are interchangeable between them.

```
**5.** What is the `Factory` design pattern?
<!-- enter you answer in the space below -->
```

Object Oriented Programming 

Creational pattern so called because the pattern provides us with a clear interface to create objects while abstracting away the varied complexity or logic involved in creating them. This pattern, is called the Factory Pattern and it allows us to easily create objects in JavaScript.
  For example:
      The factory pattern wraps a constructor for different types of objects and returns instances of the objects via a simple API. It makes it easy to create different objects by exposing a simple API that return the specified object type.

```
**6.** What is test driven development?
<!-- enter you answer in the space below -->
```
“Test-driven development” refers to a style of programming in which three activities are tightly interwoven: 
  coding
  testing (in the form of writing unit tests)
  design (in the form of refactoring(making code as succinct and to the point as possible))

1. write a “single” unit test describing an aspect of the program
2. run the test, which should fail because the program lacks that feature
3. write “just enough” code, the simplest possible, to make the test pass
4. “refactor” the code until it conforms to the simplicity criteria
5. repeat, “accumulating” unit tests over time

```
**7.** In Scrum/Agile what is the DoD?
<!-- enter you answer in the space below -->
```

Scrum defines the Definition of Done in pretty simple terms: it’s the acceptance criteria that are common to every single user story.

However, that can be broad and a lot of places will also ensure that there has been a code review, has been tested, and thus finally is immediately deployable.

Some places break it down further:

      -The first is ready to merge. Everything in this checklist needs to be ticked off before the pull request is merged to the master branch. 
      -The second is actually done. Everything in this checklist must be ticked off before the card is moved to the Done column on our task boards.

```
**8.** Give two examples of a user story:
<!-- enter you answer in the space below -->
```
What are agile user stories?
    A user story is the smallest unit of work in an agile framework. It’s an end goal, not a feature, expressed from the software user’s perspective.

    A user story is an informal, general explanation of a software feature written from the perspective of the end user or customer. 

Examples (relative to CarbonFootprint):
“As a [persona], I [want to], [so that].”

    1. As a daily long-commuter to work, I want to see my daily carbon emissions from my vehicles, so that I can hopefully decrease my carbon footprint and choose a more optimal vehicle.

    2. As a homebody, I want to see my monthly utility usage for my water and electricity, so I can see how my usage varies from month to month and I can be more aware using different light-bulbs or even aware of how much water I actually use.


```
**9.** During which ceremony is your Sprint Backlog created?
<!-- enter you answer in the space below -->
```

After the team (i.e., PO, SM, Dev team) plans out what the product backlog and the DoD as is the end of the sprint. The team then creates a plan for how they will build the backlog items and get them “Done” before the end of the sprint. The work items chosen and the plan for how to get them done is called the SPRINT BACKLOG. By the end of SPRINT PLANNING the team is ready to start work on the SPRINT BACKLOG, taking items from the backlog, to “In-progress,” and “Done."

Also REVIEW https://www.atlassian.com/agile/scrum/ceremonies

```
**10.** In which of these ceremonies are Tasks assigned to you?
<!-- enter you answer in the space below -->
```
The Daily Stand-UP is where people mention the difficulties they faced, what is still blocking them from working, but also saying what TASKS they WILL work on, but tasks shouldn't necessarily be assigned.. there should be self-accountability and trying to take the initiative to assign your own TASKS.
```