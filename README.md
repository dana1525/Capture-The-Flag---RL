# Capture-The-Flag - RL
A grid-based game in Python against an AI-controlled opponent using Q-learning.

## Features
- Playable game with grid and flag mechanics
- AI agent trained through reinforcement learning
- Interactive gameplay using keyboard controls

## Installation
1. Clone the repository and install dependencies:

```bash
git clone https://github.com/dana1525/Capture-The-Flag---RL.git
cd Capture-The-Flag---RL
```

2. Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate   # on Linux/Mac
.venv\Scripts\activate      # on Windows (PowerShell)
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Install Jupyter kernel for the virtual environment:

```bash
pip install ipykernel
python -m ipykernel install --user --name=ctf-env --display-name "Python (ctf-env)"
```

5. Run the notebook:

```bash
jupyter notebook ctf_qlearning.ipynb
```

6. Copy the first URL shown in the terminal and paste it into your browser to open the notebook.
**Important**: In the notebook, select the kernel Python (ctf-env) from Kernel → Change Kernel.

7. Run the code.