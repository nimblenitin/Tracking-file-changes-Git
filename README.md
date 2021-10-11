# Tracking-file-changes-Git

Steps to track the changes in a file in Git-

Steps include:
- Updating a file from the repository
- Tracking the changes in the file
- Adding the file to the staging area
- Comparing git commits to track file changes

```

1. Update an existing file in a local git repository-
$ git status
$ vi <yourfilename>
$ git status

2. Track the changes in the file-
$ git diff <yourfilename>

3. Use the following command to check the recent log of commits with --oneline flag-
$ git log --oneline

4. Use the git commit command to commit the changes from the staged area-
$ git commit -m "Fourth commit: Modified the txt file"
$ git push -u origin main

5. Use the git log command again to see the latest commit
$ git log --oneline

```



