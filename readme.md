# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a version control software that is used through the terminal. It solves the problem of saving and accessing previous iterations of a file, and allows for programmers to collaborate with more ease.

```

## Question 2

Describe the homework submission process.

```
1. We fork the repository on Github
2. We clone that forked repository in whatever directory we want to use in our terminal
3. We checkout a branch that we title to make it clear that it is our homework
4. We open the files in Atom, change them, and finish the homework.
5. We git add the files, we commit them, then push them back up to Github.
6. We then issue a pull request from the Master WDI branch, and include completeness level and comfort level

```

## Question 3

What is the difference between a fork and a clone?

```
A fork creations a carbon copy of a Github repository for our use that doesnt affect the original.
Cloning takes a repository, and gives us access to it on our local machines so that we can make changes to it.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
A relative path is a file path that begins in relation to another file/directory (i.e. not to the home directory) --> an example might be ../wdi_quiz
An absolute path is a file path that begins with the home directory, and continues all the way down to where we are currently --> an example might be ~/Desktop/coding/personal_website

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
var pizza = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function threeArguments (num1, num2, num3) {
  return num1 + num2 + num3;
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
names[2];

```

## Question 9

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
for (i=0; i < names.length; i++) {
  console.log("Hello " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```
