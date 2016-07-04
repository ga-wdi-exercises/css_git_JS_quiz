# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a way for a group to effectively work on the same files. It provides version control for large projects by allowing users to compare versions or undo changes or revert back to a previous version of their code.

```

## Question 2

Describe the homework submission process.

```
Fork and clone assignment from github, complete work, adding and committing as usual, then, when finished, push to github and submit as a pull request to the appropriate repo.

```

## Question 3

What is the difference between a fork and a clone?

```
Forking makes a copy of the repo under your github username, while cloning sends a copy to your local computer.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
answer goes here

```

## Question 5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
// mark an x in the brackets for the correct answer
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[x] Selects all ul's of class dropdown, only if their children are exclusively li's
```

## Question 6

Create a variable and store the string "pizza" in it

```js
var pizza = ["pizza"];
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
var add = function (a, b, c)  {
  return (a + b + c);
};
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
names[2];
```

## Question 9

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
for (var i = 0; i < names.length; i++) {
    console.log("Hello, " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```
