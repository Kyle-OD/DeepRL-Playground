# DeepRL-Playground

Using this as a space to increase my knowledge of Deep RL, building towards a more complete understanding of continuous action spaces

Study Plan: Continuous Action Spaces in Deep Reinforcement Learning

1. Foundation Review (1 week)
   - Review policy gradient methods and PPO
   - Paper: "Proximal Policy Optimization Algorithms" by Schulman et al.
   - Exercise: Implement PPO for a simple discrete action space problem (e.g., CartPole)

2. Introduction to Continuous Action Spaces (1 week)
   - Understand the differences between discrete and continuous action spaces
   - Paper: "Continuous control with deep reinforcement learning" by Lillicrap et al. (DDPG paper)
   - Exercise: Implement a simple continuous control task (e.g., Pendulum-v0) using a basic actor-critic method

3. Deep Deterministic Policy Gradient (DDPG) (2 weeks)
   - Study the DDPG algorithm in depth
   - Paper: "Continuous control with deep reinforcement learning" by Lillicrap et al.
   - Techniques: Actor-critic architecture, deterministic policy gradients, experience replay, soft target updates
   - Exercise: Implement DDPG for a continuous control task (e.g., MuJoCo environments like HalfCheetah-v2)

4. Twin Delayed DDPG (TD3) (1 week)
   - Learn about improvements to DDPG
   - Paper: "Addressing Function Approximation Error in Actor-Critic Methods" by Fujimoto et al.
   - Techniques: Clipped double Q-learning, delayed policy updates, target policy smoothing
   - Exercise: Implement TD3 and compare its performance with DDPG on the same environment

5. Soft Actor-Critic (SAC) (2 weeks)
   - Study the SAC algorithm and its benefits
   - Paper: "Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor" by Haarnoja et al.
   - Techniques: Maximum entropy reinforcement learning, off-policy learning, automatic entropy tuning
   - Exercise: Implement SAC and compare its performance with TD3 on a challenging continuous control task

6. Policy Optimization in Continuous Spaces (2 weeks)
   - Extend your knowledge of PPO to continuous action spaces
   - Paper: "Emergence of Locomotion Behaviours in Rich Environments" by Heess et al.
   - Techniques: Gaussian policies, adaptive KL penalty, natural gradient methods
   - Exercise: Implement PPO for a continuous action space problem and compare with SAC

7. Advanced Topics (2 weeks)
   - Exploration in continuous action spaces
     - Paper: "Parameter Space Noise for Exploration" by Plappert et al.
   - Model-based RL for continuous control
     - Paper: "Learning to Control a Low-Cost Manipulator using Data-Efficient Reinforcement Learning" by Deisenroth et al.
   - Multi-agent RL in continuous action spaces
     - Paper: "Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments" by Lowe et al.

8. Project (2 weeks)
   - Choose a challenging continuous control task (e.g., complex robotics simulation)
   - Implement and compare at least three different algorithms (e.g., DDPG, TD3, SAC)
   - Analyze the results, including learning curves, final performance, and sample efficiency
   - Write a report summarizing your findings and insights

Additional Resources:
- OpenAI Spinning Up: https://spinningup.openai.com/
- DeepMind Control Suite: https://github.com/deepmind/dm_control
- Stable Baselines3: https://stable-baselines3.readthedocs.io/

Papers Referenced:
1. "Proximal Policy Optimization Algorithms" by Schulman et al.
   https://arxiv.org/abs/1707.06347

2. "Continuous control with deep reinforcement learning" by Lillicrap et al.
   https://arxiv.org/abs/1509.02971

3. "Addressing Function Approximation Error in Actor-Critic Methods" by Fujimoto et al.
   https://arxiv.org/abs/1802.09477

4. "Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor" by Haarnoja et al.
   https://arxiv.org/abs/1801.01290

5. "Emergence of Locomotion Behaviours in Rich Environments" by Heess et al.
   https://arxiv.org/abs/1707.02286

6. "Parameter Space Noise for Exploration" by Plappert et al.
   https://arxiv.org/abs/1706.01905

7. "Learning to Control a Low-Cost Manipulator using Data-Efficient Reinforcement Learning" by Deisenroth et al.
   https://arxiv.org/abs/1406.5463

8. "Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments" by Lowe et al.
   https://arxiv.org/abs/1706.02275

Throughout the study plan:
- Implement algorithms from scratch when possible to deepen understanding
- Use existing libraries (e.g., Stable Baselines3) for comparison and validation
- Experiment with hyperparameter tuning and ablation studies
- Keep a journal of your learnings, challenges, and insights 