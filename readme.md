# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a distributed version control system. It simultaneously provides a solution
to back up code as it is written and to allow teams of multiple programmers to work
on one code base simultaneously.

It preserves each stage of development automatically so programmers do not have
to create different versions of code manually as experimental features are developed.

```

## Question 2

Describe the homework submission process.

```
Step 1: Fork the project from a GA repo.
Step 2: Clone the repo from your own github account to your local machine.
Step 3: Complete the homework, commit, and push to your github repo.
Step 4: Create a pull request from your github repo to the GA repo.
```

## Question 3

What is the difference between a fork and a clone?

```
Cloning a repository allows you to make a copy of the repository.

A fork creates a repository in your github profile from the git repo being forked.
Forking a repository is a more streamlined way to eventually pull from your repo
into the original repository.
```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
A relative path is the direction to a file from the current directory.
If the current folder is 'wdi_test' and 'media' is a subfolder containing 'image.jpg',
the relative path to image.jpg is 'media/image.jpg'.

An absolute path is the path from the root folder or the home directory. It does not change
if the current directory changes, only if the file in question is moved.
If wdi_test resides in the root directory, the absolute path to image.jpg described
above is '/wdi_test/media/image.jpg'.

```

## Question 5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
// mark an x in the brackets for the correct answer
[x] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

## Question 6

Create a variable and store the string "pizza" in it

```js
var myVar = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function sumOfThree(x, y, z) {
  return x + y + z;
}
```

## Given the following code:

```js
var names = ["Mary", "Tom", "Sue", "Bobby"];
var clown = {
  name: "Joker",
  evil: true,
  minions: ["Bozo", "Harley Quinn", "Grumpy", "Chuckles"],
  enemy: {
    name: "Batman",
    evil: false,
    minions: ["Robin", "Alfred"]  
  }
};
```

## Question 8

Access the value `"Sue"` out of the `names` array:

```js
names[2]
```

## Question 9

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
for (i=0; i<names.length; i++) {
  console.log('Hello ' + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1]
```
