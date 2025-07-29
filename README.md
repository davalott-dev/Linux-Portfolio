# 🐧 Linux Cohort Manager

This project simulates a simplified, terminal-based student management system for a fictional **Coding Bootcamp**. Using basic Linux commands, the project walks through the creation and manipulation of folders and files that represent cohorts and student records.

It's designed to showcase foundational Linux command-line skills and simulate real-world administrative logic using only the terminal.

---

## 🗂️ Folder Structure

Coding-Bootcamp/
├── FallCohort/
│ ├── carlos.txt
│ └── emma.txt
├── WinterCohort/
│ ├── alice.txt
│ ├── bob.txt
│ ├── bob_backup.txt
│ └── sophia.txt
└── Waitlist/
└── sophia.txt (before being moved)

---

## 🔧 Commands Used

| Command                        | Purpose                                                                |
|-------------------------------|------------------------------------------------------------------------|
| `mkdir <folder>`              | Creates new folders (`FallCohort`, `WinterCohort`, `Waitlist`)         |
| `cd <folder>`                 | Navigates into a directory                                             |
| `ls`                          | Lists files and folders                                                |
| `touch <filename>`            | Creates new student record files (e.g., `alice.txt`, `bob.txt`)        |
| `nano <filename>`             | Opens and edits file contents                                          |
| `cp <source> <destination>`   | Creates a backup copy (e.g., `bob_backup.txt` from `bob.txt`)          |
| `mv -i <source> <destination>`| Moves a file (e.g., `sophia.txt` from Waitlist to WinterCohort)        |
| `rm <filename>`               | Deletes a file from the system (e.g., `chris.txt`)                     |

---

## 🧑‍🎓 Sample Student Record (from `alice.txt`)

Name: Alice Smith
Email: alice.smith@example.com
Cohort: Winter
Status: Enrolled
GitHub Username: alice-dev


---

## 🧪 Learning Objectives

- Practice basic Linux file and directory commands  
- Simulate real-world logic for managing cohorts and student records  
- Use backup, transfer, and deletion operations on files  
- Understand how terminal workflows mirror backend admin systems

---

## 💻 Tech Used

- Linux Terminal / Bash
- Ubuntu Virtual Machine

---

## ✨ Project Purpose

This project was created to showcase my Linux command-line skills. It demonstrates how to use terminal commands to organize data, manage files and folders, and simulate a real-world student cohort system

---
