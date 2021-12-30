# Git Commands

<div align="center">
    <img alt="Git" src="./img/git_logo.png" height="80" width="192">
</div>

<hr/>

Create an empty Git repository or reinitialize an existing one
```
git init
```

Add all changes in the next commit
```
git add .
```

Clone a repository into a current directory
```
git clone <url>

// Example 
git clone https://github.com/NijatTagizada/git-commands.git
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