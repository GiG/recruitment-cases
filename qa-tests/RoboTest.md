## Introduction
You have been selected to show us how skillfull you are when it comes to BDD specs and automation.
In order to be able to complete this test, you will need to have some knowledge of the following:

- BDD (https://en.wikipedia.org/wiki/Behavior-driven_development)
- Selenium Webdriver (http://www.seleniumhq.org/projects/webdriver/)
- Protractor (http://www.protractortest.org/#/)
- Page Object Design/Model (https://www.thoughtworks.com/es/insights/blog/using-page-objects-overcome-protractors-shortcomings)
- JavaScript

Also you will require access to the internet and the following details:
- url to test: http://qatest.staging.kaboo.com
- credentials: in the email
- account usernames: autosv / autouk 
- password: autotest1 

As you would have probably seen, there is a file called **kabooPageObject.js** which contains the page object that you will need to use for your implementation. There are different methods and variables, but please feel free to add methods if you require them.

## The exercise

First of all, we would like to know how analytic your mind is when it comes to writing good and clear BDD specifications from a business requirement written in plain English.

You need to transform the following business requirement into BDD, covering the full functionality of the feature:

```
As a User already playing a game on desktop I want to be able to play 2,
3 or 4 games at the same time in the same tab, as an addition to the default single one;
Check out the designs. A matrix of 1x1 (1 game), 1x2 (2 games) or 2x2 (3 and 4 games) will be created on selecting the mode

  - 3 buttons will be clickable to change between 1 (1x1), 2 (1x2) and 4 (2x2) slots. The selected one is highlighted
  - in case of 2 games they should be placed in slots side by side (1x2)
  - in case of 3 or 4 games the screen should split horizontally and vertically, creating 4 slots (2x2)
  - The game already open should stay open on the top left position when switching between 1, 2 and 4 slots.
  - The user will be able to load 1, 2 or 3 extra games on the slots by clicking on the 
    ADD button (example in design screenshots)
  - Users will be able to alter the game selected by clicking on the <-/-> button that 
    appears when hovering over game
```

![2 ways to add](https://cloud.githubusercontent.com/assets/12252960/19851973/dce8346e-9f60-11e6-8434-a87bb36793a8.png)
![selecting games](https://cloud.githubusercontent.com/assets/12252960/19851980/e84d8d40-9f60-11e6-967d-bbb6dfe462c3.png)


In the second and *BONUS* task you are required to implement an end2end automated test case using the techonologies, url and accounts mentioned above so that the following BDD
(Behaviour driven development) Scenario is checked against the url. Note that the purpose of this test is to:

a) Demonstrate your ability to understand Page Object model and take advantage on the E2E testing

b) Build automated tests, given some specs and adapting the Page Object accordingly so that bugs can be flagged

c) Surprise us with your skills (tricks to implement code) and find bugs that we didn't even know yet!

d) present the result of the tests in HTML format (any tool you want) for easy reading

**NOTE:** The automation test exists in order to find bugs, so don't be afraid if one of the tests fails. But when it fails, let us know WHERE and WHY :)

*Scenario 1* - Check that the correct payment methods are displayed for Swedish registered users

**Given** a swedish register user logs in (autosv)

**When** clicks on the deposit button (portal/deposit)

**Then** the deposit **methods and order** should be Visa, Neteller, Trustly and Skrill

****

## Results

The results could be uploaded into a NEW and public repository in Github and include the link for us.

Follow the indications in the email sent by HR too :)

GOOD LUCK!
