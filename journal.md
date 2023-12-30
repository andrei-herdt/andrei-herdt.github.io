# Reinforcement Learning Development Journal

## Introduction
Welcome to my Reinforcement Learning Development Journal. Here, I document my journey, experiments, and learnings in the field of RL.

### Goals
- Briefly describe your goals or what you aim to achieve with your RL experiments.

### Project Overview
- Provide an overview of your project, including the problem you're trying to solve or the algorithms you're exploring.

---

## Experiment Log

changenum=1
num_minibatches = 4
num_steps:  0 eval/episode_reward:  0.5760557 eval/episode_reward_std:  0.9477362
num_steps:  30310400 eval/episode_reward:  1.806519 eval/episode_reward_std:  4.0989275
num_steps:  60620800 eval/episode_reward:  8.016773 eval/episode_reward_std:  7.0157056
time to jit: 0:00:48.443359 time to train: 0:16:33.615585

changenum=1
num_envs=1024,
num_steps:  0 eval/episode_reward:  0.56519926 eval/episode_reward_std:  0.94614327
num_steps:  30310400 eval/episode_reward:  8.624402 eval/episode_reward_std:  6.6967926
num_steps:  60620800 eval/episode_reward:  11.163882 eval/episode_reward_std:  6.147504
time to jit: 0:00:46.034939 time to train: 0:25:47.985451

ff9ffb95f64a821fc80553d6aa9e756ca97ce7db
increase batch_size
num_steps:  0 eval/episode_reward:  0.5935141 eval/episode_reward_std:  1.0470779
num_steps:  32768000 eval/episode_reward:  7.8386593 eval/episode_reward_std:  5.9317703
num_steps:  65536000 eval/episode_reward:  9.442217 eval/episode_reward_std:  5.8058133
time to jit: 0:00:47.062260 time to train: 0:27:53.307440


d200d204

Decrease batch_size, increase torque penalty. Time to JIT: 0:00:46.774209. Time to train: 0:25:50.067106.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.587013            | 1.0336502               |
| 30310400   | 6.013794            | 7.0553393               |
| 60620800   | 9.640033            | 9.364621                |

![](videos/d200d204.gif)

d24e43d7

Increase feet_air_time. Time to JIT: 0:00:47.117407. Time to train: 0:25:49.084794.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.5909057           | 1.0505813               |
| 30310400   | 3.4921775           | 6.37509                 |
| 60620800   | 13.843228           | 7.590749                |

![](videos/d24e43d7.gif)

70697c88

Increase episode_length. Time to JIT: 0:01:29.635887. Time to train: 0:27:17.197335.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.57269526          | 0.9965664               |
| 30310400   | 30.21885            | 27.981796               |
| 60620800   | 19.369843           | 24.694622               |

![](videos/70697c88.gif)

84a2f6a3

Increase torque penalty. Time to JIT: 0:01:29.584691. Time to train: 0:27:17.806234.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.60052776          | 1.0443081               |
| 30310400   | 0.014213366         | 0.013499956             |
| 60620800   | 0.017713964         | 0.020368503             |

![](videos/84a2f6a37.gif)

42ee1b36

Decrease torque penalty. Time to JIT: 0:01:28.993436. Time to train: 0:27:16.385898.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.60416865          | 1.0367799               |
| 30310400   | 9.292147            | 19.73348                |
| 60620800   | 31.627762           | 28.004442               |

de43f5f8

Remove randomisation. Time to JIT: 0:01:27.374001. Time to train: 0:27:12.238757.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.20221572          | 0.32954594              |
| 30310400   | 20.743465           | 28.053604               |
| 60620800   | 21.331964           | 23.62141                |

![](videos/de43f5f8.gif)

eed45565

Increase action rate penalty. Time to JIT: 0:01:25.692798. Time to train: 0:27:07.809092.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.103766695         | 0.21061304              |
| 30310400   | 13.177053           | 21.920616               |
| 60620800   | 12.000593           | 19.584045               |

![](videos/eed45565.gif)

8a21018a

Time to JIT: 0:01:26.443080. Time to train: 0:27:10.533919.

| num_steps  | eval/episode_reward | eval/episode_reward_std |
|------------|---------------------|-------------------------|
| 0          | 0.040621825         | 0.097854026             |
| 30310400   | 5.1783323           | 16.438326               |
| 60620800   | 1.5054538           | 7.3795896               |

![](videos/8a21018a.gif)
