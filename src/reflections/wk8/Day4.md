## Day4: Team Capstone

## Daily Journal
Read Working In a Professional Environment > Testing in Vue and answer the following questions

1. What are the three main types of testing we can accomplish in Vue? What does each method provide?

Unit Testing- test indivudal components in isolation
  -choosing framework is crucial
    --Vue
      --- Jest framework
          --unique to taking snapshots of tests which would provide an aleternative means of verifying units

      --- Mocha
        --focused on flexibility 
          able to choose different libraries
              ---spying (Sinon)
              ---assertions(Chai)

        --test features in node anin       the browser

Component Testing
  --mounted to DOM
  --compatible with VUE ecosystem
    --should easily be able to tell error

End-To-End (E2E) Testing
  - validates all code and its cohesiveness
    --multiple browsers.. more reliable and more interactive
      ---debugging more effectively on individual developer basis
            Puppeteer - controlling browser/client controller test runners.. pairs with Jest

            TestCafe

            NightWatch

            Cypress

2. What testing method do you think is the most useful? Why?

Unit Testing:

I think Unit testing to test each individual component is the most beneficial because then you are most easily able to identify if there is a problem within that component

End-To-End Testing:

This would be the other test I would use because being able to test that everything flows and connects properly from start to finish. 

3. What testing method do you think is the least useful? Why?

Component Testing:
I believe relative to the other two methods, since component testing seems specific to Vue and very similar to Unit Testing, which seems a bit more universal, I would probably want to be more comfortable with Unit Testing first and then move to Component Testing if I am going to be using Vue for an extended period. I do love Vue though and the type of framework it provides, so I probably will primarily use it after the program, but I am planning on learning React next to have as another tool/framework to be able to use and be familiar with.