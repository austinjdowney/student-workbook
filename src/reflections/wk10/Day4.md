## Day4: Building relationships with MySQL & Auth0

## Daily Journal
Read Foundations of C# > C# Enum's and answer the following questions

1. What is an Enum, and what are some use cases for them?

An Enum are strongly typed constants that you allow you to define that constant as another variable to make the code more readable.Enums are the value types, which means they have their own value and can't inherit or be inherited, but enums (lowercase) are able to inherit from the Base Class Library(BCL) type (which is the Enum)... enums (lowercase) help define Enums further.



Final Thoughts About C# Enum
Enums are lists of strongly typed constants with members that are symbolic names, corresponding to an underlying integral type. Enum base types can be changed and member values can be specified. The System.Enum .NET Framework Class Library type is the base class of enum types. It contains methods that allow you to work with enums in different ways, such as working with a list of names or values, converting from value to name, and converting from name to value. For more information on the System.Enum type, see the .NET Framework SDK documentation.



2. How can you modify an Enum?

You are able to modify an Enum through switch statements.. for example:

using System; 

// declares the enum 
public enum Volume
{ 
  Low, 
  Medium,
  High
}  

// demonstrates how to use the enum  
class EnumSwitch
{  static void Main()
 { 
   // create and initialize     
   // instance of enum type 
   Volume myVolume = Volume.Medium;  
   // make decision based 
   // on enum value     
   switch (myVolume)
    {        
        case Volume.Low:
          Console.WriteLine("The volume has been turned Down.");           break;
        case Volume.Medium:
          Console.WriteLine("The volume is in the middle.");           break;
        case Volume.High:
          Console.WriteLine("The volume has been turned up.");           break;
    }
    Console.ReadLine();
 }
}


3. How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)

I have not used an Enum yet, but I probably would have used it on rock, paper, scissors for different "attack" choices.