# Varun's Cheat Sheet 

## Github Repository Setup

In Github, create a new project repository (Example: rust-repo)
Under Code >> Clone command, copy the instruction (Example: git@github.com:chocovarun/rust-repo.git)

## Local Directory Setup

Create local directory: local-code-dir

## Local Command Line Terminal

```bash
    In CLI, execute the following commands:
        cd Documents/GitHub/local-code-dir
        code .
```

## Connect local code directory to Github repostiory

```bash
    In VS Code, open new terminal,
        git init
        git remote add origin git-code-dir (Example: git@github.com:chocovarun/rust-repo.git)
        git status
```

## Simple Rust Program to print Hello World

```bash
    In VS Code local-code-dir, create new file,
        fn main() {
            println!("Hello, world!");
        }
    Save it as rust_file_name.rs
```

## Commit & Check-in code from local directory to Github

```bash
    In the VS Code terminal,
        git status
        git add .
        git commit -a -m "first commit to git repo"
        git push origin master (or branch name)
```

## Compile & Execution Rust Code

```bash
    In the VS Code terminal,
        rustc rust_file_name.rs
        ./rust_file_name
```
