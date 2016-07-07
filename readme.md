# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is what we use for version control.  It solves the problem of too many different versions and tracking of a file at one time.
```

## Question 2

Describe the homework submission process.

```
First we fork, then copy clone url, then make a directory in cli, then git init, then
we git clone, open it, do hw, then in cli check git status, then we git we add the files that have been updated, then add a comment via git commit and git push our hw up to the repo, then we git pull and create a pull request and that is where we can write our comfort with the hw and comments about it.
```

## Question 3

What is the difference between a fork and a clone?

```
Fork is when you copy the from the remote repo while cloning is when you copy that repo into the local repo.
```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
A relative path comes from the root directory.  For example,
<img src="sunglasses.png"/>

An absolute path is from your current working directory. Ex.
<a href="file:///home/pam/Documents/GA/2week/register/cash-register/index.html"/>
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

var pizza = 8
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js

var sumIt = function(num1, num2, num3){
  return(num1 + num2 + num3);
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
for(var i=1; i <  names.length; i++){
  console.log("hello", names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown[enemy[minions[1]]]
```
