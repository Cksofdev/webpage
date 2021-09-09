# Gitpush

When you have a [remote](./REMOTE.md) set up youll need to begin to move [commits](./COMMIT.md) to the remote. This can be done with the command 'git push'

You can attach a name and a branch name to your command to specify where youre pushing to.

'''

git push origin main

'''

This command will push the **main** brach to the remote called **origin** This means any commits that are in your local will be **pushed** to the remote.

### Upstream Tracking

Instead of including the name of the remote and the brach youre on every tim, you can set local branches to track an upstream brach. This meansyou can tell the brach to push its assigned upestream remote branch by using the command 'git push'

'''

git push -u origin main

'''

## Resources

- [Git Push Documentation](https://git-scm.com/docs/git-push)

---

[Back to Home](.//README.md)