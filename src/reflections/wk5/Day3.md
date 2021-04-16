## Day3: 

## Afternoon challenge

## Morning Challenge:

Middle Earth is about to go to war. The forces of good will have many battles with the forces of evil. Different races will certainly be involved. Each race has a certain 'worth' when battling against others. On the side of good we have the following races, with their associated worth:

On the Good Side:
Hobbits - 1,
Men - 2,
Elves - 3,
Dwarves - 3,
Eagles - 4,
Wizards - 10

On the side of evil we have:
Orcs - 1,
Men - 2,
Wargs - 2,
Goblins - 2,
Uruk Hai - 3,
Trolls - 5,
Wizards - 10

Although weather, location, supplies and valor play a part in any battle, if you add up the worth of the side of good and compare it with the worth of the side of evil, the side with the larger worth will tend to win.

Thus, given the count of each of the races on the side of good, followed by the count of each of the races on the side of evil, determine which side wins.

Input:
The function will be given two parameters. Each parameter will be a string separated by a single space. Each string will contain the count of each race on the side of good and evil.

The first parameter will contain the count of each race on the side of good in the following order:

Hobbits, Men, Elves, Dwarves, Eagles, Wizards.
The second parameter will contain the count of each race on the side of evil in the following order:

Orcs, Men, Wargs, Goblins, Uruk Hai, Trolls, Wizards.
All values are non-negative integers. The resulting sum of the worth for each side will not exceed the limit of a 32-bit integer.

Output:
Return
if Good wins - "Battle Result: Good triumphs over Evil"

if Evil Wins - "Battle Result: Evil eradicates all trace of Good"

if Tied - "Battle Result: No victor on this battle field"

function battle(goodTeam, badTeam){

let gWorth = 0
let eWorth = 0
<!---Make an array out of the arrays to seperate by each individual number-->
let goodArr = goodTeam.split(' ').map (v=>Number(v))
let evilArr = evilTeam.split(' ').map (v=>Number(v))

goodPoints[1,2,3,3,4,10]
evilPoints[1,2,2,2,3,5,10]

forEach( (u, i)=> gWorth += u * goodPoints[i]
forEach( (u, i)=> eWorth += u * evilPoints[i]

if (gWorth > eWorth){
return "Battle Result: Good triumphs over Evil"
}
if (gWorth < eWorth){
    return "Battle Result: Evil eradicates all trace of Good"
} 
    return "Battle Result: No victor on this battle field"

## Daily Journal

Read Servers with Node/Express > MongoDb Relationships and answer the following questions
1. In simple terms what is a sub-document?

A sub document is a document nested within another document.

2. When might you use a sub-document?

-Passing a nested object into a "new model"
    a new Schema: {name:,
    specials: [{},{},{}],
    ultimate:{}
    }


-Adding properties into the created document 

const collection = new Collection ({name: })

//adds new keys in an array
const collection.keys = [{
    name:
    moves:},
{name:
moves:},
{name:
moves:}
}]

//adds new key as an object 
collection.key={}


3. How do you add to a collection of sub-documents? What about editing them?

//To add to a collection... must use find one to target the key in the collection but set it equal to key in the collection. .save is REQUIRED

const key = await Collection.findOne({})
collection.key.push({
})

const updated= await key.save()

//To edit a collection also use the .findOne to target the intending key in that collection you'd like to edit
 
then dig in to the property you are liking to change and set that equal to what you'd like to change it to.   .save() is also required here


const key = await Collection.findOne({nameOfProperty: ""})

key.object.property=""

const updated= await key.save()

