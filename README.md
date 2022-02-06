# Git Commands

<div align="center">
    <img alt="Git" src="./img/git_logo.png" height="80" width="192">
</div>

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

Remove ignored file from repository
```
git ls-files -z --ignored --exclude-standard | xargs -0 git rm --cached
```

Last commit will be remove (keep changes)
```
git reset --soft HEAD~1
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

Upload local repository content to a remote repository
```

git push
```

Switch branches or restore working tree files
```

git checkout branchName
```

Create the branch on your local machine and switch in this branch 
```

git checkout -b branchName
```