# Git

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