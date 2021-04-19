## Day 1: Intro to Vue.js

## Afternoon Challenge: https://austinjdowney.github.io/vue-playground/

## Daily Journal
Read Frontend Frameworks with Vue3 > Understanding Component Based Architecture and answer the following questions

1. What is Component based architecture?

Smaller abstracted pieces of the UI, which can thus be nested inside of other components to meet complex UI designs (pages)

2. What are some benefits of Component based architecture?

Components have own interfaces than are able to update without affecting other components or the UI as a whole. Helps maximize functionality (react.js uses "diffing" algorithm to detect changes and only update those changes instead of the entire component).

CBA requires that all methods and APIs pertaining to a single component exist within that component's structure. 

One of the most major benefits are that component's are able to be reused as "copies" essentially for apps that want to reuse features but still want those "copies to act independently, such as Facebook and having multiple chat windows that resemble one another but still work independently.

Allows for more control over applications and a greater range of customization, relative to MVC.

What are some drawbacks to Component based architecture?

Purpose of CBA is to encapsulate all similar responsibilities that are going to be reused into one space.. when using many components, there is a high possibility that readability might become degraded. Over-use of react.js in your CBA as more of a framework and less as a component to be sprinkled thru which can be overbearing on a UI. Shouldn't dictate structure.