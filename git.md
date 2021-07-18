## What does Git do?
* Keep track of changes to code
* Synchronises code between different users
* Test changes to code without losing the original copy
* Revert back to older versions of code

## General Commands

Associate your name and email address with your work <br>
```git config --global user.name "username" --global user.email "username@email.com" ```

Show Git config settings<br>
```git config --list```

Create local git repository <br>
```git init ```

Make a local copy of a repository<br>
```git clone <url> ```

Add a change to the staging area<br>
```git add <filename>```

Save changes to a repository as a new version<br>
```git commit -m "message"```

Track changes that have not yet been added<br>
```git diff```

Gain insight into current status of repository <br>
```git status```

Send committed changes to remote repository<br>
```git push```

Retrieve changes from remote repository<br>
```git pull```

Show history of commits and messages<br>
```git log```

Revert code to previous commit<br>
```git reset --hard <commit hash>```

Revert code to version on remote repository<br>
```git reset --hard <context>```

## Branching
A Branch is a version of the repository with its own commit history and current version.

Show all branches of code<br>
```git branch```

Create new branch<br>
```git branch <branch_name>```

Delete branch <br>
```git branch -D <branch_name>```

Switch to new branch<br>
```git checkout <branch_name>```

Merge other branch to current branch<br>
```git merge <other_branch_name>```
