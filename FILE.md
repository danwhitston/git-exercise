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
```

### Commit 3

```sh
git checkout -b bug-fix 61825a6
# Add content to FILE
git add *
git commit -m "Commit 3"
# Commit hash was bc17048
```

### Commit 4conflict

```sh
# Add content to FILE
git commit -am "Commit 4"
# Commit hash was b8attempting to create a merge conflict8881
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
```
