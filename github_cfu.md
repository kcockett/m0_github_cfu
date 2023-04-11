Initialize Git for a new project:  `git init`
Add an updated file to the staging area:  `git add <filename>`
Commit changes with all files in the staging area:  `git commit -m “Initial commit or other message”`
Check on the local status of the current Repository:  `git status`
Check on differences between orginial file vs Staging Area:  `git diff <filename>`
Check the history of Commits:  `git log`
Link current Git to GitHub:  
```
git remote add origin <link>
git branch -M main
git push -u origin main
```
Verify remote connection: `git remote -v`
Remove remote origin if incorrect:  `git remote remove origin`
Push local Staging Area files to GitHub:  `git push`
Download Clone of a Repository to your local machine:  `git clone <code link>`