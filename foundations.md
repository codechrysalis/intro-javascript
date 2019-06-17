# Foundations of Programming

## Lecture Slides

[Slides are here](https://docs.google.com/presentation/d/e/2PACX-1vSMm-b3hSJwjgc4TQe7YnXfVjpdgklt4Ma30sfWULU4jDxt0XplMXLX0vMem6cVBj8LDlbhtLSNpb4s/embed?start=false&loop=false&delayms=3000)

## Exercises

### Basic Requirements

You will only need your Chrome browser with the developer console open for the following activities.

#### Vocabulary

Can you try to define the following in your own words?

- _expression_
- _operator_
- _type_

#### numbers & strings

##### numbers

1. Enter the following expressions, line by line, into your Chrome console. What happens for each?

   ```js
   4 + 10;
   1 * 3;
   12 * 4;
   4 % 2;
   5 % 2;
   5 / 1 - 99;
   5000 * -100 * (1 + 2) * (5 * 6);
   1241 / 9 + 99;
   ```

   **Notice how we want to end all of our expressions with semi-colons.**

1. Based on your work above, what does `%` do?

1. Calculate your age in minutes using the console.

1. The console is getting a little full. Use `clear()` or `⌘ K` to clean things up a little.

##### `string`s

1. In your console, write your name as a `string`!

1. Use the `+` operator to _concatenate_ (join together) two or more
   `string`s, _e.g._:

   ```js
   // Your first and last names as an example
   "Lady " + "Gaga";
   ```

   - Your first and last names (as shown above in the example code snippet)
   - Your favourite singer's full name
   - Code Chrysalis

1. Try the following in your console, line by line. What happens? Fix the errors:

   ```js
   Where are the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?'
   ```

#### Exploration

We want you to get comfortable with actively exploring through code. This often can mean using code that you don't know very much about yet. But don't worry! This is part of the process and you'll learn them in no time.

1. Answer the following questions by coding to test the questions:

   1. What happens when I add a string and a number together?
   1. What if I reverse the order (e.g. number + string)?
   1. What happens if I multiply a number of `5` with a string `5`?

1. Try the following line by line in your console. What do you think adding `.length` does? Try finding the length of other strings.

   ```js
   "hello".length;
   "hello world".length;
   "123".length;
   ```

1. How about the below?
   ```js
   "hello".toUpperCase();
   "HELLO".toLowerCase();
   "hello".endsWith("o");
   "hello".endsWith("e");
   "hello".endsWith("llo");
   "hello".endsWith();
   ```

Can you think of more ways to test it?

`.toUpperCase()`, `.toLowerCase()`, and `.endsWith()` are what we call native methods. They are built-in to the JavaScript language and are available only for strings. We'll learn more about them later on.

1. Bonus question: Where can you find information about the methods used above?

## Homework

- Complete the exercises for this lesson.

# Foundations of Programming

## Objectives

- Understand what a program is
- Understand why JavaScript is a useful programming language for beginners to learn
- Describe and use JavaScript _expressions_
- Describe and use arithmetic _operators_
- Describe and use `number` and `string` data _types_