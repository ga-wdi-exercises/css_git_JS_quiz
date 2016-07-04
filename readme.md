# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
It solves the problem of version control, for individuals and teams.

```

## Question 2

Describe the homework submission process.

```
Originally: fork, clone, open & edit, git add & commit, pull request. Recently we found out we need to fork, clone, checkout and create a new branch saving our files under firstname_lastname_solution.

```

## Question 3

What is the difference between a fork and a clone?

```
A fork allows you to make a copy of a repo on a different GitHub account and you can make pull requests on it. A clone makes a copy on of a remote repo locally.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
An absolute path points us to a file or folder based on a root starting point (eg /Users/jacahn/wdi/quizzes), while a relative path points us from the current working directory (e.g. ../quizzes)

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
var food = "pizza"
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
var sum = function(num1, num2, num3){
  return num1 + num2 + num3;
}
sum(10,10,10);
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
var names = ["Mary", "Tom", "Sue", "Bobby"]
	for(var i=0; i<names.length; i++){
  	console.log("Hello, " + names[i])
	}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1]
```
