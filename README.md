# Deep_Reinforcement_Learning_Healthcare_Appointment_Scheduling
Reinforcement learning-based outpatient appointment scheduling for optimizing patient waiting times and doctor utilization. Includes both Jupyter Notebook and Python script implementations.

Deep_Reinforcement_Learning_Healthcare_Appointment_Scheduling: 

- DRL_Project_notebook.ipynb # Jupyter Notebook version of the project
- DRL_Project_notebook.py # Python script version of the project
- README.md # This file
- requirements.txt # Containing the library requirements 
- Project_Report.pdf # Detailed report of this project


## Project Overview:

Efficient outpatient scheduling is a challenging problem due to stochastic patient arrivals, variable consultation durations, and no-show events. Traditional heuristics like FIFO (First-In-First-Out) and SJF (Shortest-Job-First) are limited in adapting to real-time dynamics. This project implements RL-based scheduling agents that learn optimal appointment allocation policies using:

- **Tabular Q-Learning:** Discretized state representation, interpretable, and simple.
- **Deep Q-Network (DQN):** Continuous state representation, neural network function approximation for better generalization.

The system simulates an 8-hour outpatient clinic with multiple doctors, stochastic patient arrivals, and appointment slots in 15-minute intervals.

## Files:

### `DRL_Project_notebook.ipynb`:
- Jupyter Notebook version for interactive exploration.
- Includes step-by-step code, explanations, visualizations, and results.
- Ideal for experimenting with hyperparameters, reward functions, and agent policies.
   ```bash
   Jupyter DRL_Project_notebook.ipynb

### `DRL_Project_notebook.py`:
- Standalone Python script version for running experiments without a Jupyter environment.
- Produces the same results and visualizations as the notebook.
- Can be executed directly from the command line:
  ```bash
  python DRL_Project_notebook.py

### Key Features:

- Simulates patient arrivals and doctor schedules in a realistic outpatient environment.
- Implements both tabular Q-learning and DQN agents.
- Compares RL agents with traditional heuristics: FIFO and SJF.

### Tracks metrics like:

- Average patient waiting time
- Doctor utilization
- Average free time
- Overtime
- Cumulative episode reward
- Combined cost metric

### Requirements:

- Python 3.8+
- Libraries:
- numpy
- pandas
- matplotlib
- seaborn
- gym (for simulation environment)
- tensorflow or torch (depending on DQN implementation)
- scipy
- torch

### Install dependencies using: 
pip install -r requirements.txt 

### How to Run Jupyter Notebook:

- Open DRL_Project_notebook.ipynb in Jupyter.
- Run cells sequentially to see simulations, training progress, and results.
- Visualizations and tables will appear inline.

### How to Run Python Script:

- Open a terminal or command prompt.
- Navigate to the repository folder: cd path/to/Deep_Reinforcement_Learning_Healthcare_Appointment_Scheduling
- Run the Python script.
- Outputs will be displayed in the terminal and saved as plots in the working directory.

### Results:

- RL agents (especially DQN) significantly reduce average waiting times compared to FIFO and SJF.
- Doctor utilization remains balanced while minimizing idle time.
- Tables and plots in the notebook/script demonstrate performance across all metrics.

### References:

- A. Gupta and B. Denton, “Appointment scheduling in health care: Challenges and opportunities,” IIE Transactions, vol. 40, no. 9, pp. 800–819, 2008.
- O. Cayirli and E. Veral, “Outpatient scheduling in health care: A review of literature,” Production and Operations Management, vol. 12, no. 4, pp. 519–549, 2003.
- V. Mnih et al., “Human-level control through deep reinforcement learning,” Nature, vol. 518, pp. 529–533, 2015.
- M. Littman, “Markov games as a framework for multi-agent reinforcement learning,” Machine Learning, vol. 16, pp. 179–202, 1994.
- M. Pinedo, Scheduling: Theory, Algorithms, and Systems, 5th ed., Springer, 2016.
- J. Zhang, Y. Li, and X. Liu, “Q-learning for outpatient scheduling with no-shows,” Journal of Healthcare Engineering, vol. 2020, Article ID 123456, 2020.
- H. Bai et al., “Deep reinforcement learning for patient prioritization in emergency departments,” Artificial Intelligence in Medicine, vol. 97, pp. 59–70, 2019.
- K. Zhou, W. Zhang, and J. Li, “Actor–Critic approaches for hospital bed management,” Health Systems, vol. 10, pp. 55–68, 2021.
- J. Liu et al., “Multi-agent reinforcement learning for operating room scheduling,” IEEE Transactions on Systems, Man, and Cybernetics, vol. 52, no. 1, pp. 45–56, 2022.
- E. Johnson et al., “MIMIC-III, a freely accessible critical care database,” Scientific Data, vol. 3, Article 160035, 2016.
- J. Gao, M. Li, and F. Wang, “Hybrid predictive-RL models for healthcare scheduling,” Expert Systems with Applications, vol. 201, Article 117398, 2022.
- Y. Ye et al., “Graph-based reinforcement learning for shared outpatient resource allocation,” Artificial Intelligence in Medicine, vol. 145, 2023.
- Sutton & Barto, Section 6.5, page 131
- Project Proposal.pdf
- Slide deck "12DQN.pptx"


### Contact

For questions or collaboration:

- Subhiksha Saravanasundaram – subhiksha13@tamu.edu
- Gauri Pawar – gauri_pawar@tamu.edu
