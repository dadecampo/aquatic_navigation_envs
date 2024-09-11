# aquatic_navigation_envs
This paper has been accepted by the 1st Reinforcement Learning Conference (RLC), August 9–12, 2024.
During the conference the project was awarded with one of the "Outstanding Paper Awards".
The full paper is available at this [link](https://rlj.cs.umass.edu/2024/papers/Paper131.html)

### Authors
*  **Davide Corsi** - dcorsi@uci.edu
*  **Davide Camponogara** - davide.camponogara.99@gmail.com
*  **Alessandro Farinelli** - alessandro.farinelli@univr.it

#
This project introduces new and complex submarine environments to test reinforcement learning algorithms.

This package is part of a larger project that you can find at the following git repository: [SafeRLAUV](https://github.com/dadecampo/SafeRLAUV), here you will find the Unity project where you can create new underwater environments with the components already prepared by the authors.

![](https://i.imgur.com/oY8Z1El.jpg)
## Environment Setup
1. Clone aquatic_navigation_envs repository using Git.

   - `git clone https://github.com/dadecampo/aquatic_navigation_envs`
  
2. Install requirements.

   - `conda create --name aquatic_navigation python=3.10.12`
  	- `conda activate aquatic_navigation`
   - `cd aquatic_navigation_envs`
   - `pip3 install -r requirements.txt`
   - `pip3 install -e .`
