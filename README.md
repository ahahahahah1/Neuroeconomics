# Neuroeconomics
Takneek '22 PS released by BCS

Our approach was to break down the problem to figure out all the parameters that were in our hand and vary them to analyze the world as a whole.

![image](https://user-images.githubusercontent.com/106398507/229421408-8774d979-43fa-4cc0-a221-b41ac972a228.png)

***Key:
  RED- unhelpful, GREEN- helpful, YELLOW- tittat***
  
Throughout all simulations, populations around canteens could only survive. Colonies were formed mostly as circles around canteens, modelling how human civiliations used to be formed around resource-rich areas. Also, when we increase the harshness of the environment (the tax of the Ghost Gang), the circles become smaller.

The following are the parameters that we considered and their meanings (you can find all of them in the 3rd code box of the notebook.
(Note that each player is considered as to be of size 1x1). 
1) **Height**: The number of players that can be fit vertically on the gameboard.
2) **Width**: The number of players that can be fit horizontally on the gameboard

Together these factors could alter the area of the gameboard and thus the density of the canteens. For a very large area (with the fixed number of canteens), in very few simulations the population eventually died down whereas in most, there were groups of "lucky" people who spawned near a canteen and were able to set up a colony there.

3) We also have 3 parameters which control the **initial number of the population of each type**. Varying the ratio of the starting populations of the 3 types was a simulation that could've been done but we weren't able to analyze it due to shortage of time.
4) **Hours per day** is another parameter that would essentially change the number of moves that each player can make each time before the Ghost Gang comes each time. The overall population increases marginally when hours are increased.
5) **Canteen Food** is the food that each player gets each time they visit the canteen. For a small increase in canteen food, the growth rate of the population increases quite rapidly.
6) **No of days** is the time for which we run the simulation. We tried to set it to a high number to get a good idea of the variation yet limited enough so that each simulation can be run without crashing.
7) **Reproduction threshold** is the food that is required to reproduce. Upon decreasing it slightly, the population booms.
8) History size was an idea that was initially required but we changed our logic.
9) Block size is used for Pygame simulation to control the pixel size of the block.
