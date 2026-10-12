# Wine Quality Prediction Using Machine Learning

## About the Project
This project uses physicochemical properties of red wine to predict wine quality categories using machine learning classification algorithms. It was completed as part of my **Data Analytics Internship at Oasis Infobyte**.

## Objectives
- Explore the red wine quality dataset.
- Analyze chemical feature distributions.
- Investigate correlations between features.
- Examine class imbalance in quality scores.
- Train and compare three machine learning classifiers.
- Identify important features influencing predictions.

## Dataset
- **Source:** [Red Wine Quality Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- **Target variable:** `quality`
- **Features:** Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Load and inspect the dataset.
2. Check missing values, duplicates, and data types.
3. Visualize quality score distributions and chemical features.
4. Create a correlation heatmap.
5. Analyze class imbalance.
6. Group quality scores into three classes:
   - **Low:** Quality score <= 5
   - **Medium:** Quality score = 6
   - **High:** Quality score >= 7
7. Split the dataset into training and testing sets using stratification.
8. Train Random Forest, SGD Classifier, and Support Vector Classifier (SVC).
9. Evaluate models using accuracy, precision, recall, F1-score, classification reports, and confusion matrices.
10. Visualize Random Forest feature importance.
11. Compare model performance and identify a suitable model.

## Machine Learning Models
- **Random Forest Classifier:** An ensemble model based on multiple decision trees.
- **SGD Classifier:** A linear classification model trained using stochastic gradient descent.
- **Support Vector Classifier (SVC):** A classifier that learns decision boundaries between quality categories.

## Evaluation Metrics
- Accuracy
- Macro Precision
- Macro Recall
- Macro F1-score
- Weighted F1-score
- Confusion Matrix

## Key Learnings
- Performing exploratory data analysis.
- Handling imbalanced classification data.
- Applying stratified train-test splitting.
- Comparing different machine learning algorithms.
- Interpreting feature importance and evaluation metrics.

## Conclusion
This project provided hands-on experience in data exploration, feature engineering, classification, and model evaluation to predict wine quality categories.

## Internship Details
- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics

## Author
Created as part of my data analytics internship project portfolio.
