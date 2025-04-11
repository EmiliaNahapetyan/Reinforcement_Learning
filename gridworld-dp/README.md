# Gridworld Dynamic Programming

This repository contains an implementation of the Gridworld example from **Chapter 4: Dynamic Programming** of the foundational book:

> Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.).  
> [http://incompleteideas.net/book/the-book-2nd.html](http://incompleteideas.net/book/the-book-2nd.html)

---

## 📁 Project Structure

```
gridworld-dp/
│
├── book_images/              # Original figures from the book
│   ├── Example_4.1.PNG
│   └── Figure_4.1.PNG
│
├── generated_images/         # Figures generated from this implementation
│   ├── figure_4_1_in_place.png
│   └── figure_4_1_out_place.png
│
├── notebooks/
│   └── grid_world.ipynb      # Jupyter notebook for running and visualizing Gridworld
│
├── src/                      # Python source code
│   ├── __init__.py
│   └── grid_world.py
│
└── README.md                 # Project documentation
```

---

## 📌 Overview

This project demonstrates:
- Implementation of the **Gridworld** environment.
- In-place and out-of-place **policy evaluation**.
- Policy improvement using **Dynamic Programming** methods.
- Reproduction of figures similar to those shown in the book.

The goal is to understand how value functions evolve over iterations and match the theoretical examples from Sutton & Barto's book.

---

## 🧪 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gridworld-dp.git
   cd gridworld-dp
   ```

2. Set up a virtual environment and install dependencies (if any):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   pip install -r requirements.txt  # (create this if needed)
   ```

3. Launch the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/grid_world.ipynb
   ```

---
