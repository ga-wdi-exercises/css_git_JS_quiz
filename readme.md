# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a version control tool used to share and track multiple instances of the same file. Without Git, the problem would be that you would have way too many copies of the same exact file. Without the Git technology, each version of the file you save would have to be an exact duplicate of the previous version, so for instance it would look something like this: fileV1 > fileV2 > fileV3 > fileV4final_copy.

```

## Question 2

Describe the homework submission process.

```
1) Access the remote repository on Github
2) Fork the repository to your own personal remote repository on Github
3) Clone it to your local machine via git clone (into a directory that is not already an initialized repo)
4) Work on the homework, save it, git add (to the staging area), git commit
5) Git push your version back to your remote repository on Github
6) Submit a pull request
```

## Question 3

What is the difference between a fork and a clone?

```
A fork copies the repo to your REMOTE repository. Cloning takes the repo down from the remote repository to your local machine.
```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
A relative path is a path that is relative to what directory you are currently in. An absolute path always starts at the highest level, and gets more specific pointing towards the target.
Relative path: cd ../.. would move up two directories from your current working directory
Absolute path: /Users/Tyler/Pictures would access the Pictures directory
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
var foodType = "pizza";
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```

function calculator (num1, num2, num3) {
  return num1 + num2 + num3;
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
for (var i = 0; i < names.length; i++) {
  console.log("hello " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```
clown.enemy.minions[1];
```
