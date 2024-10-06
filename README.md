# Legged_gym environment for Beatles wheel-legged robot


## Install

```bash
conda create -n beatles python=3.8
conda activate beatles
# Download the Isaac Gym binaries from https://developer.nvidia.com/isaac-gym 
cd isaacgym/python && pip install -e .
cd ~/Beatles-Gym/
pip install -e .
```

## Run

```bash
python wheel_legged_gym/scripts/train.py --task=wheel_legged --headless
python wheel_legged_gym/scripts/play.py --task=wheel_legged

python wheel_legged_gym/scripts/train.py --task=wheel_legged_rough --headless
python wheel_legged_gym/scripts/play.py --task=wheel_legged_rough
```

## Reference

- https://github.com/clearlab-sustech/Wheel-Legged-Gym
- https://github.com/leggedrobotics/legged_gym
- https://github.com/leggedrobotics/rsl_rl
- https://github.com/isaac-sim/IsaacLab

