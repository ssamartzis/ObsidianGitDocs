---
layout: default
title: Δημιουργία GitHub Repo από Command
---

# 📘 Δημιουργία GitHub Repository από το Command Line

Αυτός ο οδηγός εξηγεί πώς να δημιουργήσεις νέο GitHub repository και να το συνδέσεις με τοπικό φάκελο, **μόνο μέσω εντολών** (`PowerShell`, `Terminal`, `CMD`).

---

## 🧰 Προϋποθέσεις

1. ✅ Έχεις εγκατεστημένο το **Git**  
   ➜ [https://git-scm.com](https://git-scm.com)

2. ✅ Έχεις εγκατεστημένο το **GitHub CLI** (`gh`)  
   ➜ [https://cli.github.com](https://cli.github.com)

3. ✅ Έχεις κάνει login με `gh`:
   ```bash
   gh auth login
   ```

---

## 🚀 Βήματα

### 1. Πήγαινε στον φάκελο του project σου:

```bash
cd "C:\Users\YourName\Documents\ObsidianGitDocs"
```

### 2. Αρχικοποίησε git repo (αν δεν υπάρχει):

```bash
git init
```

### 3. Δημιούργησε νέο GitHub repo:

```bash
gh repo create ObsidianGitDocs --public --source=. --remote=origin --push
```

✅ Αυτό:
- Δημιουργεί repo στο GitHub με όνομα `ObsidianGitDocs`
- Συνδέει τοπικά τον φάκελο
- Κάνει `git add`, `commit` και `push` αυτόματα

---

## 📌 Εναλλακτική χωρίς αυτόματο commit:

```bash
gh repo create ObsidianGitDocs --public
```

Έπειτα κάνεις μόνος σου:

```bash
git remote add origin https://github.com/yourusername/ObsidianGitDocs.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

---

## 🎯 Έλεγχος

Για να δεις ότι όλα πήγαν καλά:

```bash
git remote -v
```

Πρέπει να δείχνει κάτι σαν:

```
origin  https://github.com/yourusername/ObsidianGitDocs.git (fetch)
origin  https://github.com/yourusername/ObsidianGitDocs.git (push)
```
