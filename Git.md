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

#### Resetting git index after ignoring previously tracked files:

```
git rm -r --cached .
git add .
```