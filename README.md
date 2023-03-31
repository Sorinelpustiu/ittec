# Basic Git Commands Cheat Sheet
### Here are some basic Git commands that you might find useful in your development workflow.

## User/Email Config
### Configure your username and email address to be associated with your Git commits.
```bash
    itec@git-tutorial:~$ git config --global user.name "Your Name"
    itec@git-tutorial:~$ git config --global user.email "your_email@example.com"
```

## Clone
### Clone a remote Git [repository](./docs/whats-a-repository.md) to your local machine.
```bash
    itec@git-tutorial:~$ git clone <repository-url>
```

## Status
### Shows the current status of changes in the [working directory](./docs/whats-a-working-directory.md)
```sh
    itec@git-tutorial:~$ git status
```

## Log
### Displays all of the commit history in reverse chronological order
```sh
    itec@git-tutorial:~$ git log
```

## Branch
### Create a new [branch](./docs/whats-a-branch.md) or switch to an existing one.
```sh
    itec@git-tutorial:~$ git branch <branch-name>    # Create a new branch
    itec@git-tutorial:~$ git checkout <branch-name>  # Switch to an existing branch
```

## Add
### Add changes to the [staging area](./docs/whats-the-staging-area.md) in preparation for committing.
```sh
    itec@git-tutorial:~$ git add <file>    # Add a specific file
    itec@git-tutorial:~$ git add .         # Add all changed files in the current directory
```

## Commit
### [Commit](./docs/whats-a-commit.md) your changes with a descriptive message.
```sh
    itec@git-tutorial:~$ git commit -m "Your commit message"
```

## Push
### Push your committed changes to a remote Git repository.
```sh
    itec@git-tutorial:~$ git push <remote> <branch>    # Push to a specific remote branch
```

## Pull
### Pull changes from a remote Git repository to your local machine.
```sh
    itec@git-tutorial:~$ git pull <remote> <branch>    # Pull changes from a specific remote branch
```