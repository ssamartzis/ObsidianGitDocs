---
layout: default
title: Troubleshooting
---

# 🛠 Troubleshooting

## ❗ Error: detected dubious ownership

```
fatal: detected dubious ownership in repository
```
Λύση:

```bash
git config --global --add safe.directory "C:/Users/YourUser/Vaults/YourVaultName"
```

## ❗ Δεν ανεβαίνουν τα αρχεία

- Ελέγξτε σύνδεση Internet
- Δοκιμάστε manual `Commit-and-Sync` από Command Palette
- Ελέγξτε αν έχετε ορίσει σωστά το `remote origin`:
```bash
git remote -v
```

