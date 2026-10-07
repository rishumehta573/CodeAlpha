# 🐍 CodeAlpha Internship Projects

This repository contains the projects and tasks completed during my **Python Development Internship at CodeAlpha**.

The internship provided hands-on experience in Python programming, problem-solving, Natural Language Processing, automation, file handling, and building practical applications.

---

## 🎓 Internship Overview

**Organization:** CodeAlpha  
**Domain:** Python Development  
**Internship Type:** Project-Based Internship  

During the internship, I worked on multiple Python projects designed to improve practical programming skills and understand how Python can be used to solve real-world problems.

---

## 📌 Projects Completed

| Task | Project | Technologies |
|------|---------|--------------|
| Task 1 | Text-Based Hangman Game | Python |
| Task 2 | Text-Based Chatbot | Python, NLTK |
| Task 3 | Task Automation / File Organizer | Python, OS, Shutil |

---

# 🎮 Task 1: Text-Based Hangman Game

## 📖 Description

The **Text-Based Hangman Game** is a simple command-line game developed using Python.

The player has to guess a hidden word one letter at a time. For every incorrect guess, the player loses an attempt. The game continues until the player either guesses the complete word or runs out of attempts.

---

## 🎯 Objectives

- Understand Python fundamentals.
- Practice loops and conditional statements.
- Work with strings and lists.
- Handle user input.
- Implement game logic.
- Improve problem-solving skills.

---

## ⚙️ How It Works

```text
Start Game
     ↓
Select Hidden Word
     ↓
Display Word as "_ _ _ _"
     ↓
Ask Player for a Letter
     ↓
Check the Guess
     ↓
 ┌───────────────┐
 │               │
Correct         Incorrect
 │               │
 ↓               ↓
Reveal Letter   Reduce Attempts
 │               │
 └───────┬───────┘
         ↓
Check Win/Loss
         ↓
      Game Ends
