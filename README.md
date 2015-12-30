# git-cheats
Git  commands you actually need

#Rename the branch you are currently on
```
git branch -m <NEWBRANCHNAME> 
```
#Merge and delete a branch once finished with local changes

 Merge a branch into current branch

```
git merge <BRANCHNAME>
```
Delete a local branch
```
git branch -d <BRANCHNAME>
```
Delete a remote branch
```
git push <REMOTENAME> --delete <BRANCHNAME>
```
Find changes over the history of a file
```
git log --follow -p -- file
```
