# 🎲 Maximization Bias in Reinforcement Learning

This project explores the concept of **maximization bias** in Reinforcement Learning (RL), as introduced in Sutton & Barto's *Reinforcement Learning: An Introduction*. The implementation demonstrates how action-value estimates can become biased when the maximum is used both to **select** and **evaluate** actions.

---

## 📁 Project Structure

```
maximization-bias/
│
├── book_images/            # Reference images from Sutton & Barto
│   ├── Figure_6_5_graph.PNG
│   └── Figure_6_5_mdp.PNG
│
├── generated_images/       # Figures generated from experiments
│   └── figure_6_5.png
│
├── notebooks/              # Jupyter notebooks for experiments & demos
│   └── maximization_bias.ipynb
│
├── src/                    # Core Python source code
│   ├── __init__.py
│   └── maximization_bias.py
│
├── External Libraries/     # (IDE-managed, not version-controlled)
└── Scratches and Consoles/ # (IDE-managed, not version-controlled)
```

---

## ⚡ Key Features
- Implementation of **Maximization Bias** experiment (Figure 6.5 from Sutton & Barto).
- Comparison between **Q-Learning** and **Double Q-Learning**.
- Visualization of bias effects using matplotlib.
- Clean separation of code (`src/`), experiments (`notebooks/`), and images.

---

## 📓 Usage

### Run Jupyter Notebook
Open the notebook to reproduce experiments:
```bash
jupyter notebook notebooks/maximization_bias.ipynb
```

### Run Python script
To execute directly:
```bash
python src/maximization_bias.py
```

---

## 📊 Results

Generated images (in `generated_images/`) replicate **Figure 6.5** from Sutton & Barto, showing the difference between Q-Learning and Double Q-Learning.

- **Input reference images**: `book_images/`
1.
- Figure 6.5 shows that Q-learning with $\varepsilon$-greedy action selection initially learns to strongly favor the $left$ action on this example. 
- Even at asymptote, Q-learning takes the $left$ action about 5% more often than is optimal at our parameter settings ($\varepsilon=0.1, \alpha=0.1, \gamma=1$).
<img width="500" height="480" alt="image" src="https://github.com/user-attachments/assets/bc823f30-a65a-4cbd-ac1b-04645bdf3742" />

2.
<img width="500" height="480" alt="Figure_6_5_graph" src="https://github.com/user-attachments/assets/71990fb1-2f87-4dc8-ae13-b4cb5e026a51" />


- **Output experimental figures**: `generated_images/`
<img width="500" height="480" alt="figure_6_5" src="https://github.com/user-attachments/assets/e948204f-2450-448d-8750-5c8d8e5ce575" />


---



## 🛠️ Requirements
- Python 3.8+
- NumPy
- Matplotlib
- Jupyter Notebook
