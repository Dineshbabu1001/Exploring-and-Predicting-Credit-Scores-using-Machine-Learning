📊 Exploring and Predicting Credit Scores using Machine Learning 📊

In this project, I used a Credit Score Classification dataset to explore and predict credit scores using various machine learning techniques. Here's a breakdown of the code and its key components:

1️⃣ Data Visualization:

I started by visualizing the categorical variables in the dataset. Using seaborn and matplotlib, I created bar plots, histograms, and pie charts to analyze the distributions and relationships between these variables and the credit scores.

2️⃣ Data Preprocessing:

To prepare the data for machine learning models, I checked for missing values and encoded categorical variables using label encoding from the sklearn library. This step ensures that the data can be processed by the models effectively.

3️⃣ Model Building and Evaluation:

Next, I split the data into training and testing sets, with a 70-30 ratio. I used a Decision Tree Classifier and a Random Forest Classifier to build predictive models for credit scores. Grid search was performed to find the best hyperparameters for each model.

4️⃣ Model Performance Evaluation:

I evaluated the performance of the models using accuracy, F1 score, precision, recall, and Jaccard score. Additionally, I visualized the feature importance using bar plots to understand which variables have the most significant impact on credit scores.

5️⃣ SHAP Analysis:

Finally, I conducted a SHAP (SHapley Additive exPlanations) analysis to interpret the models' predictions. SHAP values provide insights into the contribution of each feature towards the final prediction.

The results showed that both the Decision Tree and Random Forest models achieved high accuracy in predicting credit scores, with the Random Forest model slightly outperforming the Decision Tree model.
