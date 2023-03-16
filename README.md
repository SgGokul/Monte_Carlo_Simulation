# Monte_Carlo_Simulation
Implementation of Monte Carlo Simulation 

A Monte Carlo simulation involves repeated attempts to predict future outcomes. After running the simulation, a distribution of results is generated through thousands or even millions of random trials. This distribution can then be analyzed, and it typically converges to a bell-curve or normal distribution. This aligns with the idea that all natural random events tend to follow a normal distribution given infinite trials. The simulation output confirms this hypothesis. In my model, I assume that the stock price moves randomly at each time step, with the maximum change in value determined by a constant volatility. The price at each step changes to a random number between the previous price multiplied by (1 - volatility) and the previous price multiplied by (1 + volatility), for the sake of simplicity.

![image](https://user-images.githubusercontent.com/107173414/225480538-08a0999c-bcf3-41d3-8090-26c32a42a150.png)

![image](https://user-images.githubusercontent.com/107173414/225480545-d660ac02-d4d6-44ea-94de-361deff6bbf1.png)
