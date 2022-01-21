# RL-LunarLanderV2
Solution to openAI LunarLanderV2 problem via DQN with target network
Autors: [Carlos Golvano](https://github.com/CarlosGolvano), [Carlos Yanguas](https://github.com/c-yanguas), [Jorge Casajus](https://github.com/jogecodes).

Hyperparameters:
 - Gamma: 0.99
 - Memory_size: 1.000.000
 - Learning rate: 0.001
 - Batch size: 64
 - Exploration max: 1
 - Exploration min: 0.01
 - Exploration decay: 0.9998
 - Episodes: 600
 - Architecture
 - - Input: Number of parameters of the state (8)
 - - Hidden Layers: : 128, 64, 32 Fully connected with ReLU
 - - Output: Number of possible actions (4) with linear
 - - Update weights of target network: 100 steps

Here is the [agent](https://drive.google.com/file/d/1piiHVW8Ja3MLZzxggQmD9maLHtJjZ_d1/view?usp=sharing) class ready to be uploaded, due to its weight it is not possible to upload it directly to github.

Results:
![Results](https://github.com/c-yanguas/RL-LunarLanderV2/blob/main/Resultados.png)
