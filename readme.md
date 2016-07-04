# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a set of remote repositories used to track changes to documents/files.

```

## Question 2

Describe the homework submission process.

```
1. Fork the repository to your own directory
2. Clone the SSH to your local directory
3. Add/Edit/Save file(s)
4. git add file(s) then git commit -m "Insert comment here"
5. Push your changes to remote repository (master or branch)
  git push origin master
6. Create a pull request in GA's repository for the assignment

```

## Question 3

What is the difference between a fork and a clone?

```
A fork is simply copying a repository onto your remote directory while a clone copies the repository into a newly created local directory.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
Absolute path is the path that contains the root directory while the relative path points to the current directory.

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
var random = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function sum(a,b,c) {
  var result = a + b + c;
  return result;
}
sum(3,4,5);
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
for (var i=0; i < names.length; i++){
console.log("Hello " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```
