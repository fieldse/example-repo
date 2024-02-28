## Questions

- What does a merge do?
- What do you do if you accidentally push unwanted changes to main?
- What happens in this scenario?
  1. You make a branch from main, and make some changes.
  2. In the meantime there's new changes added to main by someone else.
  3. You try to merge your new changes. What happens with the changes the other people made? Do they get lost? Overwritten? Can you even merge yours?
- What happens if you're working on a file in a branch, and then someone makes changes to the same file in main?

## Exercises

### Forks

- [ ] Creating a fork of a repo

### Status

- [ ] Show current state of your local repository with `git status`
- Note: Develop a habit of always doing this, before you do anything in a git repo!

### Git config

- [ ] Show git config
- [ ] Set your global user name in Git config
- [ ] Set your global email in Git config

### Remotes

- [ ] Add a second remote (origin vs upstream)
- [ ] List all remotes
- [ ] Show details of a single remote
- [ ] Remove a remote
- [ ] Push to a specific remote

### Branching

- [ ] Create branch from main
- [ ] Create branch from the new branch
- [ ] Switch to your new branch and back

### Log

- [ ] Reviewing Git log
- [ ] View the log of a different branch
- [ ] Show filenames in git commit log

### Show

- [ ] Show the changes from a specific commit

### Push + Pull

- [ ] Pull changes from remote
  - Note: This is a likely place where you may encounter merge conflicts, when working
    on a shared repository.
- [ ] Pull changes from your `origin` repo
- [ ] Pull changes from `upstream` repo
- [ ] Pull changes from remote, and resolve merge conflicts.

### Checkouts

- [ ] Checking out a specific commit
- [ ] Cherry-pick a change from another branch

### Merges

- [ ] Merging a branch to main locally (without creating a PR)
- [ ] Handling merge conflicts

### Commits

- [ ] Revise a commit message
- [ ] Unstage a single file
- [ ] Stage a single file
- [ ] Unstage all changed files

### Moving files

Q: What happens if you rename a file in your branch, and I make changes to it in my own branch, and then we both push our changes?

### Tags

- [ ] Add a tag to your commit and push the tags to the remote.

### Pull requests

- [ ] Create a pull request from a branch in your fork to an upstream repository

### Removing unwanted things

- [ ] Git rm: remove files from repo
- [ ] Gitignore: add ignore for things you don't want to be checked in

### Reset and reverting

- [ ] Soft reset: Undoing changes but leaving files staged
- [ ] Hard reset: Undoing changes and not leaving staged changes
- [ ] Hard Reset: to a specific commit
  - Q: What happens here if we made a mistake? How do we get back to a good state?
- [ ] Revert a change
- [ ] Entirely reset your branch to the state of a remote branch
