# WIDS_Flappy_Bird

This repository follows the **WiDS learning structure** and focuses on understanding the **basic ideas of Reinforcement Learning** using Flappy Bird as an example. The focus is on learning **how to think about RL problems**, not on writing code or using algorithms.

---

## Week 1 — Foundations

Week-1 is about building the basics before starting Reinforcement Learning. Python is used to learn how to think step-by-step and write clear logic. NumPy helps in working with numbers in an organized way instead of handling values one by one. Visualization helps us see how values change over time. These ideas help us later when we work with states, actions, and learning in RL.

---

## Week 2 — Reinforcement Learning Environments

### 1. Reinforcement Learning as Problem Setup  
Reinforcement Learning does not start with choosing an algorithm. It starts with **setting up the problem correctly**. The environment decides what the agent can see, what it can do, and how the world changes. If this setup is wrong, learning will not work.

---

### 2. Markov Decision Processes (MDPs)  
Reinforcement Learning problems are described using **Markov Decision Processes (MDPs)**. An MDP includes states, actions, rewards, and how the environment changes after an action. This helps us clearly describe what the agent knows and what it controls.

---

### 3. The Markov Property  
The Markov property means that the **current state should contain all important information about the future**. If the same state can lead to different results, the agent gets confused and cannot learn properly. Many RL problems fail because this rule is broken.

---

### 4. State Design and Partial Observability  
Choosing the right state is very important. If the state has too little information, the task becomes impossible. If it has too much information, learning becomes slow. The goal is to keep only what is needed to make decisions. When the state is missing important information, the problem is called partially observable.

---

### 5. Reward Design and Agent Behavior  
Agents do not understand goals like “survive” or “play well”. They only try to **get more reward**. Because of this, the reward function must be chosen carefully. A bad reward can make the agent learn strange or wrong behavior even if learning is happening.

---

### 6. Checking the Environment Before Training  
Before training an agent, we must check if the environment makes sense. Using random actions helps us see if the task is too hard, too easy, or broken. This step saves time and helps us understand the problem better.

---

### Main Idea from Week 2  
In Reinforcement Learning, **how you define the environment is more important than the algorithm**. A good environment makes learning possible, while a bad one makes learning fail.
