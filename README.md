# Prohack-Solution--D1D-Team
Our solution to the data science hackathon by McKinsey: Prohack, by our team D1D, which was ranked 4th on public leaderboard and 25th on private leaderboard. This is our first data science competition and we are very glad with the results, we worked very hard on this.
There are 2 notebooks in this repo with detailed approach: one is for the 1st task and 2nd is for the 2nd task.

![Prohack Cover](https://i.imgur.com/9Vji9vf.png)

## About Prohack:

The hackathon started on May, 18th, 2020 and ended on June 21st 2020. The dataset had around 80 features and few more than 4000 rows (train and test) with 890 rows on test set. 
We had two tasks: Predict a target variable y which represents the well being index for a galaxy, and a second task where we had to find an optimal allocation of 50k energy units. Score is computed with RMSE metric with 80% for 1st task and 20% for 2nd task.

## What we did in short ? 

To describe our approach in short (more details in the notebook), we started by cleaning and traiting missing values and outliers, we built 3 stacked models with 3 different feature sets: one using all features, one using encoded features from an autoencoder and the last model using all features + mean,min,max,std of each feature (over 500 features). Then we blended results of the 3 models using a geometric mean.

For the 2nd task we took an informal approach by analysing the results of the 1st task and assigning values using a linear decrease with 3 different slopes (more details in the notebook).

## What we used ?

We used several open source python packages and frameworks: Pandas, Numpy, SciKit Learn, Vecstack, Catboost, LightGBM, XGBoost, Scipy, Matplotlib and Keras (with Tensorflow 2).

## Team Members:

- SOUAMES Mohamed Annis - Industrial Engineering student at Polytechnic School of Algiers - (ENP Alger)
- MOHAMMEDI Larbi Abderrahmane - Industrial Engineering student at Polytechnic School of Algiers - (ENP Alger)
- MELLAK Rostane Mohamed Zakari   - Industrial Engineering student at Polytechnic School of Algiers - (ENP Alger)
- BOUDJELOUAH Rayane Yaniss - Industrial Engineering student at Polytechnic School of Algiers - (ENP Alger)
