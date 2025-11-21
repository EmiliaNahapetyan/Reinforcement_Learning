# Counter-Examples in Reinforcement Learning

Reproducing Figures from Sutton & Barto (2nd Edition)

This repository contains implementations and visual reproductions of
several well-known **counterexamples in reinforcement learning**,
including **Baird's counterexample**, **emphatic temporal-difference
learning**, and **TDC / GTD methods**.\
The goal of the project is to **reproduce the figures from Chapter 11**
of *Sutton & Barto (2018)* and to compare learning dynamics across
different TD algorithms.

## 📁 Project Structure

    counter-examples/
    │
    ├── book_images/             
    │   ├── Figure_11.1.PNG
    │   ├── Figure_11.2.PNG
    │   ├── Figure_11.5.PNG
    │   └── Figure_11.6.PNG
    │
    ├── generated_images/        
    │   ├── figure_11_2.png
    │   ├── figure_11_5.png
    │   └── figure_11_6.png
    │
    ├── notebooks/               
    │   ├── bairds_counterexample.ipynb
    │   ├── emphatic_baird.ipynb
    │   └── tdc_baird.ipynb
    │
    └── src/                     
        ├── __init__.py
        └── counter_example.py

## 🚀 Implemented Counterexamples

### 1. Baird's Counterexample

-   Demonstrates divergence of TD(0) with linear function approximation\
-   Notebook: `bairds_counterexample.ipynb`\
-   Reproduced figure: **Figure 11.2**

### 2. Emphatic TD Learning

-   Shows how Emphatic TD methods correct the divergence issue\
-   Notebook: `emphatic_baird.ipynb`\
-   Reproduced figure: **Figure 11.5**

### 3. TDC / GTD Algorithms

-   Gradient TD algorithms that provably converge under off-policy
    learning\
-   Notebook: `tdc_baird.ipynb`\
-   Reproduced figure: **Figure 11.6**


## 📊 Generated Images

  1.Figure of Semi-gradient Off-policy TD and Semi-gradient DP 
  
  <img width="640" height="1080" alt="figure_11_2" src="https://github.com/user-attachments/assets/50834aaa-7a6d-4730-bf17-759afdef1ebc" />
  
  2.Figure of TDC and Expected TDC
  
  <img width="640" height="1080" alt="figure_11_5" src="https://github.com/user-attachments/assets/37bb9de8-a1ec-4902-9fd0-94dedd87409b" />

  3.Figure of Expected Emphatic TD
  
  <img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/272c97ba-00c3-40d3-b4d9-f422f86bb548" />


