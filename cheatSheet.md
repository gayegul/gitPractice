Make a new folder
```$ mkdir <FOLDERNAME>```

Navigate into an existing folder (aka change directory)
```$ cd <FOLDERNAME>```

Turn Git on for a folder
```$ git init```

Add remote connections
```$ git remote add <REMOTENAME> <URL>```

Set a URL to a remote
```$ git remote set-url <REMOTENAME> <URL>```

Pull in changes
```$ git pull <REMOTENAME> <BRANCHNAME>```

View remote connections
```$ git remote -v```

Push changes
```$ git push <REMOTENAME> <BRANCH>```

You can create and switch to a branch in one line:
```$ git checkout -b <BRANCHNAME>```

Create a new branch:
```$ git branch <BRANCHNAME>```

Move onto a branch:
```$ git checkout <BRANCHNAME>```

List the branches:
```$ git branch```

Rename a branch you're currently on:
```$ git branch -m <NEWBRANCHNAME>```

Verify what branch you're working on
```$ git status```

Pull in changes from a remote branch
```$ git pull <REMOTENAME> <REMOTEBRANCHNAME>```

See changes to the remote before you pull in
```$ git fetch --dry-run```

Merge a branch into current branch
```$ git merge <BRANCHNAME>```

Change the branch you're working on
```$ git checkout <BRANCHNAME>```

Delete a local branch
```$ git branch -d <BRANCHNAME>```

Delete a remote branch
```$ git push <REMOTENAME> --delete <BRANCHNAME>```

Source: https://github.com/jlord/git-it
