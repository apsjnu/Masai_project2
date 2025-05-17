# Masai_project2
Library management system
# 📚 Library Management System (Console-Based)

A simple Python-based Library Management System that uses CSV files as a mini-database. This project supports librarian and member roles, book lending/return logic, password hashing, and overdue tracking.

---

## 🚀 Features

### 👩‍💼 Librarian
- Add / Remove books
- Register members
- Issue / Return books
- View overdue loans

### 👨‍🎓 Member
- Search catalogue (by title or author)
- Borrow books
- View loan history

---

## 🗂️ Project Structure

```bash
library_system/
├── data/
│   ├── books.csv
│   ├── members.csv
│   └── loans.csv
├── models.py
├── storage.py
├── auth.py
├── librarian.py
├── member.py
├── utils.py
├── main.py
├── tests/
│   └── test_issue_return.py
