# Staging changes to a git repository

When you make changes to a file in your repo git does not automatically keep track of the all of the changes at the same time. This is so you can commit (We'll talk about commits next) them in different batches and going back on changes can be modular.

to add changes to the staging area or, more colloquially, prepare to commit a set of changes you use the command:
```git
git add <file1_name_here> 
```

You can use special characters such as `*` to add multiple files at a time.

If you would like to add all the changes you have made at once you can use the `-A` tag as follows:
```git
git add -A
```