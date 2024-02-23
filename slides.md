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

## <span style="color:blue">Pulling changes from remote

</span>

```
git pull // gl
```

---

## Text

this is some text content

---

## Lists

- item 1
- item 2
- item 3

---

## Image

![alt text](image.png)

---

## Headers and Quotes

'# H1'
'## H2'
'### H3'
'#### H4 '

adding "# ' before a text tags it as a heading

> this is a Quote all you nedd to do is to add '> ' at the beginning of the sentence

---

## code

```
this is a code snipper
```

## just add 3 backticks on top and below of the code

## Extras

### you can do tables :

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### definition lists :

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
