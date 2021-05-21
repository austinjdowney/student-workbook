## Day2: Intro to WebApi's

## Daily Journal

Read Foundations of C# > C# List and answer the following questions
1. What is a List in C#?

A list is a collection (similar to an array) of any type of data, whether value types or even reference types (strings).

2. What List methods seem like you might use them often? Why?

Besides list constructor to generate the initial list with certain items.. 
List[index] to grab an item a given index

List.Add/List.AddRange will be beneficial to add not just one data point but multiple at a given time

List.Clear to empty a list may be beneficial in creating new datasets after testing

List.Contains would be a nice check to see how much data you initially have

List.CopyTo would be interesting when trying to combine datasets to a master one that you aren't  necessarily planning on manipulating 
----Copies all list items into the array, starting from the specified array index.

// list:	8 3 2
// array:	0 0 0 0 0
 list.CopyTo(array, arrayIndex: 2); 
// array:	0 0 8 3 2

List.Exists would be good to do a quick check and to be certain that an item is actually present in the list

List.Insert/InsertRange would be very beneficial to add certain data in a specfic spot

List.Remove

List.Reverse

List.Sort



3. How would you retrieve an item from a list? What method could you use?

List[index] would be the most ideal for this to grab a specific item as long as you know the index that item is at

List.Find/FindAll would be beneficial if you aren't certain of the index but wouldn't be as specific as knowing the index bc List.Find just returns the first occurance and FindAll returns every occurance 