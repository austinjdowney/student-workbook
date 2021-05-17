## Day2: Team CapStones

## Daily Journal
Read Working In a Professional Environment > Github Actions and How to Use Them and answer the following questions

1. What is a Github action and how do they work?

A Github action helps automate one's workflow based on certain variables and/or scripts you have specified in your workflow repsository.

2. What benefits do Github actions provide?

Automates certain events so your workflow is more automated from  to test and all the way thru deployment.

3. What types of trigger actions can a workflow use? What do they do?
<!-- Amazing resource on setting up workflows -->
<!--https://docs.github.com/en/actions/reference/events-that-trigger-workflows-->

All of these triggers are what "trigger" events like a push, pull, fork, etc. type request.

Workflow: You can configure workflows to run for one or more events using the on workflow syntax.

Example using a single event
<!-- Triggered when code is pushed to any branch in a repository -->
on: push

Example using a list of events
<!-- Triggers the workflow on push or pull request events -->
on: [push, pull_request]

Example using multiple events with activity types or configuration
If you need to specify activity types or configuration for an event, you must configure each event separately. You must append a colon (:) to all events, including events without configuration.

on:
  <!-- -Trigger the workflow on push or pull request,
  -but only for the main branch -->
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  <!-- -Also trigger on page_build, as well as release created events -->
  page_build:
  release:
    types: 
    <!-- # This configuration does not affect the page_build event above -->
      - created



Scheduled: Provide a timeline, whether per hour, per day, once per month, to run certain events in that workflow.

Webhooks:
          -Another type is something called a WEBHOOK event. That means some action that GitHub performs, like when somebody stars your repo or when a Wiki page gets created or edited.you can have an event triggered by an EXTERNAL (see below) process outside of GitHub. That's called a repository dispatch event. And you would use that when you want something external to communicate back with your GitHub repo

External: triggered by outside URL ^^^^^ most likely triggered by webhook event (ex. repository_dispatch: when you want to trigger a workflow for activity that happens outside of Github. You can use the GitHub API to Create a repository dispatch event. In your workflow, add

on: repository_dispatch)