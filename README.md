# Wine-Quality-Prediction
This project predicts the quality of white wine based on its physicochemical properties such as acidity, sugar content, pH, and alcohol level.
The quality scores are categorized into three classes — Bad, Average, and Good thus predicted using a Random Forest Classifier.

# Dataset
- Name: winequality-white.csv
- Source: UCI Machine Learning Repository
- Description: Contains 4,898 white wine samples with 11 physicochemical features and a quality score.

# Technologies used
- Python
- Pandas & NumPy (Data handling & preprocessing)
- Scikit-learn (Model building & evaluation)
- Matplotlib (Data visualization)

# Project OverflowData Loading & Exploration – Read the dataset and view initial records.
- Data Preprocessing – Convert quality scores into categorical labels (Bad, Average, Good) and encode them numerically.
- Train-Test Split – Divide dataset into training and testing sets (80%-20%).
- Model Training – Train a Random Forest Classifier.
- Model Evaluation – Use classification report and confusion matrix to assess performance.
- Visualization – Display confusion matrix and quality distribution in test data.

# Results
- Evaluation Metrics: Precision, Recall, F1-score, and Accuracy from classification report.
- Confusion Matrix: Visual representation of prediction performance.
- Class Distribution: Bar chart showing number of wines in each category in the test set.
