## Day4: AUTH

## Afternoon Challenge:



## Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions


1. What is a virtual property?

A virtual property are additional fields for a given model or schema.. but aren't saved to the database ( full name is common e.g. user's first and last name)

2. When might you use a virtual property?

When you want to make your code more efficient and only want to write the properties assigned to the keys in a schema just once..

for example: userSchema.virtual('fullname').get(function() {
    return this.first + ' ' + this.last;
});


How do you search by a virtual properties value?

virtual properties are more private and not available for document queries or field selections. NOT static model properties.

## Morning Challenge:

Triangulation
Given three numbers to represent the length of each side of a triangle, determine if the three numbers can actually make a triangle or not. (hint: Triangle Inequality Theorem)

//EX: 10, 20, 29 --> true
//EX: 10, 20, 31 --> false
//EX: 31, 10, 20 --> false
function isTriangle(num1, num2, num3){
<!-- could just do this one liner if just numbers and not an array-->
return num1> num2 +num3 && num2> num1 + num3 && num3> num2 + num1

<!---Could also do this.. sort sorts the array from smallest to largest number then return that the largest number is still larger than the sum of the first two--->

arr.sort((a,b)=> a,b)
return arr[2]> arr[0] + arr[1]


let num1=0
let num2=0
let num3=0
let totalSides=0

for(i=0; totalSides>num.length; i++){


if(num1+num2 >= num3){
}
    return true
if(num1+num3 >= num2){
    return true
}
if (num2+num3 >= num1){
    return true
}
return false
}
}

