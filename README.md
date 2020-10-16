# Predicting University Admissions
**Task Details**

Using the supplied predictive variables (GRE score, TOEFL score, University Rating, etc) to predict the likelihood of admission of a new candidate.

**Evaluation Criteria**

The best model should be the one that evaluates to have the lowest RMSE overall, and please indicate the error you get on validation set containing the last 100 observations.

[Here is a link to the dataset](https://www.kaggle.com/mohansacharya/graduate-admissions/tasks?taskId=6)

**Work Flow**

We firstly did Data Preprocessing, Cleaning and Exploratory Data Analysis. All the EDAs can be found in the Notebooks and EDA folder.

Based on the analysis from the EDA several machine learning models were created, and the best performing model on the test data is selected.

The selection criteria was based on the lowest RMSE score obtained from the test data.

After much consideraion the ANN model and Bayesian Ridge Model had the best performance of approximately 0.04. 

Correspondingly, a kubeflow pipeline is being prepared for further deployment of the model prepared.
