## Day 4: Audio/Video Tags and Review

## Afternoon Challenge:https://austinjdowney.github.io/funmusic/

## Morning Challenge
Make Time

Write a function called timeConvert(min) that takes the min parameter being passed and returns the number of hours and minutes the parameter converts to (ie. if num = 63 then the output should be 1:3). Separate the number of hours and minutes with a colon. If it is less than an hour you can return a 0 for hours

function timeConvert(min) {
    <!--let num= n
    let hours= n/60
    let rHours= Math.floor(hours)
    let minutes = (hours-rHours)*60
    let rMinutes= Math.round(minutes)
    return  -->

    let minutes=0 actually do min % 60
    let hours=0

    return `${hours} : ${minutes}`
}

## Daily Journal

Read Asynchronous Code > What is REST and answer the following questions
1. What does REST stand for, and in simple terms what does it mean?

REST stands for REpresentational State Transfer. Colloquially, it means when a RESTful API is called, that server will transer to the client (aka developer or browser) a representation of the STATE of the requestion resource(data/information) based off the API's constraints

<!-- watch user intereface video under RESTful API's-->
2. What does Stateless mean?

There is no memory storage about a user who uses an API. Each request is based off the information available at that time to perform the request and return the response, regardless of past requests.

3. What URL pattern is used when writing a RESTful API?

Using Uniform Resource Identifiers (URIs) to address resources that are intuitive and easy to use (nouns are best to represent a URI instead of a verb bc a verb refers to an action and nouns have properties, which verbs do not). Resources can be divided up into 4 different categories (document, collection, store, and controller) and should be kept to a single category per resource. 

-use forward slashes (/) to indicate hierarchical relationships

-don't use forward slashes (/)in URIs use dashes(-)

-do not use underscores (_)

-use lowercase letters in URIs

-don't use file extensions..  (i.e., xml etc.)

-don't use CRUD function names in URIs (GET all devices, CREATE new devices)

-use query component to filter URI collections
