# Clas 07: Programming

## How do you put on a jacket?

define a function for putting on a jacket:

- What jacket? What is a jacket?

- make sure jacket is unzipped.
- make sure jacket is right side up.
- make sure jacket is not inside out.
- put right arm through right sleeve.
- pull right jacket lapel up to right shoulder.
- put left arm through left sleeve.
- pull left lapel to left shoulder.
- put zipper nub into zipper clasp.
- pull zipper up to chin.

## Functions

Any js operation / set of operations that should repeated. Provides a syntax for turning operations into a repeatable "thing".

- JS function signature

```js

// "function" keyword, followed by a name for the function, followed by parenthesese, followed by a pair of curly brackets.

// this is just define a variable
let wordsVariable = 'Is it morning yet?';

// function defined with the words parameter.
function calulateTime(time) {
  // the things the function needs to do go here.

  if (time < 12) {
    return 'it is morning';
  } else  {
    return 'it is the evening';
  }
}

// invoke functionName
functionName('Is it morning yet'); // our argument

```

- parameters / arguments
  - Arguments are the values that are passed into the function on 'invocation' / 'call';
  - Parameter is a variable we define in the parentheses of our function signature.
  - the argument is the value that is assigned to the parameter.
- return values
  - stops your function from running.

## Additional js scripting topics

- expressions : a line of code or js operations that evaulates to some value.
```js

  let words = 'name';
  if (words > 10) {
    console.log('works');
  } else {
    console.log('doesnt work');
  }

  let isAwesome = true;

  if (!isAwesome) {
    console.log('You are awesome');
  }
```

- operators:
  - <: less than
  - >: greater than
  - +: increment one (plus)
  - -: decrement one
  - &&: logical AND
  - ||: logical OR
  - !: logical NEGATION / INVERSE
    - `!=`
  - `==`: is equal to ( only compares value)
  - `===`: strictly equal to. (compares value and type)

```js

let number = 10;

if (number < 10 && number > 5) {
  console.log('you number is between 5 and 10');
} else {
  console.log('your number is not between 5 and 10');
}


// We created this function to compare a number.
function compareNumber(number) {
  if (number < 10 && number > 5) {
    console.log('you number is between 5 and 10');
  } else {
    console.log('your number is not between 5 and 10');
  }

  return 1;
}

function makeASandwich() {

  let bread = prompt('what bread would like?');
  let meat = prompt('what meat do you like?');
  let cheese = prompt('what cheese do you like?');

  return 'Here is a sandwich with ' + bread + ', ' + meat + ', ' + cheese + '.';
}


// we need to use the `document` object to change any HTML.

```
