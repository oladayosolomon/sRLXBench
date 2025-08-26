# sRLXBench
A Benchmark Suite of Deep Reinforcement Learning as Single Objective Optimization Problems and Baseline Results

Requires Python 3.11 and PlatEMO v4.2 (https://github.com/BIMK/PlatEMO). <br />
Clone this repository and install the packages specified in requirements.txt <br />
```
git clone https://github.com/oladayosolomon/sRLXBench/
cd sRLXBench
pip install -r requirements.txt
```
For the reacher environment, you'll need to install pybullet-gym from https://github.com/benelot/pybullet-gym<br />
```
git clone https://github.com/benelot/pybullet-gym.git
cd pybullet-gym
pip install -e .
```
you should then copy the sDRL folder to the PlatEMO multi-objective problem directory, the mat_eval_env.py to the main PlatEMO directory (the one with the platemo.m file), and the HV_rl.m file to the Metric directory<br />

Path related information<br />

```
pyenv("Version",'C:\Users\ecis\anaconda3\envs\RL_Bench\python.exe')

```

The following environments are currently implemented

| **Environment ID** | **Description**                |
|--------------------|--------------------------------|
| sDRL1               | Cart Pole                     |
| sDRL2               | Frozen Lake                   |
| sDRL3               | Pendulum                      |
| sDRL4               | Lunar Lander                  |
| sDRL5               | Inversted Double Pendulum     |
| sDRL6               | Mountian Car Continuous       |
| sDRL7               | Hopper                        |
| sDRL8               | Half Cheetah                  |
| sDRL9               | Reacher                       |

