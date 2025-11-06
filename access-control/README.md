# Access Control Problem (Reinforcement Learning)

This repository contains an implementation of the **Access-Control Queueing Problem** from Sutton & Barto’s *Reinforcement Learning: An Introduction*.  
The project includes environment code, tile coding features, and an example Jupyter notebook for experimentation and visualization.

---

## 📁 Project Structure

```
access-control/
│
├── book_images/
│   ├── Figure_10_5_1.PNG
│   └── Figure_10_5_2.PNG
│
├── generated_images/
│   └── figure_10_5.png
│
├── notebooks/
│   └── access_control.ipynb
│
└── src/
    ├── __init__.py
    ├── access_control.py
    └── tile_coding.py
```

---

## 🧠 Overview

The Access-Control problem models a server that must decide whether to accept or reject incoming requests of different priority levels.  
Each decision affects immediate reward as well as system load and future returns.

This codebase includes:

### ✅ `access_control.py`
- Environment dynamics  
- Definition of states, actions, and rewards  
- Implementation based on Sutton's textbook example  
- Simulation utilities for generating episodes  

### ✅ `tile_coding.py`
- Tile coding feature representation  
- Vectorized tile indexing  
- Basis function utilities for linear value-function approximation  

### ✅ Notebook: `access_control.ipynb`
- Demonstrates how to run the environment  
- Shows how to use tile coding  
- Trains an agent (e.g., semi-gradient methods)  
- Reproduces plots similar to Figure 10.5 from the book  

---

## 📊 Figures

- **book_images/** contains original figures from Sutton & Barto.
 
  1.<img width="580" height="480" alt="Figure_10_5_1" src="https://github.com/user-attachments/assets/d8640880-0a7c-412f-aa3d-bae8d6bca477" />

  2.<img width="580" height="480" alt="Figure_10_5_2" src="https://github.com/user-attachments/assets/c23d9fdf-68fa-4ed6-8e90-5b35166a38f6" />


- **generated_images/** stores figures created by the notebook (e.g., learned value function).
  
1.Policy Heatmap

<img width="580" height="480" alt="image" src="https://github.com/user-attachments/assets/bc24c270-41e7-4746-b18b-f1229a3ca525" />

2.Value Differences

<img width="580" height="480" alt="image" src="https://github.com/user-attachments/assets/a8648843-72ac-46d4-b9eb-8a927d58c795" />


---

## 🔧 Methods Used

- Reinforcement Learning  
- Tile Coding Function Approximation  
- Semi-Gradient TD Methods  
- Policy Evaluation & Control  
- Visualization of learned state-value function  

---

## 📜 Reference

Sutton, R. S., & Barto, A. G. *Reinforcement Learning: An Introduction*, 2nd Edition.

---
