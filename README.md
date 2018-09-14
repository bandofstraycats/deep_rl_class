# Introduction to Deep Reinforcement Learning
Hands-on introduction to Deep Reinforcement Learning, presented at [PAISS](https://project.inria.fr/paiss/).

## Contents

### Class material
1. Markov Decision Process
2. Deep Q-learning 
* Experience replay
* Double Deep Q-learning
* Dueling Q-learning
3. Actor-Critic

Launch slides viewer:
```
$ jupyter nbconvert Intro_RL.ipynb --to slides --post serve
```

### Practical session
The practical exercise shows how to solve [CartPole problem](https://github.com/openai/gym/wiki/CartPole-v0).

Required Python packages: gym, keras, jupyter.

Launch exercise notebook:
```
$ jupyter notebook deep_rl_exercise.ipynb
```
Compare your solution to correction notebook: `deep_rl_exercise_CORRECTION.ipynb`
