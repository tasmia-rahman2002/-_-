# # **Titanic Survival Prediction**

This project uses various machine-learning models to analyze the Titanic dataset to predict passenger survival. It covers data pre-processing, exploratory data analysis, feature engineering, model training, and evaluation.


Here's the workflow of the project: 

1. Imported necessary libraries:
    First I imported essential libraries including pandas, numpy, seaborn, matplotlib, and scikit-learn for data manipulation, analysis, visualization, and modeling.

2. Loaded the dataset:
    This project commenced by loading the Titanic dataset from a CSV file using the pandas library.

3. Data preprocessing:

   Handled missing values by dropping the 'Cabin' column, imputing the mean for 'Age', and the mode for 'Embarked'.
   Converted categorical features ('Sex', 'Embarked') to numerical representations using label encoding.

4. Exploratory Data Analysis (EDA):

   I used descriptive statistics and visualizations to gain insights into the data.
   Including count plots and visualizations showing the relationship between features and survival.

5. Feature Engineering and Selection:

   Selected relevant features for model training (X) and the target variable (Survived, Y).
   Dropped irrelevant columns like 'PassengerId', 'Name', and 'Ticket'.

6. Data Splitting:
   Divided the dataset into training and testing sets using train_test_split to evaluate model performance on unseen data.

7. Model Training:

   Trained using multiple classification models, including Logistic Regression, Random Forest, Decision Tree, Support Vector Classifier (SVC), and XGBoost.
   Fited each model using the training data (X_train, Y_train).

8. Model Evaluation:

   Evaluated each model's performance using the testing data (X_test, Y_test).
   Calculated accuracy scores and generates confusion matrices to visualize prediction results.

**Output:** Presents the evaluation results, including accuracy scores and confusion matrices for each model, to assess their effectiveness in predicting Titanic survival.
