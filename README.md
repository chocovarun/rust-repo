# Varun's Cheat Sheet for Git Usage

## GIT Repository Setup

In Git, create a new project repository (Example: rust-repo)
Under Code >> Clone command, copy the instruction (Example: git@github.com:chocovarun/rust-repo.git)

## Local Directory Setup

Create local directory: local-code-dir

## Local Command Line Terminal

```bash
    In CLI, execute the following commands:
        cd Documents/GitHub/local-code-dir
        code .
```

## Code Development via VS Code

```bash
    In VS Code, open new terminal,
        git init
        git remote add origin git-code-dir (Example: git@github.com:chocovarun/rust-repo.git)
        git status
        git add .
        git commit -a -m "first commit to git repo"
        git push origin master (or branch name)
```
