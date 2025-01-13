# Reinforcement-Learning-DSCI-6650-002

## Prerequisites

Ensure you have the following software installed:

- Python 3.x
- Jupyter Notebook
- Necessary Python libraries: `numpy`, `matplotlib`, `gym`, and `stable-baselines3`

You can install the required libraries using the following command:

```bash
pip install numpy matplotlib gym stable-baselines3
```

## Files

This repository contains the following files:

1. `a2q1.ipynb`: Jupyter notebook for Part 1 of the assignment.
2. `a2q2v2.ipynb`: Jupyter notebook for Part 2 of the assignment.
3. `rl-a2.pdf`: PDF file containing the assignment description.

## Instructions to Run the Notebooks

### Part 1

1. **Open the Jupyter Notebook:**

   ```
   jupyter notebook a2q1.ipynb
   ```

**Follow the instructions in the notebook:** The notebook guides you through solving the gridworld problem using various methods like solving the Bellman equations explicitly, iterative policy evaluation, and value iteration.

* Execute each cell sequentially to ensure that the results are generated correctly.
* The notebook contains plots and results demonstrating the value functions and policies.


### Part 2

1. **Open the Jupyter Notebook:**

```
jupyter notebook a2q2v2.ipynb
```


**Follow the instructions in the notebook:** The notebook covers the modified gridworld problem with terminal states and negative rewards for white squares.

* Methods such as the Monte Carlo method with exploring starts, the ϵ-soft approach, and policy iteration are used.
* Execute each cell in order to reproduce the results and visualize the policies.


## Directory Structure

Ensure your directory is structured as follows:

```
reinforcement-learning-assignment/
│
├── a2q1.ipynb
├── a2q2v2.ipynb
├── rl-a2.pdf
├── Sameer-rl-a2-report.pdf
└── images
```


## Reproducing Results

To reproduce the results:

1. **Set up the environment:** Ensure you have all the prerequisites installed.
2. **Run the notebooks:** Follow the steps mentioned in the Instructions to Run the Notebooks section for each part.
3. **Verify outputs:** Check the generated plots and values to match them with the expected results as described in the assignment PDF.
