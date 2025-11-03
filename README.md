# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN, a function is a reusable block of code that performs a task when it is called.

You can think of a function like a microwave. You put something in (input), the microwave does some work, and then you get a result (output). You can use the microwave again whenever you need it — just like calling a function.

Check out this example:

```js
// Arrow function that says hello to someone

const sayHello = (name) => {
  return `Hello, ${name}!`;
};

// Calling the function
console.log(sayHello("Alex")); // Output: Hello, Alex!
```

Here’s what the syntax means:

const sayHello = (name) => {} is an arrow function

name is the parameter — the value the function needs

The curly braces { } form the code block — the instructions that run

The return statement sends back the final result from the function

Writing sayHello("Alex") is how we call/invoke the function so it actually runs