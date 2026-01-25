# Hi, I'm Akshay 👋

**PhD in Computer Science | Robotics & Reinforcement Learning**

I recently completed my PhD at Syracuse University, where I worked on training robust RL policies for robotic manipulation using adversarial co-training. My research focuses on making robots that don't break when they encounter objects they haven't seen before.

## 🔬 Research

My PhD work centered on co-training RL-based grasping policies with adversarial object generators. Instead of collecting more data, I built systems that automatically generate the objects most likely to break a policy, then train on those.

**Key contributions:**
- Voxel-based evolutionary generator that creates adversarial 3D objects for manipulation tasks
- RL-based generator that co-evolves with the learner (90% more efficient than evolutionary sampling)
- PPO-based grasping policies for continuous joint control in Pybullet
- Meta-learning algorithms for hierarchical tasks like block stacking

## 📄 Publications

| Paper | Venue | Year | Link |
|:------|:------|:----:|:----:|
| Conserving Fitness Evaluation in Evolutionary Algorithms with RL | ICLR (submitted) | 2026 | |
| Voxel-Based Evolutionary Data Generator of Adversarial Objects | GECCO | 2025 | [PDF](https://doi.org/10.1145/3712255.3734294) |
| Voxel-Based Data Generator of Adversarial Objects for Robotic Manipulators | Springer CCIS | 2025 | [PDF](https://link.springer.com/chapter/10.1007/978-3-031-85628-0_10) |
| Human-like Learning Dynamics in Simulated Humanoid Robots | HCI | 2022 | [PDF](https://link.springer.com/chapter/10.1007/978-3-031-05457-0_19) |
| Tunable Neural Encoding of a Symbolic Robotic Manipulation Algorithm | Frontiers in Neurorobotics | 2021 | [PDF](https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2021.744031/full) |

## 🛠️ Projects

### Robotic Grasper (2025)
RL-based grasping system using PPO actor-critic for continuous joint control of Poppy Ergo Jr. Currently extending this to co-train with adversarial object generators.

`Python` `PyTorch` `Pybullet` `PPO`

### Adversarial Object Generator (2024)
Generates infinite adversarial 3D objects using genetic algorithms and RL to stress-test manipulation policies.

`Python` `Evolutionary Algorithms` `Reinforcement Learning`

### Tiny LLM (2024)
Built a small transformer from scratch, then fine-tuned it to convert Shakespearean text to modern English. Personal project to understand LLM internals.

`PyTorch` `Transformers` `HuggingFace`

## 💻 Tech Stack

| Category | Technologies |
|:---------|:-------------|
| Languages | Python, C++, C, SQL |
| ML/RL | PyTorch, TensorFlow, PPO, Actor-Critic, Meta-Learning, Fine-Tuning |
| Robotics | MuJoCo, Isaac Sim, ROS/ROS2, SLAM , Pybullet |
| Tools | Git, Docker, HuggingFace, LangChain |

## 📫 Contact

| | |
|:--|:--|
| 📧 Email | akshay@syr.edu , akshay21021992@gmail.com |
| 💼 LinkedIn | [linkedin.com/in/akshay-02](https://linkedin.com/in/akshay-02) |
| 📍 Location | Syracuse, NY |

---


