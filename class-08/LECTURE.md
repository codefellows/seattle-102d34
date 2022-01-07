# Class 08: Loops

## Review

Functions:

- Alan: What are some example of things that you would return?
  - any data that another function might need, or another operation requires
    - function sum(number1, number2) => number1 + number2
- Brady: why would you console log in a web site.
  - give develpers a quick way to get feedback.
- Ella: when do we create a new function!
  - every function should have one and only one responsibility, somethings else will require another function.
  - `function addTwoNumbersAndDivide() {}` - split into 2!
- Jeffrey: wrote a function that deletes all the contents.
  - HTML body id = 'body-id'
  - ask the use if they want to delete
    - if true -> replaces the content with nothing.
- Lauren: function toggleColors!!!
  - toggles the background colors.
  - If boolean if true / false, sets backgroound colors and resets booleans.
- Liesl: writing a function that will switch an image.
  - prompt the user with a question
  - switch image depending on answer.
- Nicholas: broke their JS but fixed it!
  - main function!  A big function that does all the things!
    - Ask for a name!  display the name to the user.
- Robert: JS is the brain!  Gives you all the functionality behind the scenes.
  - Googling for getting a start on your functionality.
  - Where do you want to sink your time?

## Loops with Programs

What is a loop?

- a loop is a set of operations (one liner, or a bunch of lines of code, function invocations) that you need to run more than once.
- Purpose:  do things more.
- syntax: they look a lot like function signature, but instead of parameters, we have a couple options
- 3 types: for, while, do while

```js

// for loop

// 3 things that go here, 
// the first is a variable which should be a number. (intializer)
// the second is a condition, when the condition is false the loop with stop (condition)
// the third is an update to the intializer (incrementer) 

// times-- === times = times - 1;

for (let times = 5; times > 0; times--) {
  // the block will run as many times as the loop needs
  console.log('this loop has run ' + times + ' many times');
}


// while loops!
// the parentheses only contain a condition
let likesWatermelons = confirm('Do you like watermelons?");

let times = 0;

// likesWatermelons needs to be 'true' for the inverse to be 'false'
while (!likesWatermelons) {
  // console.log('I will never stop runnint');
  likesWatermelons = confirm('Do you like watermelons?');
}

let answer = prompt('yes or no, do you like watermelons?");

while(answer != 'yes') {
  console.log(num);
  num++;
}

let num = 10;

do {
  console.log(num);
} while (num < 10)

```

## Practice

- Brady: semicolons will matter here :/
