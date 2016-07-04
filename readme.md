# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is one of the most popular version control softwares. It solves the problem of having to save and resave new versions of documents that are in progress. Two key points where it really helps is working with teams and when merging documents. 

```

## Question 2

Describe the homework submission process.

```
Homework assignments are forked off of GA-WDI's Github, onto our own githubs, then they are cloned to our local machines where we make our own edits and then push them back to our own githubs. Then we submit a pull request which is how we "turn it in". 

```

## Question 3

What is the difference between a fork and a clone?

```
Forks are splitting off an identical version of the original code and saving it to our remote/Github. Cloning is copying a repo onto our local machines. 

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
A relative path is one which is only found by referencing the files around it. Like when we are linking a "STYLES.CSS" file in HTML; Styles.css is only relevant to other files in the same directory. 

An absolute path is one that shows the direct heirarchy to the root directory i.e. users/chase/wdi/homework/css_quiz

```

## Question 5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
// mark an x in the brackets for the correct answer
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[X] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

## Question 6

Create a variable and store the string "pizza" in it

```js
var favFood = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers. 

```js
var numCrunch = function (num1, num2, num3) {
return (num1 + num2 +num3);
}
console.log(numCrunch(10, 5, 20)); 

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
for (i = 0; i < names.length; i++) {
console.log(names[i]);
};
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1]

```


