## git push

WHen you have a [remote](./Remote.md) sey up, you'll need to begin to move [commits](./Commit.md) to the remote. This can be dont with the command `git push`.

You can attach a name and branch name to your command to specify where you are pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. This means any commits that are in your local will be **pushed** to the remote. 

### Upstream Tracking

Instead of including the name of the remote and the branch you're on every time, you can set local branches to track the upstream branch. This means you can tell the branch to push to it's assigned upstream remote branch by using the comand 'git push'.

Before doing so, you'll need to use the `-u` or `--set-upstream` flag. This can be done on any `git push`.

```
git push -u origin main
```

After this command is used, you can just use `git push` and it will funtion the same way. 

## Resources

- [Git Push Documentation](https://git-scm.com/docs/git-push)

---

[Back to home](../README.md)