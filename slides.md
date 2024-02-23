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

just add 3 backticks on top and below of the code

---

## Extras

### you can do tables :

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

---

### definition lists :

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

---

## How to automate issue closing

Automating the closing of issues on GitHub can streamline your project's workflow and help maintain a clean issue tracker. This document outlines how to automate the closing of issues through commit messages and GitHub Actions.

---

## How to apply commit

# Git Command Guide with Oh My Zsh Aliases

Simplify your Git workflow using Oh My Zsh aliases. This concise guide covers key actions: committing, amending, squashing, and cherry-picking.

---

## Committing Changes

- Stage files: `git add <file>` // `ga <file>`
- Commit changes: `git commit -m "message"` // `gcmsg "message"`
  gcb feature/cherry-pick

---

## Amending Commits

- Amend the last commit: `git commit --amend -m "New message"` // `gc! "New message"`
- Include new changes and amend without changing the message: `git commit --amend --no-edit` // `gca!`

---

## Squashing Commits

- Squash commits via interactive rebase (replace `N` with the number of commits): `git rebase -i HEAD~N` // `grb -i HEAD~N`

---

## Cherry-Picking Commits

- Apply changes from specific commits: `git cherry-pick <commit-hash>` // `gcp <commit-hash>`

---

## Best Practices

- Commit small, focused changes.
- Write clear commit messages.
- Commit frequently for easier management and troubleshooting.

Leverage Oh My Zsh aliases for a more efficient Git workflow.

---

## How to use git fragments

Git fragments refer to partial SHA-1 hashes that uniquely identify a commit. Using git fragments can streamline operations like `git show`, `git cherry-pick`, `git diff`, and more, by allowing you to reference commits without typing their full SHA-1 hashes.

---

## Understanding Git Fragments

A Git fragment is the beginning portion of a commit's SHA-1 hash. Typically, the first 7 characters are enough to uniquely identify a commit within a repository, but you may use more or fewer characters depending on the size and history depth of your repository.

---

## Finding a Commit's SHA-1 Hash

To find a commit's SHA-1 hash, which you can then shorten to use as a fragment:

1. **List Commits**: Use `git log` to display the commit history.

   - **Command**: `git log`
   - **Oh My Zsh Alias**: `gl` or `glo` for detailed logs.

---

2. **Copy Part of the SHA-1 Hash**: Identify the commit of interest and copy the first 7 characters of its SHA-1 hash.

---

## Using Git Fragments

Here's how to use git fragments in various Git operations:

---

### Viewing a Commit

- **Command**: `git show <fragment>`
- **Example**: `git show a1b2c3d`

### Cherry-picking a Commit

- **Command**: `git cherry-pick <fragment>`
- **Example**: `git cherry-pick a1b2c3d`

---

### Comparing Changes

- **Command**: `git diff <fragment1>..<fragment2>`
- **Example**: `git diff a1b2c3d..e3f4g5h`

## Best Practices

- **Uniqueness**: Ensure the fragment is unique to avoid ambiguities. Git will alert you if the fragment matches more than one commit.
- **Length**: While 7 characters are standard, consider using more in a large repository to avoid collisions.

---

By leveraging git fragments, you can efficiently reference commits without the need to type or copy long SHA-1 hashes, streamlining your Git workflow.

---

## How to fix the last commit message

---

## How to rebase

git rebase -i <sha>

## theme changed
