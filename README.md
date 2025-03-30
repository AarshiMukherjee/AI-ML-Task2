# AI-ML-Task2
This repository contains how I learnt ML step by step from scratch
<br>
<h1>Data Preprocessing</h1>
<br>
1. Check for Missing Values -- Identify columns with NaN values.<br>
2. Handle Missing Data -- Replace or drop missing values.<br>
3. Convert Categorical Data -- Convert Pokémon types into numerical form.<br>
4. Standardize Numerical Features -- Normalize attack, defense, etc.<br>
5. Feature Selection -- Choose relevant features for the model(excluding out name and keeping rest of the features).<br>
6. Use SMOTE to generate synthetic samples for the minority class (Mega Evolution), addressing class imbalance and improving model performance.
<h1>Evaluating the Model</h1>
<br>
--Split the dataset into training and testing sets  80% training, 20% testing to evaluate the model's performance.
--Used Logistic Regression model to classify Pokemon as Mega-Evolution or Regular.
--Use balanced class weights to address imbalanced classes (Mega Evolutions vs. Regular Pokémon) and ensure the model doesn't favor the majority class.
--Adjust the decision threshold to balance precision and recall, reducing false positives and false negatives.
<h1>Evaluating the Model</h1>
<br>
evaluated the model’s performance by plotting metrics such as: 
--Confusion matrix 
--ROC curve 
Pr--ecision-recall curve

