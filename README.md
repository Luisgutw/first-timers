# FirstTimers
## STEPS:
1. Initialize git repository.
```
git init
```
2. Create a new branch.
```
git branch YourBranchName
```
3. Shift to that branch from master branch.
```
git checkout YourBranchName
```
Make a file in ```contributors``` folder with ```FirstName_LastName.txt```
4. Add all the changes you've made.
```
git add .
```
5. Make a commit message.
```
git commit -m 'your_message'
```
6. Shift to the master branch.
```
git checkout branch master
```
7. Merge everything from your branch to the master branch.
```
git merge YourBranchName
```
8. Get ready to push from your local machine.
```
git remote add <message> https://github.com/CuriousGrids/FirstTimers.git
```
9. Push everything on your forked repository.
```
git push -u <message> master
```
