# Software Engineer Evaluation

This application should be built using the latest version of **React + Typescript**.
You can use [Create React App](https://github.com/facebook/create-react-app) to avoid the unecessary scaffolding and boilerplate.

## Introduction

The purpose of this evaluation is to help us better understand your
ability to follow a simple project plan and deliver a working React
solution. 

We don't want to limit your scope here but would like to see 
how far you take this rudimentary assignment.

You should time box this to ~2 hours from start to finish.

Should you have any questions or concerns regarding the instructions
that follow please reach out to us immediately for help or clarification.

## Project

NASA provides a public API for searching images. The project you
are building will query this API and display results in a SPA (single page web application). 
You do not need an API key to use the service--simply follow the URL pattern below:

`GET https://images-api.nasa.gov/search?media_type=image&q=Jupiter`

### Step 1: Create a Feature Branch

Clone this repo to your local machine and create a feature branch from the
`master` branch by following the steps below (replace `<name>` with 
your lowercased GitHub user name):

`git checkout master`

`git checkout -b <name>-evaluation`

`git push -u origin <name>-evaluation`

## Step 2: Create a GitHub Pull Request and Assign Yourself

Once you have created this new project, make your first commit and push to the 
remote feature branch from Step 1. Go to this repo on GitHub, open a new pull 
request for this feature branch, and 
[assign yourself](https://help.github.com/articles/assigning-issues-and-pull-requests-to-other-github-users).

## Step 3: Reference Images for Design

Take a careful look at each screen in this project. Each screen includes a user story in the 
"description" field (also listed below in this README). 

The images should provide you with enough context around HTML layout, measurements,
CSS, colors and images to complete this evaluation.

## Step 4: Implement User Stories

Please implement the following user stories and ensure that the acceptance
criteria for each story is met by your implementation. User stories begin
with "As a...", and acceptance criteria begin with "Given...".

NOTE: when implementing the sign in page you do not need to actually
authenticate against a real service. Please implement fake sign in 
behavior that takes "someone@example.com" as the email address and 
"password" as the password.

```
As a user
I want to sign in to my account
So that I can search for images

  Given I am on the sign in screen
  When I enter "someone@example.com", "password" and click "Sign In"
  Then I should be routed to the blank search screen

As a user
I want to execute a search query
So that I can search for images

  Given I am on the blank search screen
  When I enter "Jupiter" into the "NASA Image Search" input and click "Go"
  Then I should see a single image search result

As a user
I want to click an image search result
So that I can see the large format image from that search result in a modal dialog

  Given I see a single image search result
  When I click on the search result
  Then I should see the large format image from that search result in a modal dialog

As a user
I want to click the close button on the large format image modal dialog
So that I no longer see the modal dialog

  Given I see a large format image modal dialog
  When I click the close button on the modal dialog
  Then the modal dialog should close
  And I should see a single image search result
```

## Step 5: Request a Code Review

When you have completed your implementation of the user stories
push your final commit to your pull request feature branch and
request a code review from PSP.

## Questions?

Please contact us immediately if you have any questions about this
evaluation project, or encounter any issues getting set up. We are
happy to help.

Thanks!
