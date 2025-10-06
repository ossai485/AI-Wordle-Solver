# AI-Wordle-Solver
# 🤖 AI Wordle Solver

A powerful [Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white) project implementing AI-driven Wordle solving strategies with multiple heuristics, batch performance testing, and interactive gameplay.

---

## 📋 Overview

This project implements an AI-powered Wordle game solver capable of:

- Interactive **Player vs AI** gameplay  
- AI vs AI comparisons  
- Batch testing for heuristic performance  
- Real-time strategy visualization  

With multiple heuristics and solver strategies, this project provides insights into optimal word-guessing algorithms.

---

## ✨ Key Features

- 🧠 **Advanced AI Solvers**  
  Supports **Constraint-Based Problem (CBP)** and **A* Optimized Solver** with multiple heuristics.

- 🎯 **Heuristic Strategies**  
  Includes **Entropy**, **Minimax**, **Expected Size**, **Hybrid**, **Positional**, and **Cached** heuristics for optimal guessing.

- 📊 **Batch Performance Testing**  
  Analyze solver efficiency over hundreds of secret words.

- 🖥️ **Interactive UI**  
  Built with **Gradio** for a clean and user-friendly interface.

- 🏆 **AI vs AI Comparison**  
  Test multiple solvers against the same word to identify the most efficient strategy.

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-wordle.git
cd ai-wordle

# Install dependencies
pip install -r requirements.txt

# Run the application
python wordle_ai.py
Note: Requires Python 3.9+ and Gradio library.

🔍 Usage Examples
Play against AI:

Select CBP AI or A AI*

Input your guess

Observe AI's response in real time

Batch Testing Example:

python
Copy code
# Run batch analysis for 100 words
from batch_test import run_batch
run_batch('entropy', num_words=100)
Query Solver Efficiency:

python
Copy code
# Compare heuristics
from heuristics import compare_solvers
compare_solvers(['entropy', 'minimax', 'hybrid'])
🧩 Heuristics Overview
Heuristic	Description	Best Use Case
Hybrid	Switches between entropy & minimax dynamically	Overall best performance
Fast Entropy	Approximate Shannon entropy calculation	High accuracy, moderate speed
Minimax	Minimizes worst-case candidate set	Fast decision making
Expected Size	Minimizes expected remaining words	Lightweight computations
Positional	Entropy calculated per letter position	Position-aware guessing
Cached	Memoized computations for repeated patterns	Batch processing

📊 Batch Performance Analysis
Average guesses to solve a word

Success/failure rates

Time per guess

Heuristic comparison charts

🏗️ Project Structure
bash
Copy code
ai-wordle/
│
├── wordle_ai.py          # Main script with Gradio UI & game logic
├── wordlist.txt          # 5-letter word list
├── heuristics.py         # AI heuristic algorithms
├── batch_test.py         # Batch testing utilities
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── docs/
    └── demo_screenshot.png
🔮 Future Enhancements
Multiplayer Wordle challenges

Difficulty levels for players

AI learning via reinforcement learning

Online leaderboard integration

Enhanced analytics dashboards

👥 Team Members
Your Name – Lead Developer

Collaborator 1 – AI & Heuristic Specialist

Collaborator 2 – UI & Batch Testing

🤝 Contributing
Contributions are welcome!

Fork the repository

Create a new feature branch

bash
Copy code
git checkout -b feature/your-feature-name
Commit your changes

bash
Copy code
git commit -m 'Add your feature'
Push to GitHub

bash
Copy code
git push origin feature/your-feature-name
Open a Pull Request 🙌

