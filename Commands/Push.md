# Git Push 
When you have a [remote](./Remote.md) set up you'll need to begin to move [commits](./commit.md) to the remote. 
This can be done with the command `git push`

You can attach a name and branch name to your command to specify where you're pushing to. 
```
Git push origin main
```
This command will push the **main** branch to the remote called **origin**. 
This means any commits that are in your local will be **pushed** to the remote.

### Upstream Tracking
Instead of including the name of the remote and the branch you're on every time, you can set local branches to track an uptream branch. 
This means you can tell the branch to push to its assigned upstream remote branch by using the command `git push`.

Before doing so, you'll need to use `-u` or `--set-upstream` flag. this can be done on any `git push`.
```
Git push -u origin main
```
After this command is used, you can just use `git push` and it will function the same way.
## Resources
- [Git Push Documentation](https://git-scm.com/docs/git-push) 

---
[Back to home](../Readme.md)
