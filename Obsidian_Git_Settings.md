---
layout: default
title: Ρυθμίσεις Git
---

# Obsidian Git Plugin – Ρυθμίσεις

_Ημερομηνία: 2025-08-19 07:54:31_

Ακολουθούν οι ρυθμίσεις που εφαρμόστηκαν για το plugin **Obsidian Git** ώστε να γίνεται αυτόματος συγχρονισμός και αποθήκευση των αλλαγών στο GitHub.

---

## 🔁 Αυτόματες Ενέργειες

- **Auto commit-and-sync interval:** 15 λεπτά
- **Auto commit-and-sync after stopping file edits:** ✅
- **Pull on startup:** ✅
- **Push on commit-and-sync:** ✅
- **Pull on commit-and-sync:** ✅
- **Commit message on auto commit:** `vault backup: {date}`

---

## 🧠 Συμπεριφορές

- Κάθε 15 λεπτά μετά την τελευταία επεξεργασία αρχείου, γίνεται:
  - Commit σε όλα τα αλλαγμένα αρχεία
  - Pull από GitHub
  - Push προς GitHub
- Κατά το άνοιγμα του Obsidian: γίνεται αυτόματα **pull**
- Με κάθε commit-and-sync γίνεται και **push**

---

## 👁️ Εμφάνιση & Status

- **Show Author:** Full ✅
- **Show Date:** ✅
- **Automatically refresh source control on file changes:** ✅
- **Show branch status bar:** ✅
- **Show modified file count in status bar:** ✅

---

## ⚠️ Μη ενεργοποιημένα (σκόπιμα)

- **Split timers**
- **Push/Pull interval**
- **Only staged files**
- **Custom commit prompt**
- **Disable notifications**

---

## 💡 Τι να περιμένεις

- Κάθε αλλαγή που κάνεις θα αποθηκεύεται αυτόματα και θα ανεβαίνει στο GitHub repository.
- Δεν χρειάζεσαι πλέον χειροκίνητες εντολές Git (`git add`, `git commit`, `git push`).
- Είσαι πάντα ασφαλής από απώλεια δεδομένων, αρκεί να έχεις internet!

---

> Επόμενο βήμα: **δοκιμή αλλαγής και αυτόματου sync** με το αρχείο αυτό.
> 	Έγινε η αλλαγή (αυτή είναι), να κάνουμε πρώτα χειροκίνητα το commit και το push από το Command Palete (`Ctrl+P`)


