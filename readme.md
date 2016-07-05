# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a version control system that is mainly used in software development. It allows to organize and control versions or revisions of a project that we are working on.

```

## Question 2

Describe the homework submission process.

```
We fork the repo to our own Github, then clone it so we can work on it locally. After we are done, we add and commit, and push it back to our Github. Finally we do a pull request in the master repo.

```

## Question 3

What is the difference between a fork and a clone?

```
Fork duplicates the repo in our own github, while clone makes a copy that we can work on locally.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
Relative paths are links to sources relative to the local directory we are working at, while absolute paths are links to pages and content that are somewhere in the internet. For instance, if there is a file called Photo1.jpg that I want to link, a relative path would be /images/photo1.jpg. An absolute path would be a whole website address: http://www.website.com/images/photo1.jpg.

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

```
var dinner = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function add(num1, num2, num3) {
  console.log (num1 + num2 + num3);
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
names[2]
```

## Question 9

Write a for loop such that you say hello(using `console.log`) to each name in the `names` array

```js
var text = "";
var i;

for (i=0; i<names.length; i++) {
    text += "Hello " + names[i] + "<br>";
    console.log (text);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.minions [2]
```
