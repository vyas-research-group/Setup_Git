# Merging_a_branch
Merging a branch is when you take changes made to one branch and merge it into another. 
**To start you need to [[Switching_what_branch_you_are_on|switch to the branch]] you want the changes to be applied to.**

Then use the merge command
```git
git merge -m branch_to_merge_from "Merge message here"
```

Merges are a special type of commit, but a commit none the less so it is important to leave a meaningful and descriptive message.
