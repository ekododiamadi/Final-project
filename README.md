# Final-project
Final project of Coding Factory
# 📱 Quiz Master – Android Multiple Choice Quiz App

![Android](https://img.shields.io/badge/Platform-Android-green)
![Java](https://img.shields.io/badge/Language-Java-orange)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue)

---

## 📌 Project Overview
**Quiz Master** is an Android-based multiple-choice quiz application developed as an academic semester project.  
It enables users to participate in timed quizzes, view detailed performance statistics, and compare their scores with others.

The project focuses on clean architecture, modular design, and practical use of Android core components.

---

## 🎯 Objectives
- Design and implement a functional Android quiz application
- Apply RecyclerView, SQLite, and Activity navigation
- Practice structured data modeling and persistence
- Deliver a complete academic software project

---

## 👥 Development Team

- **Kontodiamanti Efrosyni** 

---

## 🚀 Features
- Player registration
- Randomized multiple-choice questions
- Image-based questions
- Countdown timer per question
- Score calculation and statistics
- Persistent storage of results
- Top scores leaderboard

---

## 🔄 Application Flow
1. **MainActivity** – Entry point and navigation
2. **RegisterActivity** – Player registration
3. **SelectAnswerActivity** – Quiz execution
4. **ReviewActivity** – Performance review
5. **TopScoresActivity** – Leaderboard display

---

## 🗄 Database Design (SQLite)
Managed through the `DBHelper` class.

### Tables:
- `questions`
- `answers`
- `players`

Supports full CRUD operations for quiz functionality.

---

## 🧱 Architecture
### Core Classes
- `Question`
- `Answer`
- `Player`

### Adapters
- `AnswersAdapter`
- `PlayersAdapter`

### Utilities
- `Env`
- `RecyclerViewClickInterface`

---

## 🛠 Technologies Used
- Java
- Android SDK
- SQLite
- RecyclerView
- XML Layouts

---

## ⚙️ Installation & How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/quiz-master.git
```

2. Open the project in **Android Studio**

3. Sync Gradle dependencies

4. Run the app on:
   - Android Emulator, or
   - Physical Android device (USB Debugging enabled)

---

## 📸 Application Screenshots
Screenshots demonstrating the user interface and application flow are included in the project documentation.

---

## 📚 Academic Context
This project was developed and demonstrates:
- Android application lifecycle understanding
- UI/UX design principles
- Local data persistence
- Object-oriented programming practices

---

## 📄 License
This project is licensed under the **MIT License**.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies.

---

## 📌 Notes
- Intended for educational use
- Easily extendable with new questions and features
- Clean separation of logic and UI layers
