# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
version control system. Helps track your work and the different versions you make, allows multiply people to work on the same program.

```

## Question 2

Describe the homework submission process.

```
fork that shit (to your github). clone that shit (to your local repo). work on that shit (on your local repo). push that shit(to you remote repo on github). then pull request that shit(from your github which lets the github user from which you originally forked the repo from, know that you have made changes and they should take a look).

```

## Question 3

What is the difference between a fork and a clone?

```
fork copies a repo from someone else github to your own(remote repo). Cloning a repo copies that repo to your computer(local repo)

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
absolute path - is the location of a file or directory beginning from the root directory and containing all subdirectories leading to the current working directory and or file.
relative path - is the location of a file or directory beginning from your current location, where ever that maybe.

```

## Question 5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
// mark an x in the brackets for the correct answer
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

## Question 6

Create a variable and store the string "pizza" in it

```js
var andy = 'pizza';
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function addThree(a, b, c) {
  return a + b + c;
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
for (i = 0; i < names.length; i++) {
  console.log("hello", names[i]);
};
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```


