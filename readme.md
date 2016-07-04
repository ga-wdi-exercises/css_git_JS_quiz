# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a tool that helps developers collaborate. It solves the version control problem.
It allows us to track changes of files. It allows us to navigate to different states of a project, to go back to an earlier state or experiment with adding features without risking causing irreversible problems to the code that's already there.

```

## Question 2

Describe the homework submission process.

```
Fork the homework from GA's remote repository: this creates our own remote repository. Clone our own remote repository to make a local repository. Do the homework. Add the changes to the staging area. Commit the changes to the local repository. Push the local repository to the remote repository. Submit a pull request.

```

## Question 3

What is the difference between a fork and a clone?

```
A fork creates a remote repository that is associated with your own github account. It creates a copy that you can push to should you clone it and make changes. A clone makes a repository locally on your computer.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
A relative path describes how to get from the current working directory to another directory or file. An absolute path describes  how to get to a file or directory from the root or home directory. An example of an absolute path:
/Users/marc/wdi/quizzes/css_git_JS_quiz/readme.md
An example of a relative path:
./quizzes/css_git_JS_quiz/readme.md

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
var food = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function add(x,y,z) {
  return x + y + z;
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
for(i in names) {
  console.log("Hello, " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```
