# Git Best Practices.

Display graph of all commits.
```sh
git log --graph --all --oneline
```

Create a new git instance
```sh
git init
```

Stage files
```sh
git add README.md
```

Commit files
```sh
git commit -m "first commit"
```

Adding remotes
```sh
git remote add origin git@github.com:pedramphp/git-best-practices.git
```

Pushing to a remotes
```sh
git push -u origin master
```


rebase: add all commits on the feature branch to the end of master branch
Note: it always needs to happen locally on your feature branch.
Common in open source projects, easier to read.
```sh
git checkout feature-branch
git rebase master
```
