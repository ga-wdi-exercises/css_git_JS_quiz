# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a program created and utilized to address the problem of version control in coding and development projects. By saving records only of changes made - as opposed to copies of the files or the files themselves - it allows for efficient tracking of those changes, even across multiple "branches" of work.

```

## Question 2

Describe the homework submission process.

```
1. Fork the files in the remote repository from GA's account to yours (which creates a copy that you can manipulate and work on in your own account)
2. Clone the files from your remote repository into your local repository using the 'git clone' terminal command
3. Do the homework, saving locally as appropriate
4. Commit the changes to your local Git repository using 'git commit -m'
5. Push the changes to your remote Github repository (usually called 'origin') on the appropriate branch (usually 'master') using 'git push'
6. Submit a pull request to GA's account on Github

```

## Question 3

What is the difference between a fork and a clone?

```
A fork copies files between Github repos (e.g. from GA's remote repo to my remote repo).
A clone copies files between a remote repo to a local repo (e.g. from my Github repo to my local repo).

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
An absolute path describes the location of a file or directory from a fixed, universally recognized starting point, e.g. ~/Users/tedwards1884/personal/coolest_pic_ever.jpg

A relative path describes the location of a file or directory from the current location or some other locally defined starting point, e.g. website_assets/coolest_pic_ever.jpg

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

var dinner = 'pizza';

```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js

function addThree(num1, num2, num3) {
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
  console.log("Hello + " + names[i]);
};

```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js

clown.enemy.minions[1];


```
