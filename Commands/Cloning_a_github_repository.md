# Cloning_a_github_repository

While the hoops you may have jumped through before with a zip file would work for copying a repo, there is a much easier way. 

First, find a repository on github you would like to clone on to your local computer.

I have made [This one](https://github.com/vyas-research-group/Practice_Repo)for you to practice.

On the main page or the repo you will see a big green "<> Code" button:
![[Clone_A_Repo.png]]
click it and select the SSH section. 
Copy the ssh key (the double stacked squares button to the left of the key copies it to your clipboard).

Next, in your terminal or command line `cd` to the directory you would like the repo to be in and run the following command

```git
git clone Copied_Key_here
```

That is it, you now have that repository in that directory. You can edit it on your local machine.
