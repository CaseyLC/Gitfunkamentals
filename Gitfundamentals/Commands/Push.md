# git push 
When you have a [remote](./REMOTE.md) set up you'll need to begin to move [commits](.COMMIT.md) to the remote.
This can be done with the command `git push`.
You can attach a name and branch name to your command to specify where you're pushing to.
```
git [push origin main]
```
This command will push the **main** branch to the reomote called **origin**.
This menas any commits that are in your local will be **pushed** to the reomote.
### UPstream Tracking
Instead of including the  name and the branch your're on every time you casn set local branches to track an upstream branch.
THis means you can tell the bracnh to push to its assigned upstream remote branch by using the command `git push`.
```
git push -u origin main
```
After this command is used, you can just use `git push` it will function the same way.
## Resources
- [Git push Documentation](https://git-scm.com/docs/git-push)
---
[back to home](../README.md)