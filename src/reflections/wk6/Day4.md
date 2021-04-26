## Day 4: USING AUTH0 IN VUEJS AND REVUE ADVANCED FRONTEND FRAMEWORKS

## Afternoon Challenge:

## Daily Journal

Read Frontend Frameworks with Vue3 > Using Nested Routes in Vue.js and answer the following questions
1. What is a nested route?

A nested route is the ability to refer to multiple pages (children) thru another already established route that overarches the other pages (parent route... ex path" '/travel', component: TravelPage... children: [{
  path: '/travel/america, component: TravelAmericaPage
}, {
  path: '/travel/china, component: TravelChinaPage}
  ])

2. When might you use a nested route? (other than the provided example)

REVIEW

When you have multiple related pages that are overarched by a single entity. A profile and the main profile page, to the photos page, to a friends list page?

3. Can you pass parameters through nested routes? When might you use them?

Yes for example if you are trying to reference all the data thru an id.. or a particular route.. youd reference it by this.$route.params (which would refer to the route that for example might by path: '/location/:id'). THis could be used to get all of a users data like all (users, pictures, etc.)