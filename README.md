# Solving acrobot-v1 using DQN
Acrobot-v1 Environment training using DQN – results
Training and rewards:
During the training phase, a DQN Agent targeting the "Acrobot-v1" environment is put through up to 2,000
episodes, with the possibility of halting earlier if performance meets specific criteria. Performance checks occur
every 10 episodes, evaluating the agent by averaging the rewards from the last 100 evaluations and comparing them
against a -120 threshold. Surpassing this benchmark indicates that the environment is effectively "solved," giving an
early end to training to conserve resources and prevent overfitting. Upon completion of the training, regardless of
early termination, the agent's learned weights are saved for future application. The training phase is followed by a
testing phase across 100 episodes to get the agent's trained proficiency, with the outcomes averaged for a proper
assessment of its post-training capabilities in navigating the chosen environment.
