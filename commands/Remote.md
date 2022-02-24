## git remote

When workign with git, a **remote** is any git repository that is not on the machine that you're working on. The counterpart to this is **local**, or the machine that is is being developed on. 

Take GutHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host you remote repositories. Once sotred remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, that can have different states of the changes are not shared between the two. 

### Adding a remote

A remotw can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local file name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```

### Removing a remote

A remote can be removed with the `git remote remove` command follwed by the name of the remote.

```
git remote remove origin
```

## Resources

- [Git Init Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)