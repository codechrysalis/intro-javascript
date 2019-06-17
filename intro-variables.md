# Intro to Variables

## Objectives

- Be able to declare variables and assign values
- Know when to use `var`, `let`, or `const`

## Lecture Slides

[Slides here](https://docs.google.com/presentation/d/e/2PACX-1vS3IfJZl5CaZ6XjQsojAb99GA2vjfg7HSYZ8USwgBF0DGkSHUwxuSY17tBseAh3ip2YwK0IHIwPL_l5/embed?start=false&loop=false&delayms=3000)

## Vocabulary

- _immutable_ - cannot change; cannot mutate

## Paired Activity

For each of the following code blocks, use a whiteboard or pen and paper to reason about what the value of `x` is supposed to be on the last line with your partner.

Once you have arrived at a conclusion that you are comfortable with, enter the lines into a console and check your answer. Was your hypothesis correct? If not, understand why (talk with a classmate, or ask for help).

```js
var x = 5;
x + 10;
x; // => ???

var x = 17;
x = (x + 1) / 2;
x * 4;
x; // => ???

var x = 5;
var y = 20;
x = y;
y = y + 7;
x; // => ???

var x = 10;
var y = 5;
x = x * 4 - 3;
x + 17;
x = x + y;
x; // => ???
```

## Exercises

Create a copy of the `_lesson-templates` folder called `variables-intro`.

Inside of `script.js` complete the following exercises:

### Basic Requirements

#### Focused Practice

All of these exercises use the techniques from the this lecture.

1. Create variables called `name`, `age`, `currentTask` and `isProgrammer` and assign them values so your test cases print what you expect! Use the keywords `let` and `const` instead of `var` (you will need to think about which variables should be "immutable").

   ```js
   // Examples
   const school = "Code Chrysalis";
   console.log(school); // should print "Code Chrysalis"
   let week = 1;
   console.log(week); // should print "1"

   // Your code
   console.log(name); // should print your name
   console.log(age); // should print your age
   console.log(isProgrammer); // should print "true"
   console.log(currentTask); // should print "1"
   ```

1. Re-assign `currentTask` to 2.

   ```js
   console.log(currentTask); // should print "2"
   ```

1. Compute some basic geometry. You may need to use Google to remember the formulas.

   ```js
   // Compute and store the area of a square
   const squareSideLength = 2;
   // Your code here.

   console.log(squareArea); // should print "4"

   // Compute and store the area of a rectangle
   const rectangleBaseLength = 3;
   const rectangleHeightLength = 4;
   // Your code here.

   console.log(rectangleArea); // should print "12"

   // Compute and store the area of a triangle
   const triangleBaseLength = 4;
   const triangleHeightLength = 5;
   // Your code here.

   console.log(triangleArea); // should print "10"
   ```

### Medium Requirements

#### Challenging Practice

These exercises may use techniques that were not covered in this lecture.

1. More basic geometry. Some of your answers might be a _little bit_ different than the expected values. Don't worry. They should just be _close_ to the expected values.

   ```js
   // Compute and store the circumference and area of a circle
   const circleDiameter = 10;
   // Your code here.

   console.log(circleCircumference); // should print something close to "31.41592653589793"
   console.log(circleArea); // should print something close to "78.53981633974483"
   ```

1. Without directly reassigning the values, swap the values of `a` & `b` so that your test cases print what you expect.

   Hint: you will need to create another variable to store data temporarily.

   ```js
   let a = "B";
   let b = "A";
   ```

   ```js
   console.log(a); // should print "A"
   console.log(b); // should print "B"
   ```

1. Exponential growth. Change the value of a _single variable_ to contain the powers of two.

   ```js
   let value = 1;

   // you do something to value

   console.log(value); // should print "1"

   // you do something to value

   console.log(value); // should print "2"

   // you do something to value

   console.log(value); // should print "4"

   // you do something to value

   console.log(value); // should print "8"

   // you do something to value

   console.log(value); // should print "16"

   // you do something to value

   console.log(value); // should print "32"

   // you do something to value

   console.log(value); // should print "64"
   ```

1. String concatenation. Concatenate different variables to display the desired result.

   ```js
   const firstName = 'your first name';
   const lastName = '???';
   const city = '???';

   console.log(???); // should print something like "Hello, my name is Yan Fan. I live in Tokyo."
   ```

### Advanced Requirements

For these exercises, you may need to use techniques that we haven't covered in class.

1. Declare a function called `counter` that, when invoked, always `console.log`s a number that is one more than the previous invocation.

   ```js
   // hint: you may need to do something here

   function counter() {
     // your code here
   }

   counter(); // => 1
   counter(); // => 2
   counter(); // => 3
   // etc.
   ```

1. Declare a function called `isOdd` that, when invoked, `console.log`s whether or not the given number is odd.

   ```js
   function isOdd(givenNumber) {
     // your code here
     // should print "Yes, it's odd" or "No, it's even", depending on the given number.
   }
   ```

## Homework

- Complete the `Basic Requirements` for this lesson.
- Complete the `Additional Reading`.

### Additional Reading 📖

1. [DevTools](http://javascript.info/devtools)
1. [Eloquent JavaScript Chapter 1 - Values](http://eloquentjavascript.net/01_values.html)
1. [JavaScript for Cats: The Console](http://jsforcats.com/#basics)
1. [JavaScript for Cats: Strings](http://jsforcats.com/#strings)
1. [JavaScript for Cats: Values](http://jsforcats.com/#values)
