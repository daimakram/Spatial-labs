# Git skills

Can you create a fork of this `gist` and push it to your `gist`? `Yes`

How would you make sure that your work doesn't conflict with someone else's code when working on the same project in a team?
```
First, checkout the branch you want to merge into using "git checkout".
Then, use 
git merge <branch to merge from>

example, we want to merge " login" feature in main branch. 
we will first checkout in main
git checkout main
then do,
git merge feature/login
(since, feature directory contains login)
```
Write the command for merging someone's code?
```
First, checkout the branch you want to merge into using "git checkout".
Then, use 
git merge <branch to merge from>

example, we want to merge " login" feature in main branch. 
we will first checkout in main
git checkout main
then do,
git merge feature/login
(since, feature directory contains login)
```

Can you install and run the following library on your system? https://github.com/geelen/git-smart `Yes`

What are some good branching conventions?

What are some good commit message conventions?

For bonus points create a github repo or a gist where you commit your answers to each question in a separate commit.


# Screening Questions for ReactJS

Will the following component work? If not why not?

```js
import React from "react"

const myComponent = ({name}) => (
  <div>Hi there! {name}</div>
);
```

Can you rewrite the above component to use `state` instead of `prop`?

```js
// your solution
// ....
```


Why is the following react code wrong? What would be the correct way to set the `state`?

```js
//Wrong
this.state.message = 'Hello world'
```

What's wrong with the following ReactJS code?

```js
<button onclick={activateLasers}>
```

What are inline conditional expressions? Give an example.

```js
// inline conditional render example:
```

When would you use a `key` prop and why is it important?

```js
// example of using the key prop
```

What are `refs`? Why would you use them?

What are hooks? Give an example of a component that uses hooks?

```js
// component with hooks
```

# NodeJS/Serverside

What is a RESTful API and how would you document it?

Can you write simple server in Node.js that returns Hello World?

```js
// your solution
```

Name some techniques for avoiding callback hell?
