# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
used to declare scope of project/files
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structures and classes differ in the following particulars: Structures are VALUE types; classes are REFERENCE types. A variable of a structure type contains the structure's data, rather than containing a reference to the data as a class type does. Structures use stack allocation; classes use heap allocation.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

REVIEW.. not certain if this is right?

static methods for static classes will return that actual class and the static class members by using the static methods and from calling on the static class name
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
access modifier = public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
string is an indication of the value type that will be returned or accessed in the method
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The abstract keyword enables you to create classes and class members that are incomplete and must be implemented in a derived class.

The sealed keyword enables you to prevent the inheritance of a class or certain class members that were previously marked virtual.

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class. 

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

public: Access is not restricted.

protected:; Access is limited to the containing class or types derived from the containing class.

internal: Access is limited to the current assembly.

private: Access is limited to the containing type.

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Private access is the least permissive access level. Private members are accessible only within the body of the class or the struct in which they are declared

```