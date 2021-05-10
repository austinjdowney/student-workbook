# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Package.json holds all of a workspace's version information, scripts, and dependencies at the root level, so that way all of the information is applied to both the client side and server side.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```

REVIEW

You need package.json at the root level outside of the client and server side so that way all of the dependencies and necessary scripts are applied throughout the project

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```

Npm run build 

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```

.env in the server or env.js in the client side

```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```

You can go to the Heroku dashbard and use the VIEW BUILD LOG to check all of the activity.

You can even use the Heroku CLI to view the most recent logs or even other commands using the heroku logs

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```

You may need to clone the respository from GitHub to local device.. 

-but simply make the changes and commit them to GitHub
-Login to Heroku
-Set the project to remote
-Push to Heroku master branch to deploy updates


```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```

Proper branching to be able to have a deployed branch that handles all of the MVP or product able to de "deployed" to the public as there are updates and new features to be added, but also a branch to be able to work on those features before they are able to be merged with the main branch is crucial to make certain that the working product isn't disrupted until a developer is certain the feature is ready. 

```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```

Code Review should happen before there is any Unit Testing, ideally, but also before anything goes to deployment for quality assurance testing, which I would assume is more E2E testing.

```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```

Merging

```
