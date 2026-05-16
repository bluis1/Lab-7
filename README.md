# Lab 7

Name: Benedict Luis

## Check Your Understanding (Question problems)

### 1. Where would you fit your automated tests in your Recipe project development pipeline?

I would put the automated tests in a GitHub Action that runs whenever code is pushed. I think this makes the most sense because the tests would run automatically instead of relying on someone to remember to run them manually. This would help catch problems earlier, especially before changes get merged or submitted.

### 2. Would you use an end-to-end test to check if a function is returning the correct output?

No. I would not use an end-to-end test just to check one function’s output. A unit test would be better for that because it focuses on one small piece of code. End-to-end tests are better for testing a full user flow, like loading the page, clicking buttons and checking that the cart updates correctly.

### 3. What is the difference between navigation and snapshot mode?

Navigation mode checks the page right after it loads, so it is useful for seeing how the website performs during the initial page load. Snapshot mode checks the page in its current state, so it is more useful for looking at what is already on the page, such as accessibility issues.

### 4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

Based on the Lighthouse results, three possible improvements would be to optimize the images so the page loads faster, improve accessibility by adding better labels or alt text where needed and reduce unused JavaScript or CSS so the browser does not have to load extra code.





