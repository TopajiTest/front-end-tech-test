# Frontend Technical Test

Welcome to The Stars Group technical test for frontend test engineers!

These tasks are open ended but we recommend that you spend no more than a few hours on them.

The site we would like you to test can be found at: https://www.pokerstarssports.uk. Please bear in mind that the site is highly dynamic and both the content and the layout may change over time. You will not need to register an account or log in to the website to complete this test.

### Task 1
Write a number of BDD scenarios using Gherkin to test the following features:
- Adding things to, and removing things from, the bet slip
- Changing the odds format

### Task 2
Create a simple test framework using NPM, Cypress and Cucumber to automate a selection of the scenarios you have created. You should include at least two scenarios from each feature.
- https://www.npmjs.com
- https://www.cypress.io
- https://www.npmjs.com/package/cypress-cucumber-preprocessor


After completing the tasks, please update the README.md file with your scenarios from Task 1 and instructions on how to run your tests, include any information you think is relevant, interesting or useful. The preferred delivery method for this project is via Github but we will also accept a zipped file sent as an email attachment.

**Scenarios from Task-1**
I have created 2 sencarios in cypress and cucumber to automate: 
**1.Add and remove thigns from bet slip**
For this test i have created 2 things
- Step definition file under folder called Odds format. 
- .Feature where you can see cucumber BDD scenarios. 
**2.Changing the odd format**
For this test i have created 2 things
- Step definition file under folder called Odds format. 
- .Feature where you can see cucumber BDD scenarios. 
**Steps to run the cypress:**
You can run cypreess using the command in terminal : npx cypress open > choose the test you want to run from cypress window 
**OR**
You can run the test in cypress individually by using these commands 
- **npx cypress run --spec cypress/integration/BDD/bet_slip.feature --browser chrome**
- **npx cypress run --spec cypress/integration/BDD/OddsFormat.feature --browser chrome**

