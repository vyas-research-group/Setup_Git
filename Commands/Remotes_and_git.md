# Remotes_and_git
In the future you are going to want to Pull changes that might have been made in the github repository back down onto your computer or push your changes up to github. You can use the [[Linking_your_machine_to_github|ssh key you should have generated]]. But typing all of that or copy and pasting it every time you wanted to do that it would be pretty annoying. This is where remotes come in. a github remote is like an alias you set to represent that link.

If you have [[Cloning_a_github_repository|cloned]] a repository there is already a default remote called "origin"
You can check what remotes you have with the following command.

```git
git remote
```

If you want to create a remote:

In the local repo you plan to "Push" and "Pull" following command.

```git
git remote add remote_name Key_to_github_repo
```

The remote name can be anything you like, but typically it is origin.