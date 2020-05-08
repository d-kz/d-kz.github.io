---
layout: default
title: Helpful Resources
home: 0
about: Resources and links for acitivits. 
---

# {{page.title}}
{{page.about}} 

## Surfing
- [MagicSeaWeed](https://magicseaweed.com/Rockaway-Surf-Report/384/) - wave forecast (Rockaway beach)

## Skiing
- [OnTheSnow](https://www.onthesnow.com/colorado/winter-park-resort/skireport.html) - snow forecast and history (Winter Park)
- [OpenSnow](https://opensnow.com/state/CO#forecasts) - 10 day snow forecast (Colorado Rockies)
- [Evo](https://www.evo.com/) - discounted gear, not just skiing

## Hiking
- [AllTrails](https://www.alltrails.com/)

## Yoga
- [Yoga with Adriene](https://www.youtube.com/user/yogawithadriene) - awesome guided yoga lessons with insightful perceptions of movement.


## Courses:

### Game theory/(Multi-Agent) Reinforcement Learning (MARL)
- (Foundations):
	- [Game Theory (Standord, UBC), part 1](https://www.coursera.org/learn/game-theory-1) - lacks intuition, but a good structure. Introduces Nash's equilibrium, strategies, convergence intuition for strategies, (non)zero-sum games, (im)perfect information games. 
	- [Game Theory (Standord, UBC), part 2](https://www.coursera.org/learn/game-theory-2) - extends to marketplaces, voting. Feel free to skip, but look up [Walras Equilibrium Theorem](https://en.wikipedia.org/wiki/General_equilibrium_theory), because it's  cool. 
		- (If you speak Russian) [Game theory, MIPT](https://www.coursera.org/learn/gametheory) - combines the structure of 2 courses above, adds more examples for intuition, overall explained better. 
	- To make this theory practical, understand [alpha-beta pruning](https://www.geeksforgeeks.org/minimax-algorithm-in-game-theory-set-4-alpha-beta-pruning/), min-max in detail. Simple AI agents use this exact framework, but use heuristics to evaluate non-final states. Check out [checkers-ai](https://github.com/d-kz/checkers/blob/master/checkers.py), [chess-ai](https://github.com/lamesjim/Chess-AI/blob/master/heuristics.py). 
- Moving into "deep" Game Theory:
	- Fictitious play convergence towards Nash Equilibrium is one of the most helpful concepts from pure game theory. I see GANs as a fictitious play convergence framework. Explicitely, there is [fictitious GAN](https://arxiv.org/abs/1803.08647). 
	- [Neural Fictitious Self-Play](https://arxiv.org/pdf/1603.01121.pdf) is one of the most effective and practical algorithms used in neural agents. Used by [Deepmind's AlphaZero](https://science.sciencemag.org/content/362/6419/1140) to achieve superhuman performance from scratch. 
	- Overview of RL by Ilya: [Ilya Sutskever: OpenAI Meta-Learning and Self-Play](https://www.youtube.com/watch?v=9EN_HoEk3KY)
	- [Advanced RL by Deepmind](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs) - further material
- Multi-Agent RL:
	- [Deepmind's tutorial on MARL](https://rlss.inria.fr/files/2019/07/RLSS_Multiagent.pdf) - a great summary of everything above. 
	- [AlphaStar](https://www.nature.com/articles/s41586-019-1724-z.epdf?author_access_token=lZH3nqPYtWJXfDA10W0CNNRgN0jAjWel9jnR3ZoTv0PSZcPzJFGNAZhOlk4deBCKzKm70KfinloafEF1bCCXL6IIHHgKaDkaTkBcTEv7aT-wqDoG1VeO9-wO3GEoAMF9bAOt7mJ0RWQnRVMbyfgH9A%3D%3D) -  Deepmind's Starcraft 2 paper. They used human games to pretrain agents via imatation learning, but later used self-play to advance. Notably, human games were necessary here, in comparision to AlphaZero. 


### [Network Analysis and Modeling](http://tuvalu.santafe.edu/~aaronc/courses/5352/)
The most informative and helpful study of networks-graphs I've ever taken/seen. [Aaron Clauset](https://scholar.google.com/citations?user=e7VI_HcAAAAJ&hl=en&oi=sra) is a world expert on the topic and this is his view on the field. 

### [Machine Learning - math perspective](https://github.com/chrisketelsen/CSCI5622-Machine-Learning/blob/master/resources/schedule.md)
Here, you will derive **from scratch** the standard ML toolset  (Regressions, Support Vector Machines, Regularization, Boosting etc.). If you want to understand the ins and outs of ML, take this class. 

### [Algorithmic Economics and Machine Learning](https://www.cs.colorado.edu/~raf/teaching/7000-s17.html)
Information elicitation, game theoretic lens on Economics. Really elegant. 

<!-- ### [Calling Bullshit](https://callingbullshit.org/syllabus.html) 
A funny summary of how information in the modern world is abused, misrepresented, and even weaponized.  -->

### [Learning How To Learn](https://www.coursera.org/learn/learning-how-to-learn)
Neuroscience backed facts about how your brain acquires and solidifies knowledge. A class everyone should take as early as possible in any career they choose. Applicable to sports, science, self-improvement and most things really. 
