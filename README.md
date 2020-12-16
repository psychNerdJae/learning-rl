# Learning RL

Jae's record of self-teaching reinforcement learning (RL), as it's used in psychological research. Also a record of self-teaching Python(!), so lacks any sort of the elegance of well-written Python.

## Topics
1. Learning the value of a single stimulus (learning rate parameter alpha)
2. Multi-stimulus environments (Rescorla-Wagner and the prediction error delta)
3. Choosing between stimuli (exploration parameter beta)
4. Multi-step choice (temporal discounting parameter gamma)
5. Agents with "memory activation" (TD-lambda)
6. Sarsa and Q-learning
7. Model-based (MB) agents and transition structure
8. The Successor Representation (SR) and transition structure

## Potential future topics
1. SR + Dyna replay + prioritized sweeping
2. SF + LSFM
3. Parameter-fitting

## Inspiration / tutorials
- [Bob Wilson's class on computational modeling](http://u.arizona.edu/~bob/web_NSCS344/index.html)
- [Hanneke den Ouden and Jill O'Reilly's tutorial on reinforcement learning](http://hannekedenouden.ruhosting.nl/RLtutorial/Instructions.html)
- [Ida Momennejad's GitHub repository on predictive representation](https://github.com/idamomen/predictive_representations)

## Installation notes
Recently upgraded to the "Apple Silicon" MacBook Pro (i.e., with the new M1 ARM chipset). As of 12/13/2020, most things are (to my knowledge) working pretty smoothly. All packages can be managed exclusively via Anaconda. My virtual environment is running Python 3.8 with jupyter, scipy, and seaborn (and others, but this installs the max number of dependencies with the fewest calls). I also use python-graph, with a minimum v0.8.3. This can be done through conda-forge without hiccups.