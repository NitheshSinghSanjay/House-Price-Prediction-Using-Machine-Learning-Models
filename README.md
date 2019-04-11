# House-Price-Prediction-Using-Machine-Learning-Models

## Overview
This project carried out a systematic investigation to predict the final price of each home using machine learning techniques. Various machine learning techniques such as multiple linear regression (base model), random forest regression and polynomial regression were applied to the dataset to compare the results.

The data describes the sale of individual properties, various features and details of each house in Ames, IW from 2006 to 2010. The dataset comprises of 80 explanatory variables which include 23 nominal, 23 ordinal, 14 discrete, and 20 continuous variables. 
The programs were implemented using Python, by using core libraries like pandas, scikit–learn, NumPy.

Backward elimination algorithm is applied in building optimal model and selection of features over 270 independent variables with approximately 7,91,320 observations. K-fold cross validation technique is used to measure the performance of all the models. A good high R- squared values with low variance are recorded for linear models.

In order to select a good prediction model, all the regression models are explored and compared with each other. Results from K fold cross validation indicates high R-squared values for MLR and Random forest, stating a high level of performance when applied on an actual test set. Each model is evaluated with kaggle score checker against top performing models. My Random forest model achieved the score of 0.14696, which is better compared to my base model Multiple linear regression (kaggle score 0.16854) and Polynomial regression (kaggle score 0.24399).

## Results

![fitness comparison](bgraph.PNG)

The above bar graph shows comparison of fitness scores of custom models and top 3 models from kaggle.

![Model comparison](model_comparison.PNG)

The above scatter plot shows predicted house prices of custom models, Mayumi’s, Zubair’s, and Boris’s models. The custom Random forest and MLR shows similar trends on the graph. The highest expense for a home predicted in MLR is $700,000, while Random forest predicted the highest expense for a home to be $620,000 and Polynomial predicts $1,000,000. Highest expense predicted in Mayumi’s model is approximately $640,000, while Boris’s model predicted highest expense of the home to be nearly $1,400,000. From the graph, we can notice that custom  Random forest model and Zubair’s random forest shows the similar trends and highest expense predicted in Zubair’s model for a home to be $540000.
