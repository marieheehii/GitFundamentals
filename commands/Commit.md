# git commit

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package the up in what is called a commit.

Commits come woth commit messages that are required for each commit. You add a message to commit command by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictatyes that you should use that message to indicate the changes included in the commit. 

For example, if we have an application we're working on where we just built the abiltiy to register new accounts, then you might have some variation of the following:

```
git add . 
git commit -m "Added register functionality"
```

Then when veiwing the history of the repository, you can pinpoint where the registration funcitonality was added. 

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)