# git commit
The command `git commit` will take all tracked changes (items added with[git add](./Add.md)) and package them up them up in what is called commit.
Commits come with commit messges that are required for each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes
A commit message _can_ be anything, but  best practice dictates that that you should use that message to indicate the cahnges included in the commit.
For example, if we have an application we're working on where we just built out the ability to register new accounts, the you might have some varaition of the following:
```
git add .
git commit -m "Added register functionality"
```
Then when viewing the history of a git repository , you can pinpoint where the registration functionlity was added.
## Resources 
- [Git Commit Documentation](https://git-scm.com/docs/git-commit)
---
[Back to home](../README.md)