# 🛡️ File Integrity Checker using Python

**Developed by: _[Praveen Vinod]_**

⚠️ _This project is intended for educational and research use only. Ensure that it is used ethically and within authorized environments._

---

## 📌 Overview

The **File Integrity Checker** is a simple yet effective Python tool that uses **SHA-512** hashing to monitor the integrity of files in a directory. It helps detect:

- 🟡 **Newly added files**
- 🔴 **Modified files**
- 🟣 **Deleted files**
- 🟢 **Unchanged files**

By comparing current file hashes with a saved baseline, it ensures your files haven’t been tampered with or unintentionally altered.

---

## 🔍 Key Features

- ✅ Generate SHA-512 hash baseline of all files in a folder
- ✅ Detect changes by comparing current hashes to the baseline
- ✅ Logs results to `integrity_log.txt` for future auditing
- ✅ Uses **`colorama`** to color-code file status in terminal output

---

## 📁 Folder Structure
File-Integrity-Checker/
- Files/                    # Folder to monitor
 │Subfolder/            # Nested files supported
- file_integrity_checker.py # Main Python script
- baseline.txt              # Stores SHA-512 hashes (auto-generated)
- integrity_log.txt         # Logs detected changes (auto-generated)

