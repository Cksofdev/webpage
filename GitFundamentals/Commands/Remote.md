# git remote

When working with git, a **remote** is any git repository that is not on the machine youre working on. The counterpart to this is **local**, or the machine that is being developed on.

Take github for example. While git is the technology that allowsyou to create local repositories, GHithub is the site that will host your remote repositories. Once stored remotley, you can bring that repository back down or share it with others.

**note**: While shared repositories (local and remote) are related and track the same project, they can have different states if changes are mot shared between the two.

### Adding a remote

A remote can bee added with teh 'git remote add' command, followed by the name and location of the remote. The name is  local name, meaning its your label and does not impact the actual remote whatsoever.

'''

git remote add origin https://github.com/ElevenFiftyAcademy/GitFundamentals.git

'''

### Removing a remote

A remote can be removed with the 'git remote remove' command, followed by the name of the remote.

'''

git remote remove origin


'''

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---



[Back to home](.//README.md)