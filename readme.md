# Week 1 Quiz!!
Fork and clone this repo and follow the directions below.

For the following quiz, there will be a series of questions or directions followed by `answer goes here`. You'll replace `answer goes here` with your answer between the triple back ticks ( \`\`\` ) Then submit this updated file as a pull request to this repo.

## Question 1

What is Git, what problem does it solve?

```
Git is a form of version control that allows you to take snapshots of projects and files within an initialized git repository. It allows a user flexibility as far as revision, backup, and accessing past snapshots. It also allows for collaboration in the form of branch and merge requests where projects can be worked on independently of a 'master' branch. By being able to branch off from and merge into the master branch git allows for a smoother development process that keeps an updated and functional master branch separate from experimental newly made branches.

```

## Question 2

Describe the homework submission process.

```
Go to the linked repository on git-hub! Make sure you fork this repo so that you're committing and uploading to a version you have permissions for. Clone this repo so that it is available on your local machine. Make the read-me changes as specified in the assignment. Add the files with 'git add .' command to the staging area. "git commit -m'this is a messages'"" so that they are now committed to the working head. "git push origin master" so that the commit is reflected on your version of the repository on github. Visit the repository on the git-hub page and create a pull request for the master repo that you forked your from. This will allow the instructors to view what you have created and the changes you've made in order to give you feedback.
```

## Question 3

What is the difference between a fork and a clone?

```
Forking a repo creates a new repo under your own github account this is the version that will live in the cloud. Cloning a forked repo will create the local repository that lives on your computer and has an origin address of the forked repo you created from git-hub.

```

## Question 4

Describe the difference between a relative and absolute path, give an example of each.

```
any path that references the root directly is an absolute path eg ~/Users/Chris/Desktop. This will allow you access to what ever you're pathing to. A relative path is one that references the current directory eg if you're in the directory Chris, Chris/desktop/index.html will access the index.html file.

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
var myPizzaString = 'pizza';
```

## Question 7

Write a function that takes 3 arguments(numbers) that calculates and returns the sum of all three numbers.

```js
function threeArguments(num1, num2, num3){
    return num1+num2+num3;
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
for (i=0;i<names.length;i++) {
    console.log("Hello " + names[i]);
}
```

## Question 10

Access the value `"Alfred"` out of the `clown` object

```js
clown.enemy.minions[1];
```
