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