# NewSpaceRL‐Env

A gym‐compatible environment for multi-agent LEO satellite tasking.

## Installation

```bash
git clone git@github.com:RAISSOUNIHASSAN/NewSpaceRL-env.git
cd NewSpaceAI-env
python3 -m venv .env && source .env/bin/activate
pip install -r requirements.txt
pip install -e .



# Usage

import gym
env = gym.make("NewSpace-Swarm-v0")
obs = env.reset()
See train.py --help for training and evaluation commands.
