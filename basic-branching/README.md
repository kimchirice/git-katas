# Git Kata: Basic Branching
## Setup:

1. Run `./setup.sh` (or `.\setup.ps1` in PowerShell)

## The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git.
Hint: `git checkout` will make you switch from one branch to another.

1. Use `git branch` to see the two branches that are relevant for this exercise
1. What branch are you on?
1. Use `git branch mybranch` to create a new branch called _mybranch_
1. Use `git branch` again to see the new branch created.
1. Use `git checkout mybranch` to switch to your new branch.
1. How does the output from `git status` change when you switch between the _master_ and the new branch that you have created?
1. How does the workspace change when you change between the two branches?
1. Make sure you are on your _mybranch_ branch before you continue.
1. Create a file called `file1.txt` with your name.
1. `Add` the file and `commit` with this change.
1. Use `git log --oneline --graph` to see your branch pointing to the new commit.
1. Switch back to the branch called _master_.
1. Use `git log --oneline --graph` and notice how the commit you made on the _mybranch_ branch is missing on the _master_ branch.
1. Make a new file called `file2.txt` and commit that file.
1. Use `git log --oneline --graph --all` to see your branch pointing to the new commit, and that the two branches now have different commits on them.
1. Switch to your branch _mybranch_.
1. What happened to your working directory? Can you see your `file2.txt`?
1. Use `git diff mybranch master` to see the difference between the two branches.

## Useful commands
- `git checkout`
- `git checkout -b`
- `git log --oneline --graph`
- `git branch`
- `git diff`
