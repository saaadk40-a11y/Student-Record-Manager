# StudentRecordManager

## Project Overview
A menu-driven Python application to manage student records, built using OOP principles. Records are stored in a JSON file, and a summary report is generated after every session.

## Features
- Add a new student record
- View all student records
- Search for a student by ID
- Update student information
- Delete a student record
- Stores data in `students.json` (auto-created if missing)
- Validates input and handles invalid entries without crashing
- Generates `report.txt` after each session with:
  - Total student records
  - Records added / updated / deleted during the session
  - Timestamp of execution

## How to Run
```bash
python main.py
```
Follow the on-screen menu (1–6) to manage records. Choosing **6** saves the report and exits.

## Folder Structure
```
StudentRecordManager/
│── main.py            # menu-driven CLI, program entry point
│── student_manager.py # Student and StudentManager classes
│── students.json       # student data (auto-created)
│── report.txt          # session summary report (created on exit)
│── README.md
```

## Git & GitHub
```bash
git init
git add .
git commit -m "Add Student Record Manager project"
git branch -M main
git remote add origin https://github.com/<your-username>/StudentRecordManager.git
git push -u origin main
```
