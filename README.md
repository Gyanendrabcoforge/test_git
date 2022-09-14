# test_git
git virsion-------
which git
git init
git add <file/directory name #1> <file/directory name #2> < ... >
git add .
This will "stage" all files to be added to version control, preparing them to be committed in your first commit.
For files that you want never under version control, create and populate a file named .gitignore before running
the add command.
Commit all the files that have been added, along with a commit message:
git commit -m "Initial commit"
This creates a new commit with the given message. A commit is like a save or snapshot of your entire project. You
can now push, or upload, it to a remote repository, and later you can jump back to it if necessary.
If you omit the -m parameter, your default editor will open and you can edit and save the commit message there.
Adding a remote
To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored
at.
The git remote add command takes two arguments:
1. A remote name, for example, orig
