# CS294-112 HW 3: Q-Learning

Dependencies:
 * Python **3.5**
 * Numpy version **1.14.5**
 * TensorFlow version **1.10.5**
 * MuJoCo version **1.50** and mujoco-py **1.50.1.56**
 * OpenAI Gym version **0.10.5**
 * seaborn
 * Box2D==**2.3.2**
 * OpenCV
 * ffmpeg

Before doing anything, first replace `gym/envs/box2d/lunar_lander.py` with the provided `lunar_lander.py` file.

The only files that you need to look at are `dqn.py` and `train_ac_f18.py`, which you will implement.

See the [HW3 PDF](http://rail.eecs.berkeley.edu/deeprlcourse/static/homeworks/hw3.pdf) for further instructions.

The starter code was based on an implementation of Q-learning for Atari generously provided by Szymon Sidor from OpenAI.

# Instructions for Composable Soft Q Learning

```ruby
python run_dqn_vizdoom.py --vizdoom --explore soft_q --env_path /Users/wangyujie/Desktop/iProud/iCourse/US/294-Reinforcement_Learning/Group_Project/DirectFuturePrediction/maps/D1_basic.cfg
python run_dqn_vizdoom.py --vizdoom --explore soft_q --ex2 --coef 1e-4 --env_path /Users/wangyujie/Desktop/iProud/iCourse/US/294-Reinforcement_Learning/Group_Project/DirectFuturePrediction/maps/D1_basic.cfg
```

## Cheers!