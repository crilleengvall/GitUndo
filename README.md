# GitUndo
Git extension with easy to remember undo commands

## Installation
Copy git-undo file to /usr/local/bin with terminal:    
    `cp <path-to-file>/git-undo /usr/local/bin/`    
now the extension is ready to use

## Usage
This extension currently has three new commands.

`git undo commit`    
This will undo the latest commit, but the changes in that commit will be left staged.

`git undo stash-apply`    
if you've done a git stash apply, but didn't mean to you can use this command to undo the apply.

`git undo pushed-merge <merge-commit-hash>`    
This will undo a pushed merge. run a git log to get the commit hash.