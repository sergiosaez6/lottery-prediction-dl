# Euromillions prediction with neural networks

First of all, it is important to mention that this project is carried out on an exploratory basis. It is known that predicting the lottery can be an unfeasible task, because it is a random process and past events do not necessarily have to be significant for the future. However, I want to explore how far we can go with this type of analysis.

Euromillions is a lottery that takes place twice a week (on Tuesday and Friday) over all Europe, where you have to predict 5 numbers (from 1 to 50) and two stars (from 1 to 12) in order to win it. This repository contains:
- An exploratory prediction of these numbers with Deep Learning.
- [Retrieved data from the Euromillions draws]([url](https://www.euromillones.com.es/historico/euromillones-anos-anteriores.html)) from 2004 to 2023.
- The results from this prediction.

I will be updating this repository with all the advances I make on it, but the first approach will be to use RNNs considering 7 different variables (each of the five numbers plus two stars) to forecast the next draws.
