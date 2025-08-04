# Reinforcement-Learning

Reository created for Reinforcement-Learning codings

<img width="384" height="243" alt="image" src="https://github.com/user-attachments/assets/fa3122eb-0a9e-49a6-8a2f-ea5ff04e08c7" />


The rules of the environment are as follows.
1. An agent is supposed to start in cell (1,1).
2. Available actions, 𝐴(𝑠) = {𝑢𝑝, 𝑑𝑜𝑤𝑛, 𝑙𝑒𝑓𝑡, 𝑟𝑖𝑔ℎ𝑡}, where state 𝑠 is some cell (𝑥, 𝑦) with 𝑥 being 
the column number and 𝑦 being the row number.
a. An action results in the intended movement with probability 0.8 but can cause movement 
in one of the perpendicular directions with probability 0.1 each.
b. Bumping into a wall results in staying in the same cell.
3. 𝑅(𝑠) denotes the reward received in state 𝑠. 𝑅((4,3)) = +1,𝑅((4,2)) =
−1, 𝑎𝑛𝑑 𝑓𝑜𝑟 𝑎𝑛𝑦 𝑜𝑡ℎ𝑒𝑟 (𝑥, 𝑦), 𝑅(𝑥, 𝑦) = −0.04.
4. The agent will exit the environment if any of the two terminal states, i.e., (4,3) 𝑜𝑟 (4,2), is 
reached.
5. The objective of the agent is to maximize the total sum of rewards received. Assume that rewards 
are additive. Use a discount factor 𝛾 = 0.9, wherever applicable.
6. The environment is fully observable – the agent knows exactly which sell it is in
