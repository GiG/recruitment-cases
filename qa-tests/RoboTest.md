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
- password: Autotest1 

As you would have probably seen, there is a file called **kabooPageObject.js** which contains the page object that you will need to use for your implementation. There are different methods and variables, but please feel free to add methods if you require them.

## The exercise

First of all, we would like to know how analytic your mind is when it comes to writing good and clear BDD specifications from a business requirement written in plain English.

You need to transform the following business requirement into BDD, covering the full functionality of the feature:

```
As a user I want to see my reward history (the ones I have obtained and claimed) in the Freebies Vault Section
the functionality would be:
  
  - When user claims a reward (token) the "Your history" section will be displayed
  - Each token will display 1 characteristic thumbnail 
  - Only the last 8 tokens will be displayed
```
This is the design template:
https://github.com/betit/recruitment-cases/blob/master/qa-tests/reward%20H.png


In the second and *BONUS* task you are required to implement an end2end automated test case using the techonologies, url and accounts mentioned above so that the following BDD
(Behaviour driven development) Scenario is checked against the url. Note that the purpose of this test is to:

a) Demonstrate your ability to understand Page Object model and take advantage on the E2E testing

b) Build automated tests, given some specs and adapting the Page Object accordingly so that bugs can be flagged

c) Surprise us with your skills (tricks to implement code) and find bugs that we didn't even know yet!

d) present the result of the tests in HTML format (any tool you want) for easy reading

**NOTE:** The automation test exists in order to find bugs, so don't be afraid if one of the tests fails. But when it fails, let us know WHERE and WHY :)

*Scenario 1* - Check that the correct payment methods are displayed for British registered users

**Given** a British registered user logs in (autouk / Autotest1)

**When** clicks on the deposit button (thrills / flappybird)

**Then** the deposit **methods and order** should be [Mastercard, Maestro, Visa, Paysafecard, Neteller and Skrill]

****

## Results

The results could be uploaded into a NEW and public repository in Github and include the link for us.

Follow the indications in the email sent by HR too :)

GOOD LUCK!
