# Step 1: Set Objective / Problem

### Predicting-University-Admissions
**Task Details**

Using the supplied predictive variables (GRE score, TOEFL score, University Rating, etc) to predict the likelihood of admission of a new candidate.

**Evaluation Criteria**

The best model should be the one that evaluates to have the lowest RMSE overall, and please indicate the error you get on validation set containing the last 100 observations.


# Step 2: Get Data (Engineer, Domain Expert)

* [Here is a link to the dataset](https://www.kaggle.com/mohansacharya/graduate-admissions/tasks?taskId=6)



# Step 3: Explore Data (Analyst, Domain Expert)

* Descriptive Analysis
* Checking for Missing Values
* Check for Correlation


# Step 4: Exploratory Data Analysis

* Python Profiling
* Understanding the distribution of the features.
* Outlier Detection
* Visualization
* Check for Multicollinearity (Detecting Multicollinearity using VIF)

# Step 5: Split Data(Engineer)

* You need fresh data for checking performance
* Split the data into:
    * Training dataset
    * Validation dataset
    * Test dataset
* Key Message : Your ML system is no good to you if it can't deal with new data. It's too easy to build a system that's really good at old data but fails miserably on new. Make sure this is avoided by evaulating performance on fresh data.

# Step 6: Train and Debug(Cross-validation and Hyperparameter tuning)

**Training** : the goal is to run lots of algorithms in parallel on our data and assess the models they produce on the same data.
    * Linear Regressor
    * Random Forest Regressor
    * Decision Tree Regressor
    * Gradient boosting Regressor
    
**Validate and Testing** : 
    * training/tuning/debugging
    * Use performance metric to get the model that evaluates/generalises well on both the training and test dataset.
    
# Step 7: Build Pipeline (Kubeflow Pipeline)


