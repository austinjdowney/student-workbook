## Day3: Simulating Multiple Pages with the VUE Router

## Afternoon challenge: https://austinjdowney.github.io/vue-gregslist/

## morning challenge: https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting/diff-two-arrays

## Daily Journals:

Read Frontend Frameworks with Vue3 > Understanding VueJs Lifecycle Hooks and answer the following questions

1. What are lifecycle hooks? What are lifecycle hooks used for?

LIFESTYLE HOOKS are a window into how a library that you are using is working behind the scenes. LS Hooks allow you to when a component is created, added to the DOM, updated, or destroyed.

2. How have you utilized lifcycle hooks in your afternoon projects?

REVIEW

We have used onMounted to help register the CRUD methods in the setup(){} within the script tags to be able to update the information on the DOM (page) more readily bc the mounted hooks have full access to the reactive component, templates, and rendering the DOM.

3. What are mounting hooks? When might you use them?

Mounting hooks allow acces to the component immediately before and after the first render (they don't run during server-side rendering). Only use if you need access to modifying the DOM of your component beore or after initial render.. never to fetch data for your component on initialization.

I intend to use onMounted quite a bit for updating data on the page more easily with hte CRUD methods (post, put, gets, and deletes)