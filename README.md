
# Welcome to games-analysis repository

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on League of Legends match statistics from Kaggle. 

## Contributors

@NotDaWw (Lin Da Wei) - Machine Learning, Exploratory Data Analysis.<br>
@NtuJiaZe (Ang Jia Ze) - Data Extraction, Exploratory Data Analysis.<br>
@brendanchan03 (Chan Kin Leong) - Data Extraction, Machine Learning.<br>

## Problem Definition
Can we predict the outcome of the match based on 10 minutes worth of data and how can we improve the win rate of a match?

## Models Used

- Gaussian Naive Bayes
- K Nearest Neighbors
- Random Forest
- Decision Tree

## Conclusion

- Random Forest model was the most accurate for our data. However, the difference between all the models isn't that significant which implies that from just the first 10 minutes of the game, we can only roughly be 70% certain about the outcome of the game.<br>
- K Nearest Neighbors model, large numbers of variables in our data, predicted data point may be equidistant to many of the training data, giving inaccurate result.<br>
- From what we gather, the variables blueDeaths,blueKills and blueAssist greatly influence the outcome of the game. Followed by blueDragons killed and blueMinions killed. In order to increase our winrate, we should try to assist our teammates to get kills but not at the expense of our life. If there are no fights, we should prioritize killing the dragon rather than herald. While the dragon is being summoned. We should focus on killing the minions to gain a lead. <br>
 
## Project Takeaway

- Explore other machine learning models such as Gaussian Naive Bayes, K Nearest Neighbors, Random Forest<br>
- Other packages such as PrettyTable, SKlearn<br>
- Collaborating using Google Colaboratory<br>
- Concepts about Precision, Recall, and F1 Score<br>

## References

https://iq.opengenus.org/gaussian-naive-bayes/#:~:text=Gaussian%20Naive%20Bayes%20is%20a,Bayes%20along%20with%20an%20example<br>
https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/#:~:text=Random%20forest%20is%20a%20Supervised,average%20in%20case%20of%20regression<br>
https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html<br>
https://www.kaggle.com/code/alexaraya27/machine-learning-approach-predicting-wins-losses#Using-other-Machine-Learning-Algorithms<br>
https://www.kaggle.com/code/christianmcb/league-of-legends-diamond-classification<br>
 

