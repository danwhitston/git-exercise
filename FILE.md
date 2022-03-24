# FILE.md

## List of commands to generate this repo

I'm updating the list as I go along.

### Commit 0

```sh
git init
touch ./FILE.md
# Add content to FILE
git add *
git commit -m "Commit 0"
# Commit hash was 61825a6
```

### Commit 1

```sh
# Add content to FILE
git add *
git commit -m "Commit 1"
# Commit hash was 35f7d8f
```

### Commit 2

```sh
# Add content to FILE
git add *
git commit -m "Commit 2"
# Commit hash was cee990a
```

### Commit 3

```sh
git checkout -b bug-fix 61825a6
# Add content to FILE
git add *
git commit -m "Commit 3"
# Commit hash was bc17048
```

### Commit 4

```sh
# Add content to FILE
git commit -am "Commit 4"
# Commit hash was b88881b
```

### Commit 5

I'm not counting the merge commit from master to bug-fix as a numbered commit.

```sh
git merge master
git reflog
# Add content to FILE
git commit -am "Commit 5"
# Commit hash was 2b5582a
```

### Commit 6

```sh
# Add content to FILE
git commit -am "Commit 6"
# Commit hash was 7eff28f
```

### Commit 7

```sh
git checkout -b bug-fix-experimental b88881b
# Add content to FILE, hopefully including a merge conflict
git commit -am "Commit 7"
# Commit hash was 74edfc5
```

### Commit 8

```sh
# Add content to FILE
git commit -am "Commit 8"
# Commit hash was 57b06d7
```

### Commit 9

```sh
# Add content to FILE
git commit -am "Commit 9"
# Commit hash was d5f57be
```

### Commit 11

```sh
git checkout bug-fix
git merge bug-fix-experimental
# Fix merge conflicts in editor
git add FILE.md
git commit
# Accept git merge message
# Add content to FILE
git commit -am "Commit 11"
```
