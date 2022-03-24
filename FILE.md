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
```
