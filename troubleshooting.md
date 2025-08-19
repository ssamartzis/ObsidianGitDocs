# Troubleshooting

## ✅ Δεν γίνεται commit ή push;
- Βεβαιωθείτε ότι έχετε εγκατεστημένο το Git (`git --version`)
- Ελέγξτε τα δικαιώματα φακέλου (.git ownership error)
- Ρυθμίστε το `safe.directory`:
```sh
git config --global --add safe.directory "C:/Users/<user>/Vaults/<vault name>"
```

## 🕒 Δεν συγχρονίζει αυτόματα;
- Ελέγξτε ότι το `Auto commit-and-sync` είναι ενεργό
- Δείτε το log (`CTRL + SHIFT + I`)

## 🔄 Χειροκίνητο Commit & Push
Χρησιμοποιήστε το Command Palette (`Ctrl + P`) και γράψτε `Git: Commit-and-sync`

---
Για περισσότερα, δείτε το αρχείο `Obsidian_Git_Settings.md`
