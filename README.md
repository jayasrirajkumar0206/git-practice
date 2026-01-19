# Git Practice – Basic Concepts (Short)

## Goal

Practice core Git commands step‑by‑step.

---

## 1. Create Repo

```bash
mkdir git-practice
cd git-practice
git init
```

---

## 2. Create & Track File

```bash
echo "Hello Git" > file1.txt
git status
git add file1.txt
git commit -m "Add file1"
```

---

## 3. Modify File

```bash
echo "Learning Git" >> file1.txt
git diff
git add file1.txt
git commit -m "Update file1"
```

---

## 4. View History

```bash
git log --oneline
```

---

## 5. Add Another File

```bash
echo "Second file" > file2.txt
git add .
git commit -m "Add file2"
```

---

## 6. Ignore File

```bash
echo "temp.txt" > .gitignore
echo "temp" > temp.txt
git add .gitignore
git commit -m "Add gitignore"
```

---

## 7. Undo Basics

Discard changes:

```bash
git checkout -- file1.txt
```

Unstage file:

```bash
git reset file1.txt
```

---

## Key Commands

* `git status` – check state
* `git add` – stage files
* `git commit` – save snapshot
* `git diff` – see changes
* `git log` – history
