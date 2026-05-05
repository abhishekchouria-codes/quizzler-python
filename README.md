# quizzler-python

An interactive quiz application built with **Python** and **Tkinter**.  
It fetches real‑time trivia questions from an API, provides a user‑friendly interface, and tracks your score as you play.

---

## Project Overview

### 1. Project Structure
quizzler-python/
   - main.py              # Entry point to launch the app
   - quiz_brain.py        # Handles quiz logic, question flow, scoring
   - question_model.py    # Defines Question class (text + answer)
   - ui.py                # Tkinter GUI interface (buttons, labels, score display)
   - requirements.txt     # Dependencies for easy setup

---

### 2. How to Execute
1. Clone the repository  
   git clone https://github.com/abhishekchouria-codes/quizzler-python.git

2. Navigate into the project folder  
   cd quizzler-python

3. Install dependencies  
   pip install -r requirements.txt

4. Run the application  
   python main.py

---

### 3. Features
- Fetches live quiz questions from the Open Trivia API  
- Interactive True/False interface with instant feedback  
- Score tracking throughout the session  
- Clean and responsive Tkinter GUI  
- Lightweight and beginner‑friendly project  

---

### 4. Technologies Used
- Python 3  
- Tkinter – GUI framework  
- Open Trivia API – fetches real‑time questions  
- Object‑Oriented Programming (OOP) principles  

---

### 5. Controls
- Click **True** or **False** buttons to answer each question  
- Score updates automatically after each response  
- Continue until all questions are answered  
