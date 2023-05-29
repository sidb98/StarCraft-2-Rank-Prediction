# StarCraft-2-Rank-Prediction

This repo contains my approach to develop a model for predicting a players rank by analysing StarCraft 2 player performance data in ranked games.

Below are the key findings from my analysis:

- Need more data on low and high rank
- All features were statistically significant for rank prediction
- Model can be used to scout for Pro players & Strategy Development
- Need new features for better Rank Prediction

Based on the EDA and modeling results, here are a few suggestions to imporve the dataset
  
- More Detailed Gameplay Data: The top features in our model are mostly related to the player's actions during the game. If we could collect more detailed data about these actions, such as the types of actions performed or the sequence of actions, that could potentially improve the model. Data like Race Selection, Average Unspent Resources, Time Spent Supply Capped, Resource Collection Rate.
- More Data on Less Common Ranks: Our dataset was imbalanced with fewer examples of players with very high or very low ranks. Collecting more data on these players could help the model learn to predict these classes better.
- Time Series Data: Starcraft is a real-time strategy game, so the sequence of actions can be very important. If we could collect time-series data about the actions taken by players during the game, that could potentially be very useful.
- Meta-Game Data: Information about the game state, such as the number of units or the type of units a player has at different times, could also be useful.
 
 
