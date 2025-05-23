# Git Commands to Commit and Push Changes

Based on the examination of your project, it appears that changes were made to the `App.java` file, specifically changing the output message from "Hello World!" to "Hello World new! Date: 23052025!".

To commit these changes to your Git repository and push them to a remote repository, you would need to execute the following Git commands:

## 1. Check the status of your changes
```
git status
```
This will show you which files have been modified.

## 2. Add the modified files to the staging area
```
git add my-app\src\main\java\com\mycompany\app\App.java
```
Or to add all modified files:
```
git add .
```

## 3. Commit the changes with a descriptive message
```
git commit -m "Update Hello World message with current date"
```

## 4. Push the changes to your remote repository
```
git push origin main
```
Note: Replace `main` with your branch name if it's different (e.g., `master` for older repositories).

## Additional Useful Git Commands

### To see the difference between your working directory and the last commit
```
git diff
```

### To see the commit history
```
git log
```

### To create and switch to a new branch
```
git checkout -b new-branch-name
```

### To switch to an existing branch
```
git checkout branch-name
```

### To pull the latest changes from the remote repository
```
git pull origin main
```
