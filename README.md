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
[GITFLOW](https://i.stack.imgur.com/tjJCt.png)
```
1. Use issue tracker IDs in branch names
2. Add a short descriptor of the task
3. Use hyphens as separators
```


What are some good commit message conventions?

```
Good Practices:
Separate subject from body with a blank line
Capitalize the subject line and each paragraph
Use the imperative mood in the subject line
Wrap lines at 72 characters
Use the body to explain what and why you have done something.

What commit message should contain:

Describe why a change is being made.
How does it address the issue?
What effects does the patch have?
Describe any limitations of the current code.
```

For bonus points create a github repo or a gist where you commit your answers to each question in a separate commit.
