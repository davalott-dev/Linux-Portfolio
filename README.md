🐧 Linux Cohort Manager

This project simulates a simplified, terminal-based student management system for a fictional Coding Bootcamp. Using basic Linux commands, it walks through the creation and manipulation of folders and files that represent cohorts and student records.

It’s designed to showcase foundational Linux command-line skills and simulate real-world administrative logic using only the terminal.

📂 Folder Structure
Coding-Bootcamp/
├── FallCohort/
│   ├── carlos.txt
│   └── emma.txt
├── WinterCohort/
│   ├── alice.txt
│   ├── bob.txt
│   ├── bob_backup.txt
│   └── sophia.txt
└── Waitlist/
    └── sophia.txt   (before being moved)

🔧 Commands Practiced
Command	Purpose
mkdir <folder>	Creates new folders (FallCohort, WinterCohort, Waitlist)
cd <folder>	Navigates into a directory
ls	Lists files and folders
touch <filename>	Creates new student record files
nano <filename>	Opens and edits file contents
cp <source> <destination>	Creates a backup copy
mv -i <source> <destination>	Moves a file (e.g., waitlist → cohort)
rm <filename>	Deletes a file
chmod / chown	Manages file permissions and ownership
grep, wc -l	Searches student data and counts records
🧑‍🎓 Sample Student Record

Example contents of alice.txt:

Name: Alice Smith
Email: alice.smith@example.com
Cohort: Winter
Status: Enrolled

🔒 Permissions Management

To simulate real-world file security:

Restricted cohort folders to certain users with chmod

Reassigned folder ownership to a dedicated instructor user/group with chown

This demonstrates how Linux permissions control access to sensitive files.

⚙️ Automation Script

Created a Bash script (add_student.sh) to streamline student intake:

Adds a new student file into the correct cohort

Auto-populates name, email, cohort, and status

Outputs a confirmation message

Example usage:

./add_student.sh WinterCohort "Sophia" "sophia@example.com"

🧪 Learning Objectives

Practice core Linux file and directory commands

Simulate logic for managing cohorts and student records

Use backup, transfer, and deletion operations on files

Explore permissions and ownership for access control

Automate tasks with a Bash script

Understand how terminal workflows mirror backend admin systems

💻 Tech Used

Linux Terminal / Bash

Ubuntu Virtual Machine

✨ Project Purpose

This project was created to showcase my Linux command-line skills in a practical, easy-to-understand way. It highlights how to:

Navigate and manage the Linux file system

Work with files and directories

Apply permissions and ownership for security

Search and analyze data from the terminal

Automate repetitive tasks with Bash scripting

The project demonstrates how Linux fundamentals can be used to simulate real-world administrative workflows, making it a strong foundation for roles in technical support, system administration, or any environment where Linux proficiency is valuable.
