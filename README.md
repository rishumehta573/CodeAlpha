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


# 🤖 Text-Based Chatbot using Python

A simple **rule-based text chatbot** developed using Python during my **CodeAlpha Python Development Internship**.

The chatbot interacts with users through the command line and responds to different types of messages using predefined conversation patterns. It uses the **NLTK `Chat` utility** for pattern matching and the **PyJokes** library to generate jokes.

---

## 📌 Project Overview

The objective of this project is to develop a simple conversational chatbot that can understand common user inputs and provide appropriate responses.

The chatbot can:

- 👋 Respond to greetings
- 🧑 Identify the user's name
- 😊 Respond to basic mood-related messages
- 🤖 Tell the user about itself
- 💬 Explain what it can do
- 😂 Tell jokes
- ❓ Handle unknown or unrecognized inputs
- 👋 End the conversation when the user enters `quit`

This project demonstrates the basic concept of **rule-based conversational AI** using Python.

---

## 🎯 Objectives

The main objectives of this project are:

- Learn the basics of chatbot development.
- Understand pattern-based text matching.
- Use Python libraries for conversational applications.
- Implement predefined responses for different user inputs.
- Learn how NLTK's `Chat` utility works.
- Integrate an external library for dynamic joke generation.
- Build an interactive command-line application.

---

## 🛠️ Technologies Used

| Technology / Library | Purpose |
|----------------------|---------|
| **Python** | Main programming language |
| **NLTK** | Chatbot and text pattern matching |
| **nltk.chat.util.Chat** | Handles rule-based conversations |
| **reflections** | Handles conversational reflections |
| **PyJokes** | Generates programming jokes |
| **Regular Expressions (Regex)** | Matches user input patterns |
| **Command Line** | User interaction |

---

## 📦 Libraries Used

The project uses the following Python libraries:

```python
import nltk
from nltk.chat.util import Chat, reflections
import pyjokes


# ⚙️ Task Automation with Python

A Python-based **File Organization Automation Tool** developed as part of my **CodeAlpha Python Development Internship**.

This project automates the process of organizing files in a folder by identifying their file types and moving them into appropriate folders such as **Images, Documents, Videos, Audio, and Others**.

The project demonstrates how Python can be used to automate repetitive file-management tasks and improve productivity.

---

## 📌 Project Overview

Managing a folder containing hundreds of files manually can be time-consuming and inconvenient.

This project provides a simple solution by automatically scanning a selected directory, identifying files based on their extensions, creating required folders, and moving the files into their respective categories.

For example:

```text
Before:

Downloads/
├── photo.jpg
├── resume.pdf
├── video.mp4
├── song.mp3
├── assignment.docx
└── notes.txt
