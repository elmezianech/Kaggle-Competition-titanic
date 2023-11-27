# Kaggle-Competition-titanic
Description :


Hello ! 👋 I'm thrilled to share my debut in the world of Kaggle competitions with my solution for the Titanic: Machine Learning from Disaster competition. In this challenge, we are tasked with predicting which passengers were more likely to survive the tragic sinking of the Titanic.  Public Score: 0.79186

link : https://www.kaggle.com/code/elmezianech/notebook71ac3c60cf

Approach:


Being my first Kaggle competition, I approached this problem with a combination of enthusiasm and a thirst for learning. My notebook walks through my journey, covering aspects of feature engineering, data preprocessing, and model selection. I've added detailed explanations and comments to make the code accessible for others and to showcase my learning process.

Key Features:

- Feature Engineering: As part of my approach, I delved into feature engineering, combining the "SibSp" and "Parch" columns to create a new feature named "Family Size." This allowed me to capture the information about the size of a passenger's family, contributing to the model's predictive power.

- Data Preprocessing: I paid special attention to handling missing values and encoding categorical variables. Notably, I didn't employ standardization since the Random Forest algorithm is not sensitive to feature scaling.

- Model Selection: For this competition, I opted for the Random Forest algorithm, leveraging its ensemble nature for robust predictions. To fine-tune the model and optimize performance, I utilized cross-validation and GridSearchCV. This involved systematically exploring hyperparameter combinations to identify the best configuration for the RandomForestClassifier.

Note: Unlike some models that benefit from feature standardization, Random Forests are inherently robust to varying scales, making them well-suited for datasets with features of different magnitudes.
