# GitUndo
Git extension with easy to remember undo commands    
Support this open source repo by using flattr
[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ChristianEngvall&url=https://github.com/crilleengvall/GitUndo&title=GitUndo&language=&tags=github&category=software)       
[GitUndo on Github pages](http://crilleengvall.github.io/GitUndo/ "GitUndo's Homepage")


## Installation
You need to put the file git-undo in the correct path. After that is done, the extension is ready to use.

Start by [downloading the repo](https://github.com/crilleengvall/GitUndo/archive/master.zip)


### Mac/Linux
Copy git-undo file to /usr/local/bin with terminal:    
    `cp <path-to-file>/git-undo /usr/local/bin/`    

### Windows
Copy the git-undo file to your git installation folder:
`C:\Program Files\Git\mingw64\libexec\git-core`    
or     
`C:\Program Files (x86)\Git\mingw64\libexec\git-core`


## Usage
This extension currently has three new commands.

`git undo commit`    
This will undo the latest commit, but the changes in that commit will be left staged.

`git undo stash-apply`    
if you've done a git stash apply, but didn't mean to you can use this command to undo the apply.

`git undo pushed-merge <merge-commit-hash>`    
This will undo a pushed merge. run a git log to get the commit hash.     

![GitUndo logo](http://www.christianengvall.se/wp-content/uploads/2016/04/git-undo-1024x500.png)