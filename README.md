# Swag Labs (SauceDemo) Test Suite — Manual Testing

This is a personal practice project. I tested [SauceDemo](https://www.saucedemo.com), a demo website made for QA practice, and wrote test cases and bug reports based on what I found.

*Note: Since this is a demo site with no official requirements document, I wrote my own requirements (with some help from AI) based on how the site is expected to behave, then used those as the basis for testing.*

## Purpose

I made this to practice manual testing skills:
- Test scenarios based on requirements, covering positive, negative, and edge cases
- Clear test steps and accurate test data
- Detailed expected and actual results
- Exploratory / ad-hoc testing to find issues outside the written requirements
- Finding and reporting real bugs using the `standard_user` account

## What I Tested

I tested 9 parts of the site, with 73 test cases total:

| Page/Section | What I Checked |
|---|---|
| Login | Valid/invalid login, required fields, locked-out user, some edge cases |
| Sidebar | Menu links |
| All Items | Product list, sorting |
| Your Cart | Cart items, removing items, checkout access |
| Checkout: Information | Required fields, input checks, navigation |
| Checkout: Overview | Order summary |
| Checkout: Complete | Order confirmation |
| Footer | Footer links |
| Security | Trying to access pages without logging in |

Each test case has: Test Case ID, Test Scenario, Precondition, Test Data, Test Steps, Expected Result, Actual Result, and Status.

## Tools Used

- Excel — for practicing writing test cases and bug reports
- Manual testing only, no automation
  
---

This is a personal project for practice, not affiliated with SauceDemo/Sauce Labs.
