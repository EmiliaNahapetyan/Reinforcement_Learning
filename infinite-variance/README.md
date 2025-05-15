# 📈 Infinite Variance Project

This project focuses on the **Infinite Variance** problem in reinforcement learning, which often arises in off-policy learning scenarios when importance sampling weights grow too large, leading to unstable learning.

---

## 📁 Project Structure

```
infinite-variance/
├── .idea/                # IDE-specific configuration files
├── book_images/          # Diagrams or figures used in external documentation
├── generated_images/     # Images produced by experiments or visualizations
├── notebooks/            # Interactive notebooks for experimentation and analysis
├── src/                  # Source code for environment, algorithms, utilities, etc.
```

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/EmiliaNahapetyan/infinite-variance.git
   cd infinite-variance
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 📓 Notebooks

Explore the `notebooks/` directory for Jupyter notebooks showcasing variance problems, visualizations, or algorithmic fixes such as:
- Weighted importance sampling
- Baseline subtraction
- Variance-reduction techniques

---

## 🖼️ Images

- **book_images/** – Contains visuals used in documentation or educational material.
- **generated_images/** – Includes images created from running code (e.g., plots, agent paths).

---

## ⚙️ Source Code

Located in the `src/` directory, the source code likely includes:
- Simulation environments
- Off-policy learning algorithms
- Variance tracking and mitigation strategies

---

## 🤝 Contributing

Contributions and feedback are welcome! Feel free to fork the project and open a pull request. 🌟
