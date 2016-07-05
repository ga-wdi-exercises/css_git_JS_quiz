# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a tool that allows developers to work together, or view their own work at various commit points.
It solves the problem of version control, making it easier to experiment with various ideas while having
a stable, saved, point of code progression to return to.
```

## Question 2

Describe the homework submission process.

```
After forking and cloning the assignment, work is saved as a series of commits. A pull request is then used to
submit this branch of commits to the original assignment repo.
```

## Question 3

What is the difference between a fork and a clone?

```
A clone downloads the repo, but a fork creates a identical repo under the forker's github. A fork allows a user to make changes that can be submitted by a pull request to be added to the master branch of the repo.
```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
An absolute path begins at the root directory, while a relative path starts only at the current directory.
Absolute: D:\documents\generalassembly.document
Relative: ..\images\image2.jpg
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

```
var nonsense = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```
function adder(num1, num2, num3){
  return (num1 + num2 + num3)
}
```

## Given the following code:

```
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

```
names[2];
```

## Question 9

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```
for (i=0; i< names.length; i++){
  console.log('Hello '+ names[i]);
  }```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```
clown.enemy.minions[1];
```
