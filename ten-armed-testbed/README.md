
# 🎰 Ten-Armed Testbed – Reinforcement Learning Exploration

This project implements the **Ten-Armed Bandit Testbed** example from the legendary book 📘 _"Reinforcement Learning: An Introduction"_ by **Richard S. Sutton** and **Andrew G. Barto**.

It simulates a common reinforcement learning environment where agents must learn the best action (bandit arm) through exploration and exploitation over time.

---

## 🧠 Based On

📘 Sutton, R. S., & Barto, A. G. (2018).  
_Reinforcement Learning: An Introduction (2nd Edition)_  
🔗 [Read the book online](http://incompleteideas.net/book/the-book-2nd.html)

Chapter: **2. Multi-armed Bandits**

---

## 📁 Project Structure

```bash
ten-armed-testbed/
├── generated_images/            # Plots generated during experiments
│   ├── 1.png
│   ├── 2.png
│   └── ...
├── notebooks/
│   └── ten_armed_testbed.ipynb  # Jupyter notebook for experimentation
├── src/
│   ├── __init__.py
│   └── bandit.py                # Main simulation logic and agents
├── requirements.txt             # Required Python packages
```

---

## 🚀 How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/YourUsername/ten-armed-testbed.git
cd ten-armed-testbed
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**  
```bash
jupyter notebook notebooks/ten_armed_testbed.ipynb
```

---

## 📊 Features

- Implements **ε-greedy strategies** for different values of ε
- Simulates **non-stationary rewards** (optional)
- Visualizes performance with average rewards and % of optimal actions
- Reproduces results similar to Sutton & Barto’s **Figure 2.2**

---

