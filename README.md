# EDA Tier 1 Week 2 - Part 2

This week we introduced the programming language of the Internet, JavaScript. With JavaScript we can make our websites smart by adding interactivity and logic.

## Topics Covered

- Variables and Constants
- Conditional statements

## Assignment

As always, start off by forking and cloning this repository from GitHub. Open the code up in VS Code to get started.

> Note that in the future we will not call this out explicitly. We'll assume you already know that is how you start your work.

### Files Provided

- [ ] _describe.js_ (Required Features)

The describe.js file contains prompts for comments and code. It is for practicing explaining code without running it to see what happens. There is no HTML file provided to source in and trigger the JavaScript file to run.

### Instructions

Add comments as instructed into the `describe.js` file.

The file is broken into two sections:

- The first section has you describe written code blocks in your own words.
- In the second section, there is a description of how the code _should_ work, but the code has an issue or "bug" in it for you to find.

**Section 1**  
For questions 1-3, you will narrate what the code is doing. The code here is correct. Just describe in your own words what the code is doing. Pretend it is running in the browser and you need to describe each line as it would run. NOTE: Not all lines WOULD run based on the conditional logic.

Example:

```js
// 0. (EXAMPLE!)
// DESCRIPTION:
// We make a variable called number and set it to 1 as a number.
// Then we increment the number variable. Number is now 2.
// We check if number is greater than or equal to 2. If it is,
// 'yes' will be console.logged.
// OUTCOME:
// 'yes' is what is logged.

// CODE:
/*
let number = 1;

number++;

if (number >= 2) {
  console.log('yes');
}
*/
```

**Section 2**  
For questions 4-6, you are given a description of how the code _should_ behave.
The code given will have something logically incorrect, and your job is to find the issue and make a comment describing what is wrong and how to fix it.

Example:

```
// 0. (EXAMPLE!)
// DESCRIPTION:
// We make a variable called number and set it to 1 as a number.
// Then we increment the number variable. Number is now 2.
// We check if number is greater than or equal to 2. 
// -- it is, so we console.log 'yes'

// CODE:
/*
let number = 1;

// FIX - number-- decrements number, but the instructions ask to increment. 
// Should be number++.
number--; 

if (number >= 2) {
  console.log('yes');
}
*/
```

### Assignment Submission

Check in your repo, then turn in your work via the <a target="_blank" href="https://portal.emergingacademy.org/#/student/assignments">EDA Assignment Portal</a>, as usual and don't hesitate to hit up the Slack channel as needed!

**REMINDER**: Make sure to answer the Slack discussion question!
