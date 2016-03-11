# Git

#### Git branches list with tracking info

```
git branch -vv
```

#### Git config

Checking:

```
git config --list
```

User config path:

```
~/.gitconfig
```

#### Git log

A nice short decorated log with graph:

```
git log --graph --oneline --decorate
```

#### List all tracked files

```
git ls-tree --full-tree -r HEAD
```

#### Resetting git index after ignoring previously tracked files:

```
git rm -r --cached .
git add .
```

#### Adding files by glob pattern

```
git add "*.gradle"
```

#### Deleting pushed commit

```
git reset HEAD^ --hard
git push <remote> -f
```

#### Renaming recent commit

```
git commit --amend -m "New message"
// if commit is pushed
git push <remote> -f
```

#### Git flow cheatsheet

http://danielkummer.github.io/git-flow-cheatsheet/

#### Gitignore

https://www.gitignore.io/