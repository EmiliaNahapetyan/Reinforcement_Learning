
# 🤖 Tic-Tac-Toe with Reinforcement Learning

This project implements a simple **Tic-Tac-Toe (XOX)** game using **Reinforcement Learning**, inspired by the classic book 📘 _"Reinforcement Learning: An Introduction"_ by **Richard S. Sutton** and **Andrew G. Barto**.

Two agents learn optimal strategies by self-play using **value function updates** and **ε-greedy policies**, demonstrating how simple reinforcement learning techniques can be applied to board games.

---


## 📁 Project Structure

```bash
tic-tac-toe/
├── src/
│   ├── tic_tac_toe.py        # Main script: training and playing the game
│   ├── state.py              # Game board and states
│   ├── player.py             # Reinforcement learning agent (value function, ε-greedy policy)
│   ├── judge.py              # Game logic, determining the winner
│   ├── policy_first.bin      # Trained policy for the first agent
│   ├── policy_second.bin     # Trained policy for the second agent
```

---

## 🚀 How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/EmiliaNahapetyan/Reinforcement_Learning.git
cd Reinforcement_Learning/tic-tac-toe
```

2. **Train the agents** (optional, if policies are not trained yet)  
```bash
python tic_tac_toe.py --train
```

3. **Play the game between two trained agents**  
```bash
python tic_tac_toe.py --play
```

4. **You can also let a human play vs the trained agent**  
(You’ll need to add interactive support in the code, if desired)

---

## 💡 Key Concepts Used

- **TD(0) Learning**
- **Self-play**
- **Exploration vs Exploitation (ε-greedy policy)**
- **State-value functions**
- **Serialization of learned policies**

---

## **📌 How the AI Learns**  

- **Self-Play Training**: The agent improves by playing against itself.  
- **State-Value Learning**: Assigns values to board positions based on past results.  
- **Policy Updates**: Uses different strategies for first and second players.  
- **Judging System**: `judge.py` evaluates game outcomes for training.   

