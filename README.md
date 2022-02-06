# Git Commands

<div align="center">
    <img alt="Git" src="./img/git_logo.png" height="80" width="192">
</div>

</br>

<img src="https://img.shields.io/badge/26%26command-git-red?style=for-the-badge&logo=git">

<hr/>

Create an empty Git repository or reinitialize an existing one
```
git init
```

Clone a repository into a current directory
```
git clone <url>

// Example 
git clone https://github.com/NijatTagizada/git-commands.git
```

Add all changes in the next commit
```
git add .
```

Show commit logs
```
git log
```
Show commit logs short
```
git log --oneline
```
Show commits graphic
```
git lg
```

Unstage a file (keep changes)
```
git restore --staged <filename>

// Example
git restore --staged src/index.html
```

Unstage all files
```
git restore --staged .
```

Show the working tree status
```
git status
```

Downloads commits, branch, objects and refs from another repository
```
git fetch
```

Update the local version of a repository from a remote.
```
git pull
```

Update the current branch from a remote branch
```
git pull <remote name> <branch name>

// Example
git pull origin feature/task
```

Update the current branch from a local branch
```
git pull . <branch name>

// Example
git pull . feature/task
```

Upload local repository content to a remote repository
```
git push
```

Switch branches or restore working tree files
```
git checkout <branch name>

// Example
git checkout feature/task
```

Create the branch on your local machine and switch in this branch 
```
git checkout -b <branch name>

// Example
git checkout -b feature/task
```

List all the remote repositories
```
git remote -v
```

Remove ignored file from repository
```
git ls-files -z --ignored --exclude-standard | xargs -0 git rm --cached
```

Last commit will be remove (keep changes)
```
git reset --soft HEAD~1
```

Revert existing commits with commit hash (Doesn’t change the project history. Doesn't remove commits)

```
git revert <commit hash>

// Example
git revert 9f9069de
```

Creates a new Git repository
```

git init
```

Adding a remote repository
```

git remote add origin https://github.com/yourprofile/repo.git
```

Git stash temporarily shelves (or stashes) changes
you've made to your working copy so you can work
on something else, and then come back and re-apply 
them later on.
```

git stash
```

Apply the same stashed changes to multiple branches
```

git stash apply
```

View a summary of a stash
```

git stash show
```

Delete all of your stashes
```

git stash clear
```