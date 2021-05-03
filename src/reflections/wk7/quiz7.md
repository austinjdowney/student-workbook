# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```

<!-- REVIEW is this correct? -->

Binding a source to an image tag is the most common for me to be able to render the a user's picture or possibly any image. The other would be in a v-for and binding a prop or even a key to the component to render that information each time possible.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
In a single page application there is quicker processing speed and a bit easier to exchange the data that is relative to what you are intending to change and keeping the data that will be the same throughout. Relative to a multi-page application that may be more secure but might be more complex and easier to cause errors

```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```

It will mount/render whatever information you intend to be there on the page as soon as you route there 

```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```

creates a two-binding between the input and the component to be able to update in the data properties of the component, which is most common in a form input to update the new data additions/changes

```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```

instead of using an onClick it is @click to make certain on a button it is able to link to the proper function, whether it is a delete, add, edit, whatever you might like to happen @ the click.

```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
<!-- REVIEW are there any other v-attributes that would be ideal? -->

v-for helps render each new created element onto a page once the user has inputed the new data

```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```

The key attribute binds to the component or whichever HTML element you are liking to create more of in a v-for or even update or delete those same elements based off the specific id of that element of the key.


```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slot element allows you to exhange specific information that might be related to other information such as with GREGSLIST and exchanging information from the CarsModal to the Job and House modal to be able to keep similar info but using the slots to exhange the information that may be different.

```