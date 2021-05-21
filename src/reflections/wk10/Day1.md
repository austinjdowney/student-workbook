## Day1: Intro of C##

## Daily Journal
Read Foundations of C# > C# Data Types and answer the following questions

1. What are the three categories of data types? How are they different?

Value: A data type is a value type if it holds a data value within its own memory space. It means the variables of these data types directly contain values.

Example
int i= 100;

bool byte char decimal
double enum float int 
long sbyte short struct
uint ulong ushort

Reference: Unlike value types, a reference type doesn't store its value directly. Instead, it stores the address where the value is being stored. In other words, a reference type contains a pointer to another memory location that holds the data. Changing the data in one method

std2.StudentName="Steve";
Student std1 = new Student();
std1.StudentName="Bill";
ChangeReferenceType(std1);
Console.WriteLine(std1.StudentName); = "Steve"

In the above example, we pass the Student object std1 to the ChangeReferenceType() method. Here, it actually pass the memory address of std1. Thus, when the ChangeReferenceType() method changes StudentName, it is actually changing StudentName of std1 object, because std1 and std2 are both pointing to the same address in memory.

Example
string x = "YANKEES"

The followings are reference type data types:
String
Arrays
Class
Delegate
Default value of reference types is NULL

Pointer:The type specified before the * in a pointer type is called the referent type. Only an unmanaged type can be a referent type.

When you declare multiple pointers in the same declaration, the asterisk (*) is written together with the underlying type only; it is not used as a prefix to each pointer name.

Example
int* p1, p2, p3;   // Ok
int *p1, *p2, *p3;   // Invalid in C#


2. What are the Value-type data types? What differences do you notice from JavaScript?

Value-type data examples:
bool byte char decimal
double enum float int 
long sbyte short struct
uint ulong ushort

In C#, bools(bc of true or false), char(singular Character "A"), and number based values for the rest that pertain to the relative size of the int that may be trying to be assigned. 

JS just assigns the number regardless of the size


3. In your own words how do Reference types get stored in memory? How does this differ from Value types?

Reference types you have assign another value to then refer to that value to access it especially with strings to hold that value, but is never stored directly, such as with value data. 
