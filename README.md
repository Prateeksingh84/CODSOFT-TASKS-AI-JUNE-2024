# 💻 Codsoft Internship - Python Mini Projects

This repository includes **three Python-based beginner-friendly projects** created as part of the **Codsoft Internship Tasks**. Each project explores different areas of programming, including natural language processing, AI-based game logic, and recommendation systems.

---

## 📌 Project 1: Rule-Based Chatbot

### 📄 Description

A basic text-based chatbot that responds to user inputs using **predefined rule sets** and **regex pattern matching**.

### 🚀 Features

- Responds to greetings, questions about itself, and simple queries.
- Uses regular expressions for pattern matching.
- Simulates a basic conversation flow.

### 🔧 Technologies

- Python
- Regular Expressions (`re` module)

### 💡 Sample Interaction

```
Welcome to SRM chatbot! Type 'bye' to exit.
You: HI
Chatbot: Hello! How can I assist you today?
You: WHAT IS YOUR NAME
Chatbot: I'm Codsoft's chatbot. What's yours?
You: BYE
Chatbot: Goodbye! Have a great day!
```

---

## 📌 Project 2: Movie Recommendation System

### 📄 Description

A **user-based collaborative filtering** recommendation system using **cosine similarity** to suggest movies to users based on similar user profiles.

### 🧠 Algorithm Used

- Cosine Similarity (via Scikit-learn)
- Weighted rating aggregation
- Filtering based on unrated movies

### 🔧 Technologies

- Python
- NumPy
- Pandas
- Scikit-learn

### 💡 Sample Output

```python
Recommendations for User1: ['Avatar']
```

### 🧪 Data Sample

```python
user_ratings = {
    'User1': {'Matrix': 5, 'Titanic': 3, 'Inception': 4},
    'User2': {'Matrix': 3, 'Titanic': 4, 'Inception': 2, 'Avatar': 5},
    'User3': {'Matrix': 4, 'Titanic': 5, 'Avatar': 3},
    'User4': {'Titanic': 5, 'Avatar': 4},
}
```

---

## 📌 Project 3: Tic-Tac-Toe Game with AI (Minimax + Alpha-Beta Pruning)

### 📄 Description

A **Python terminal-based Tic-Tac-Toe game** where a human plays against an **AI opponent** powered by the **Minimax algorithm with Alpha-Beta pruning**.

### 🧠 AI Logic

- Minimax Algorithm
- Alpha-Beta Pruning Optimization
- Dynamic evaluation of game board

### 🔧 Technologies

- Python
- Basic terminal I/O
- Minimax Algorithm

### 🕹️ How to Play

- Human is **'X'**, AI is **'O'**
- Input format: `Enter row and column (0, 1, or 2):`

### 💡 Sample Game Output

```
Welcome to Tic-Tac-Toe!
You are 'X' and the AI is 'O'.
 | | 
-----
 | | 
-----
 | | 
Enter row and column (0, 1, or 2): 0 0
...
Congratulations! You win!
```

---

## 🧠 Learnings

✅ Basics of NLP with regex  
✅ Cosine similarity & collaborative filtering  
✅ Game AI using Minimax with pruning  
✅ Pythonic class design and modularity

---

## 🛠️ Setup & Run

### Install Required Libraries (for Project 2)

```bash
pip install numpy pandas scikit-learn
```

### Run Chatbot

```bash
python chatbot.py
```

### Run Movie Recommendation System

```bash
python recommendation_system.py
```

### Run Tic Tac Toe with AI

```bash
python tic_tac_toe_ai.py
```

---

## 📬 Author

**Prateek Singh**  
Intern @ Codsoft  
Made with ❤️ and Python!

---

