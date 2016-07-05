# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is basically a version control system that allows us to create, manage, share (etc) projects and all the projects' versioning through repositories (locally and remotely). It solves a lot of problems you run into when you're working on a big project: i.e. it makes file size storage more manageable because it only tracks what has changed from one commit(version) to the next - which makes backtracking through changes easier as well. It also makes sharing ownership (without losing control) easier with the process of branching (low risk) and hosting everyone's contributions in a neutral, remote place vs. on one person's system.

```

## Question 2

Describe the homework submission process.

```
To submit homework assignments that have been hosted on GA's GitHub, you have to go to the repository page, fork it so that a copy is hosted on your own personal GitHub repo, then clone the link from your personal repo. Using terminal, navigate to a new folder and clone your url down. Open the files, add or make changes. Add, commit, push your changes back up to your personal repo. Back in the browser, submit a pull request from your repo, which will appear as a request listed in the original GA repo. Pull request should include title, comfort/completeness level, and description.

```

## Question 3

What is the difference between a fork and a clone?

```
A fork is when you copy a remotely hosted repo from someone else's GitHub repository so that you have an identical remote repo you can control and manipulate on your personal GitHub account. A clone is different because it uses the link of your remote repo to host that repo locally on your file system.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
An absolute path starts from a root and provides the complete path. A relative path defines its path in relation to wherever the user is currently working, like using nearby landmarks. An example of absolute path: /Users/OldGreg/projects/homework/final.txt  an example of relative path: projects/homework/final.txt

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
var lunchFood = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
var calculate = function(num1,num2,num3) {
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
for(var i = 0; i < 4; i++)
console.log("hello " + names[i]);
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```
