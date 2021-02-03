# Chick-fil-A Coding Challenge
### Prerequisites
* Node.js
* NPM

## Instructions
In the test directory, there is a single test file called `autocomplete-states.spec.js` The objective
is to get all test methods in this file to pass.  The unit test is testing the function
which is also in this file for simplicity.  

Imagine you are building autocomplete
functionality for an input box where a user can start typing to select a state.
Given what the user types, this method returns a list of zero or more states that match
based on the rules below:
1) Match exact abbreviation (Should be case-insensitive)
2) Match start of state name
3) Match any part of state name

For the user to get the most relevant matches, it is important that the matches are
returned in the priority order listed above.  There should be no duplicate states
returned by the method.

To run the tests, from the command line navigate to the directory where this file is located.  Execute the following command.

`npm test`
