# What is the working directory?

When you clone or initialize a Git repository, a copy of the repository is created on your local machine, and the files in the repository are stored in a directory called the "Git repository". The working directory is a separate directory that contains a copy of the files from the repository, and it is where you make changes to the files and create new files.

When you make changes to the files in the working directory, Git recognizes those changes and tracks them as "modifications". Git does not automatically track these modifications; instead, you have to explicitly tell Git to stage the changes for committing using the git add command.

Once you have staged your changes, you can create a new commit by running the git commit command. The new commit will contain a snapshot of the changes made to the files in the working directory since the last commit.

It's important to note that the working directory is not the same as the repository directory. The repository directory is where the entire history of the project is stored, including all the commits, branches, and tags. The working directory, only contains the current state of the project, including the modifications that have been made to the files since the last commit.

The working directory in Git is the directory on your local machine where you make changes to your files. Git tracks these changes as modifications, which you must explicitly stage using the git add command before committing them to the repository. The working directory is separate from the [repository directory](./whats-a-repository.md), which contains the entire history of the project.