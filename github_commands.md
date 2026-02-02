# 🚀 GitHub Commands

This guide explains **Git commands step by step**.


---
<br>
<br>


# 🟢 First Time Setup

## Initialize Git Repository

to initialize the project locally on the labtop

```bash
git init
```

---

## Add Files to Git

to let git add all the files you want to commit

```bash
git add .
```

---

## Commit Project

to commit your changes and init the project at the start

```bash
git commit -m "your commit message"
```

---

## Connect Project to GitHub Repository

to make word to use like (orign) instead of writing your project link

```bash
git remote add origin (your project link)
```

---

## Push Project to GitHub

to push your commits to the master branch using orign instead of writing the project link

```bash
git push -u origin master
```

---

# 🔁 Every Time You Make Changes

## Add All Files

to make git add all the files you want to commit

```bash
git add .
```

---

## Commit Changes

to commit your changes

```bash
git commit -m "your commit message"
```

---

## Push Changes

to push your commits

```bash
git push
```

---

# 🛠 Git Commands

## Add Specific File

add the sepcific file to the next commit

```bash
git add (file name)
```

---

## Check Project Status

show all the changes you did

```bash
git status
```

---

## Create Branch

create branch called feature-1

```bash
git branch feature-1
git -b feature-1
```

---

## Create and Switch Branch

create and stand on branch you created

```bash
git checkout -b name
```

---

## List All Branches

list all the branches

```bash
git branch -a
```

---

## Switch Branch

switch to stand on branch called feature-1 locally on device

```bash
git checkout feature-1
```

---

## Update Current Branch

get all the changes of parent branch on the current branch on github (its a short cut for fetch and merge the parent branch to current branch)

```bash
git pull origin (your branch)
```

---

## Delete Branch (Merged)

delete the branch called feature-1 if its already merged

```bash
git branch -d feature-1
```

---

## Delete Branch (Force)

delete the branch called feature-1 even its not merged

```bash
git branch -D feature-1
```

---

## Merge Branch

to merge the branch you are standing on with branch feature-1

```bash
git merge feature-1
```

---

## Merge Parent Branch

when you stand on child (branch) its like updating parent

```bash
git merge master
```

---

## Merge Child Branch to Master

when you stand on master its merge (creating new commit that contain the commits of changes in the b1)

```bash
git merge b1
```

---

## Rebase Branch

when you stand on master this takes copies of the commits of b1 and put it on top of commits of master

```bash
git rebase b1
```

---

## Clone Repository

to clone the repository online

```bash
git clone url
```

---

## Show Remote Repository Info

to see the data of clone repository

```bash
git remote -v
```

---

## Show Commit History

to see tree of logs in graph

```bash
git log --graph
```

---

## Revert Commit

it make new commit dont contain the changes happend in the commit id and keep the commits line

```bash
git revert (commit id)
```

---

## Reset to Commit

it return the header to the commit id and start a new line of commits form it in other meaning it delete commits till commit id you give

```bash
git reset --hard (commit id)
```

---

# 📌 Head

## Head Reference

its word refer to the last commit

```bash
head
```
