# Pushing_to_a_github_repository

**This section assumes you have a [[Remotes_and_git|remote]] and it is called origin.**

When you have made some changes to a repo or a branch you will likely want to share that with the group. To do this you will want to use the pull command.

==**_IT IS HIGHLY ENCOURAGED THAT YOU [[Pulling_from_a_github_repository|PULL DOWN]] THE RESPECTIVE GITHUB REPOSITORY BEFORE PUSHING YOUR CHANGES UP!!!!!_**==

```git
git push origin Respective_Branch
```

If you forget the name of the branches on the github you can check this using:

```git
git branch -r
```

It is good practice to work on a similarly named branch to the one you are pushing to.
If you would like to create a link between a github branch and a local branch you can use the `-u` flag when you push.
```git
git push -u origin Respective_Branch
```

now all you have to do is type `git push` and `git pull` on that working branch and it will push and pull to and from that github branch.

Be careful with this, because you don't want to accidentally push to a branch you don't mean to because you forgot what you linked.