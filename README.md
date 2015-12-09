# git-cheats
Git  commands you actually need

#Rename the branch you are currently on
```
git branch -m <NEWBRANCHNAME> 
```
#Merge and delete a branch once finished with local changes

0. Merge a branch into current branch


```
git merge <BRANCHNAME>
```
1. Delete a local branch
```
git branch -d <BRANCHNAME>
```
2. Delete a remote branch
```
git push <REMOTENAME> --delete <BRANCHNAME>
```
