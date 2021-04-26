# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
vue create project-name
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
REVIEW
.env?
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
components should be data that is reusable
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
Template
Script
Style
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle (LSP)

Object substitutability. If S is a subtype of T then objects of T should be able to be substituted with objects of S since they are related

```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```

app.vue is the "default" page that contains elements that will be on every page that with SPA's really the main information thru the router-view should exchange for other information from the other pages

```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
State object within a component is more of a local definition of a variable but can pass AppState variables thru computed's in the state

```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
More of the business logic just like with the standard MVC pattern. Components/pages still pass the CRUD methods to the services

```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
app.vue contains the information that will be sent to the id="app" in the html
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
Style tag

scoped(to keep it within the "scope" of the file, but don't forget lang=scss in some files)
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
Computed()
```