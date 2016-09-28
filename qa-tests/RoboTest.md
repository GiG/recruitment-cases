## Introduction
You have been selected to show us how skillfull you are when it comes to automation.
In order to be able to complete this test, you will need to have some knowledge of the following:

- Selenium Webdriver (http://www.seleniumhq.org/projects/webdriver/)
- Protractor (http://www.protractortest.org/#/)
- Page Object Design/Model (https://www.thoughtworks.com/es/insights/blog/using-page-objects-overcome-protractors-shortcomings)
- JavaScript

Also you will require access to the internet and the following details:
- url to test: http://qatest.staging.kaboo.com
- credentials: in the email
- accounts: autosv / autotest1  AND  autouk / autotest1 

As you would have probably seen, there is a file called **kabooPageObject.js** which contains the page object that you will need to use for your implementation. There are different methods and variables, but please feel free to add methods if you require them.

## The exercise
In this task you are required to implement two e2e automated tests using the techonologies, url and accounts mentioned above so that the following BDD
(Behaviour driven development) Scenarios are checked against the url. Note that the purpose of this test is to:

a) Demonstrate your ability to understand Page Object model and take advantage on the E2E testing

b) Build automated tests, given some specs and adapting the Page Object accordingly so that bugs can be flagged

c) Surprise us with you skills with tricks to implement code and find bugs that we didn't even know yet!

d) present the result of the tests in HTML format (any tool you want) for easy reading

**NOTE:** The automation test exists in order to find bugs, so don't be afraid if one of the tests fails. But when it fails, let us know WHERE and WHY :)

*Scenario 1* - Check that the correct payment methods are displayed for Swedish registered users

**Given** a swedish register user logs in (autosv)

**When** clicks on the deposit button (portal/deposit)

**Then** the deposit **methods and order** should be Visa, Neteller, Trustly and Skrill

****

*Scenario 2* - Check that the correct payment methods are displayed for British registered users

**Given** a British register user logs in (autouk)

**When** clicks on the deposit button (portal/deposit)

**Then** the deposit **methods and order** should be Visa, Neteller and Skrill

*****

## Results

Follow the indications in the email
