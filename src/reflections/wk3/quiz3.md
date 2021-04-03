# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation: Privately stored information that can only be accessed/changed by an objects method. (import/export)

Abstraction: the selection of certain data from a larger "pool" of data (filter()?) so that it only shows the relevent details to the object

Inheritance: One object "inherits" all (or some depending) properties of another object (ProxyState?)

PolyMorphism: Grants a class (child) all the properties of its parent so there is no confusion of mixing types.

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation: Privately stored information that can only be accessed/changed by an objects method. (import/export)

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```

Single-responsibility principle: one job and one reason for a class to change

```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```

A class describes all the different data types and an instance of a class describes a single object of that data type that exists in memory.

```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```

A Proxy (ProxyState) is a copy of an object so that the client has access to it but mostly monitors the object until it is changed (ProxyState.on).

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```

MVC pattern helps organize files of particular data to help seperate different functions and make it easier for the programmer and future programmers to help read the data. Also assists with encapsulation and what the client thas access to with being selective with what files get what information (import/export)

```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller helps translates information from the model and sends it to the Services file telling it when and if to run.

```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```

The Service file in MVCS format handles all of the "business logic" pertaining to how the information should be run 

```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```

The Model file describes the overall properties of what the individual Classes will entail. The AppState will help describe the individual details that will be sent to the other files in the form of a ProxyState not AppState so that the main information will maintain integrity.

```

