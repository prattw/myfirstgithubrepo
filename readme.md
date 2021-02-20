# My Git Cheatsheet

## Creating a Git Repo

In the folder, you want to create a repo, do the following

```
git init
```

** Always check that you are not already in a repo** 

---

## Adding Files to staging

Staging is the files that are being tracked to be committed.

Use git status to see which files are untracked(red) or in staging (green)

```
git status
```

Three ways to add files to staging

- add one file at a time `git add <filename>`
- add all files in the repo `git add -A`
- add all files in my current folder with `git add`

---

## Commiting Files to Our Repo

```
git commit -m "some randome text, something descriptive"
```
** If you forget the -m, you'll end up in vim, to exit, type: ":wq"**

---

## Looking at our commit history

```
git log
```

```
git log --oneline
```