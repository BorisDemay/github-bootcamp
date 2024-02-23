--- { "layout" : "center" }
# git-bootcamp

---

- Made with Spectacle

---

## How to initialise a new repository

```
git init
```

---

## How to review changes

```
git diff // gd
```

---

## How to commit changes

```
git commit -m "commit message" // gcmsg "commit message"
```

---

## Create a new branch

```
git branch newBranch // gcb newBranch
```

---

## Work on a Branch

### What is a Branch?

A branch in Git is simply a lightweight movable pointer to one of these commits.

---

### Why Use Branches?

- Isolate your work: Branches help you switch between versions of your project.
- Experiment without fear: You can make changes on a branch, without worrying about affecting the main project.
- Collaborate more effectively: Each collaborator can work on their own branch, without interfering with others.

---

## Merge branch on main

```
git checkout main
git merge <branchname>
```

---

## Delete a branch

```
git branch --delete <branchname> // gbd <branchname>
```

---

## pushing changes to remote

```
git push // gp
```

---

## Pulling changes from remote

```
git pull // gl
```
