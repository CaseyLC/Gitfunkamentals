# git remote 
When working witrh git, **remote** is any git repository that is not on the machine your're working on. The counterpart to this is **Local**, or the machine that is being developed on.
Take GitHub for example. While git is a technoogy that allows you to creat Local Repositories, GitHub is the site that will host your remote repositories.
Once stored remotely, you can bring that repository back down or share it with others.
**Note**: While repositories (Local and remote) are related and track the samee project, they can have different states if changes are not shared between the two.
### Adding a remote
A remote can be added with the `git remote add` command, followeing by the name and location of the reomte.
The name is a local naem, meaning it's your lab el and does not impact the actual remote whatsoever.
```
git remote add origin https://github.com/ElevenfiftyAcademy/Gitfundamentals.net
```
### Removing a remote
A remote with the `git remote remove` command, followed by the name of the remote.
```
git remote remove origin
```
## Resources 
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)
[Back to home](../README)
