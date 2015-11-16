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

#### Resetting git index after ignoring previously tracked files:

```
git rm -r --cached .
git add .
```