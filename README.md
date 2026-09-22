# PDF Password Cracking — NetworkWalks Tools

**Topic:** Recovering passwords from locked PDF files using online hash extraction & cracking tools

---

## 📋 Overview

This lab documents the process of extracting password hashes from locked PDF files and cracking them using the **NetworkWalks** online toolset — a hash calculator and password cracker designed for training/lab exercises.

---

## 🛠️ Tools Used

| Tool | Purpose | Source |
|------|---------|--------|
| NetworkWalks Lab PDFs | Sample locked PDF files for the exercise | [Password Cracking Lab Task](https://networkwalks.com/password-cracking-with-networkwalks-tools-project-task-lab/) |
| Hash Calculator | Extracts the password hash from a locked PDF | [networkwalks.com/hash-calculator](https://networkwalks.com/hash-calculator/) |
| Password Cracker | Cracks the extracted hash to recover the password | [networkwalks.com/password-cracker](https://networkwalks.com/password-cracker/) |

---

## 🔐 Process

### 1. Download Target Files
Downloaded the locked/password-protected PDF files provided as part of the NetworkWalks lab task.
<img width="1366" height="737" alt="Screenshot_2026-09-22_15-03-22" src="https://github.com/user-attachments/assets/6824fddc-5251-4d1b-ab9a-381dcb06c911" />

### 2. Extract Hashes
Uploaded each locked PDF, one by one, to the **Hash Calculator** tool to generate its corresponding password hash.
<img width="1366" height="768" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/44a50c4f-456a-4b2f-b446-76ac0cee5bdc" />

### 3. Crack the Hashes
Submitted each extracted hash to the **Password Cracker** tool to recover the original plaintext password.
<img width="612" height="624" alt="Capture1" src="https://github.com/user-attachments/assets/32b563e5-89ad-47b2-b672-14054ceb1385" />

### 4. Unlock & Verify
Used the recovered passwords to open each PDF and confirm successful decryption.
<img width="1366" height="768" alt="Screenshot (87)" src="https://github.com/user-attachments/assets/b35b03b1-917a-4cb9-baf0-6f64af4e333d" />
<img width="1366" height="768" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/9679dffc-16c9-4a39-81f1-36a67d514b72" />


---

## ✅ Results

| # | PDF Hash (truncated) | Recovered Password |
|---|------------------------|---------------------|
| I | `$pdf$4*4*128*-1060*1*16*55d1a5c1...` | `password1` |
| II | `$pdf$4*4*128*-1028*1*16*0853f2cd...` | `password1` |
| III | `$pdf$4*4*128*-1028*1*16*34eb542e...` | `1qaz2wsx` |

> Full hash strings are available in the lab notes; truncated here for readability.

---

## 📌 Key Learnings

- How PDF encryption hashes are structured and extracted for offline/online cracking.
- Practical exposure to weak, commonly-used passwords (`password1`, `1qaz2wsx`) and why they're trivial to crack.
- Workflow for using web-based hash extraction and cracking tools as an alternative to local tools like John the Ripper.
- Reinforced the importance of strong, unique passwords and proper PDF encryption settings.

---

## ⚠️ Disclaimer

This exercise was performed using **sample lab files provided by NetworkWalks** for educational/training purposes only. These techniques should only be applied to files and systems you own or are explicitly authorized to test.

---
## 👤 Author
- Gaurav Bharty
