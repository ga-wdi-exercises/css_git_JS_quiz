# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a version control system. It is used to solve the problem of tracking changes among many collaborators.

```

## Question 2

Describe the homework submission process.

```
1) Fork the repo from GA's github account.
    - "Forking" a repo copies the repo into my personal github account

2) From the forked repo, click on "Clone" and copy the SSH address.

3) From the terminal, change the directory to the directory you will be working in.

4) Once in that directory, type the following: git clone "paste SSH address". Press enter.

5) Cd back into the directory and open the contents by typing "atom ."

6) Make changes to the file, save, and type "git status" into the terminal.
    - git status shows your untracked files

7) Type "git add ." to add the file to the staging area.

8) Type "git status" again, files should now ready to be committed.

9) Type "git commit -m "comment on the code" "

10) Once committed, you need to push the repo back to the github cloud. Type: git push origin master
    - Type git remote -v to verify

11) Go back to Github and create a pull request
    - Add comfort, completeness, and any comments necessary.  
```

## Question 3

What is the difference between a fork and a clone?

```
Fork: Copies the repo on a remote maching (aka the github cloud)

Clone: Copies the repo onto a local maching (aka the client aka my pc)

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
Absolute path - Tells us exactly where the file or folder is located based on a root starting point.

Relative path - Interpreted as starting from the current working directory.

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
var food = "pizza"
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function add(num1, num2, num3) {
    console.log(num1 + num2 + num3);
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
var names = ["Mary", "Tom", "Sue", "Bobby"]
  for(i in names) {
  console.log("Hello " + names[i])
  }
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1]
```
