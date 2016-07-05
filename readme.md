# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a Version Control System.  It allows developers to collaborate over the internet.  Git allows developers to store versions of their work from their local directory to a cloud based directory.

```

## Question 2

Describe the homework submission process.

```
1. We fork and clone the wdi repo to our own github user repo.
2. We use git clone to put the repo on our local directory.
3.  We finish the homework via atom.
4.  We create a new branch and then merge to our master branch.
5.  We submit a pull request and submit our modified repo to the class repo.
6.  We judge our comfort and completeness level. Lastly, leave any comments we may have.

```

## Question 3

What is the difference between a fork and a clone?

```
Fork brings a public or shared repo to our own github user repo.
Clone brings a repo to our local/home directory.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
An absolute path describes the location of a file or directory from a fixed, universally recognized starting point, example ~/Users/alexanderpholland/pics/dog.jpg

 A relative path describes the location of a file or directory from the current location or some other locally defined starting point, e.g. pictures/dog.jpg

```

## Question 5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
// mark an x in the brackets for the correct answer
[] Selects all li's which are directly inside a ul of class dropdown (children)
[x] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

## Question 6

Create a variable and store the string "pizza" in it

```js

var food = "pizza";

```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js

function addNums (num1, num2, num3) {
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


for (var i=0; i<names.length; i++){
  console.log("Hello +" + names[i]);
}


```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js

clown.enemy.minions[1];
```
