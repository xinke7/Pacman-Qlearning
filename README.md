# Pacman-Qlearning
 Pacman game with Q-learning AI for CDS524 assignment.

**Features**
- Simplified 10x10 grid Pacman game
- Q-learning algorithm implementation
- Pygame-based visualization
- Customizable reward system

**Project Structure**
Pacman-Qlearning/
├── game_env.py      # Game environment
├── q_learning.py    # Q-learning agent
├── train.py         # Training script
├── requirements.txt # Dependencies
└── README.md        # This file

**Q-learning Implementation**
State: [pacman_position, ghost_position, pellet_positions]
Actions: Up, Down, Left, Right
Rewards: +10 for pellet, -10 for ghost, -0.1 per step
