Of course. Here is the fully formatted README.md file based on the content you provided.

# 🤖 AI Wordle Solver

[](https://www.python.org/)

A powerful Python project implementing AI-driven Wordle solving strategies with multiple heuristics, batch performance testing, and interactive gameplay.

-----

## 📋 Overview

This project implements an AI-powered Wordle game solver capable of:

  - Interactive **Player vs AI** gameplay
  - AI vs AI comparisons
  - Batch testing for heuristic performance
  - Real-time strategy visualization

With multiple heuristics and solver strategies, this project provides insights into optimal word-guessing algorithms.

-----

## ✨ Key Features

  - 🧠 **Advanced AI Solvers** Supports **Constraint-Based Problem (CBP)** and **A\* Optimized Solver** with multiple heuristics.

  - 🎯 **Heuristic Strategies** Includes **Entropy**, **Minimax**, **Expected Size**, **Hybrid**, **Positional**, and **Cached** heuristics for optimal guessing.

  - 📊 **Batch Performance Testing** Analyze solver efficiency over hundreds of secret words.

  - 🖥️ **Interactive UI** Built with **Gradio** for a clean and user-friendly interface.

  - 🏆 **AI vs AI Comparison** Test multiple solvers against the same word to identify the most efficient strategy.

-----

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-wordle.git
cd ai-wordle

# Install dependencies
pip install -r requirements.txt

# Run the application
python wordle_ai.py
```

**Note:** Requires Python 3.9+ and the Gradio library.

-----

## 🔍 Usage Examples

**Play against AI:**

1.  Select "CBP AI" or "A\* AI".
2.  Input your guess.
3.  Observe AI's response in real time.

**Batch Testing Example:**

```python
# Run batch analysis for 100 words
from batch_test import run_batch
run_batch('entropy', num_words=100)
```

**Query Solver Efficiency:**

```python
# Compare heuristics
from heuristics import compare_solvers
compare_solvers(['entropy', 'minimax', 'hybrid'])
```

-----

## 🧩 Heuristics Overview

| Heuristic | Description | Best Use Case |
| :--- | :--- | :--- |
| **Hybrid** | Switches between entropy & minimax dynamically | Overall best performance |
| **Fast Entropy** | Approximate Shannon entropy calculation | High accuracy, moderate speed |
| **Minimax** | Minimizes worst-case candidate set | Fast decision making |
| **Expected Size** | Minimizes expected remaining words | Lightweight computations |
| **Positional** | Entropy calculated per letter position | Position-aware guessing |
| **Cached** | Memoized computations for repeated patterns | Batch processing |

-----

## 📊 Batch Performance Analysis

  - Average guesses to solve a word
  - Success/failure rates
  - Time per guess
  - Heuristic comparison charts

-----

## 🔮 Future Enhancements

  - Multiplayer Wordle challenges
  - Difficulty levels for players
  - AI learning via reinforcement learning
  - Online leaderboard integration
  - Enhanced analytics dashboards

-----

## 👥 Team Members

  - **Dishank Vyas**
  - **Krishna Shetty** 
  - **Pal Soni** 

-----

## 🤝 Contributing

Contributions are welcome\!

1.  Fork the repository.
2.  Create a new feature branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3.  Commit your changes:
    ```bash
    git commit -m 'Add your feature'
    ```
4.  Push to GitHub:
    ```bash
    git push origin feature/your-feature-name
    ```
5.  Open a Pull Request 🙌

-----
