### Titanic Survival Prediction

This project aims to predict the survival of passengers on the Titanic based on various features such as age, gender, ticket class, and fare.

#### Data Exploration and Cleaning
- Loaded datasets and checked for null values.
- Explored dataset statistics and correlations.
- Visualized data to understand the distribution of features and survival rates.
- Conducted analysis on factors like gender, ticket class, and age.

#### Feature Selection and Engineering
- Selected relevant features for training, including age, ticket class, and embarked location.
- Filled missing values in age and embarked columns.
- Converted categorical variables like gender and embarked location into numerical values.

#### Model Building and Evaluation
- Split the data into training and testing sets.
- Utilized various machine learning algorithms such as Logistic Regression, Support Vector Machines, Naive Bayes, KNN, and Decision Trees.
- Evaluated models using accuracy scores and confusion matrices.
- Selected the Naive Bayes algorithm for its accuracy score of 76%.

#### Conclusion
- The Naive Bayes algorithm was chosen as the best model for predicting survival on the Titanic, achieving an accuracy of 76%.
- Further optimization and hyperparameter tuning could potentially improve the model's performance.
