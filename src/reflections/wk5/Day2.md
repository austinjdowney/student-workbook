## Day 2: USING AN ORM TO INTERACT WITH A DATABASE

## Afternoon Challenge: 

## Morning Challenge:https://austinjdowney.github.io/catsapi/

Cats API
Start a new node server that will return a cat array when hitting the route api/cats and a dog array when requesting api/dogs



Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions

1. What are the three types of relationships?

1:1: one to one 
1:N one to many
N:M many to many

2. What are the benefits of the traditional linking of relationships instead of Embedding?

<!------------------Is this right???-------------------->

Traditional linking may be more optimal because you have more flexibility in assigning "foreign keys" instead of having it embedded and not as flexibile to be subjected to change.

3. What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

Depending on the size of either of the collections for N (example if N is a max of 3 categories for a book) and M (example of M is a max of 500000 books) then One-way embedding might be best but in cases where the collections are smaller, such as N > 3 and M>5 then two-way embedding might be preferred bc it is easier to manage both of the smaller collections relative to a larger collection like in One-way. 

If both collections are large third-way embedding might be preferred to pull the information you need from both into a third collection and edit from there.