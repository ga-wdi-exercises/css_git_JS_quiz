# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is version control for our projects. A way for us to snapshot a moment of time in our work so that we could go back to that exact moment if we wanted to. For example if we took a snapshot of a moment where our project is working perfectly but then proceed to add more code that ultimately broke our code, we could go back to that snapshot and continue with where we left off.

```

## Question 2

Describe the homework submission process.

```
We are suppose to fork the homework repo so that we have a copy of the repo under our username on github, then we clone the remote repo under our username down to our local machine to start editing content. Once the homework is complete we would add, commit, and push our code back to our repo on github. Finally we submit a pull request to upstream (the original remote repo) so that GA will see our changes.

```

## Question 3

What is the difference between a fork and a clone?

```
When you fork a remote repo you copied the repo onto your account on github. When you clone a repo you will have a copy of the original repo on your local machine.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
Absolute path starts with your root on your local machine and relative path is a path that start relative to the directory the file is currently in.

Absolute path: /Users/vanphan/wdi/exercises/css_git_JS_quiz/

Relative path: css_git_JS_quiz/

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
var food = "pizza"
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers. 

```js
function sum(num1, num2, num3) {
	return (num1 + num2 + num3);
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
for (var i = 0; i < names.length; i++) {
	console.log("Hello " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```


