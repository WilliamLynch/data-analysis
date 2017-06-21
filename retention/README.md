# Employee Retention Model

For this analysis I used the Human Resource Analytics dataset from Kaggle to develop a model to identify and predict retention.  The ultimate question posed is "Why are our best and most experienced employees leaving prematurely?"

From the Kaggle description:
    Why are our best and most experienced employees leaving prematurely? Have fun with this database and try to predict which valuable employees will leave next. 
    
    Fields in the dataset include:

    Last evaluation
    Number of projects
    Average monthly hours
    Time spent at the company
    Whether they have had a work accident
    Whether they have had a promotion in the last 5 years
    Department
    Salary
    Whether the employee has left
    *This dataset is simulated


# Data Preprocessing

The dataset was preproceed by checking for null values, binarizing categorical variables, normalizing the data, and finally shuffle and sorting so we do not introduce order bias into our algorithm.


# Exploratory Data Analysis

I produced visualizations that help tell the story of the dataset.  This includes relationships between variables, identifying key features which lead to reduced churn, and also summary and descriptive statistics to get an idea of the distributions for each feature and outliers we may be dealing with.

# Predictive Model

Used Scikit Learn to create a supervised learning model which classifies and predicts whether an employee will remain or leave the company.  Models include: Logistic Regression, Knn, SVM, Random Forest Classifiers, Boosting and Bagging Ensemble Classifiers.
