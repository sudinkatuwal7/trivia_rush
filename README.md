# 🕉️🧠 Sanskrit & English Trivia Quiz

A **console-based Python quiz game** combining **Sanskrit slokas** with **English general knowledge questions**.  
Test your knowledge, learn Sanskrit, and enjoy fun trivia! 🎉

---

## 📖 Description

This project is a **True/False quiz game** that:
- Helps users **learn and understand Sanskrit slokas**  
- Provides **English trivia questions** to keep the quiz engaging  
- Tracks your **score in real-time**  

It is perfect for:
- Students of Sanskrit and Indian philosophy 🕉️  
- Trivia enthusiasts 🧠  
- Beginners learning **Python** and **Object-Oriented Programming (OOP)** 💻  

---

## ✨ Features

- Alternating **Sanskrit & English questions**  
- Immediate feedback on answers ✅  
- Score tracking after each question 📊  
- Modular design using Python **classes** (`Question` and `QuizBrain`)  
- **Easily extensible**: add more questions in `data.py`  

---

## 🗂️ Project Structure

```bash
sanskrit-english-quiz/
│
├── data.py # Contains all the quiz questions
├── question_model.py # Contains the Question class
├── quiz_brain.py # Contains the QuizBrain class
├── main.py # Main script to run the quiz
└── README.md # This file
```

## 🕹️ How to Play

- A question will appear in the console

- Type True or False and press Enter

- After each question, you’ll see:

   - ✅ Whether your answer was correct

   - 📝 The correct answer

   - 📊 Your current score

- Continue until all questions are answered

- At the end, your final score will be displayed

## 💡Example
```
Q.1: रामः अयोध्यायाः राजा आसीत्। (True/False): True
You got it right!
The correct answer was True.
Your current score is 1/1.

Q.2: The Earth revolves around the Sun. (True/False): True
You got it right!
The correct answer was True.
Your current score is 2/2.
```

## Run the program
```
python main.py
```
## 🎁 Surprise

Here’s a little Sanskrit wisdom for you, hidden as a reward for completing the quiz:
```
ज्ञानेन तु तदज्ञानं येषां नष्टमात्मनः।
By knowledge, one destroys the ignorance of the Self.
```
