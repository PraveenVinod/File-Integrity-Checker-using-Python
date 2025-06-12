# File-Integrity-Checker-using-Python
A simple Python tool to monitor file integrity using SHA-512 hashes.
It can detect file **modifications**, **deletions**, and **new additions**, helping ensure your files haven’t been tampered with.

---

## 🚀 Features

- Generate a baseline of SHA-512 hashes for all files in a directory.
- Check current file hashes against the baseline.
- Logs changes to `integrity_log.txt`.
- Displays file status using color-coded output with `colorama`:
  - 🟢 Unchanged
  - 🟡 New
  - 🔴 Modified
  - 🟣 Deleted

---

## 📁 Folder Structure
File-Integrity-Checker/
├── Files/                    # Directory to monitor
│   └── Subfolder/            # Optional nested folders
├── baseline.txt              # Stores reference hashes (generated)
├── integrity_log.txt         # Logs detected changes (generated)
├── file_integrity_checker.py # Main Python script

