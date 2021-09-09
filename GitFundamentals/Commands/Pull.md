#git pull

Similar to a [git push](./PUSH.md), a 'git pull' will interact with a remote repository. Only this time it will **pull** the changes it does not have from the remote down to the loca repository.

This means any commits made that are on the remote repository will be pulled down and added to th local repository.

This can be done by adding the remote and branch name:

'''

git pull origin main

'''

If there is any upstream connection established, you can use 'git pull' without specifying a remote or branch.

## Resources

-[Git Pull Documentation](https://git-scm.com/docs/git-pull)

---

[Back to home](../README.md)