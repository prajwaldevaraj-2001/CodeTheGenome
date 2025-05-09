# CodeTheGenome

🧬 Genetic Variant Classification Using Machine Learning
This project analyzes and classifies genetic variants using data from ClinVar — a public database containing information about human genetic variations and their relationships to diseases. The objective is to build a predictive model to classify these variants into categories such as benign, pathogenic, or uncertain significance.

📚 Context
Genetic variants are often classified by clinical laboratories into categories such as:

Benign

Likely benign

Uncertain significance

Likely pathogenic

Pathogenic

Conflicting interpretations can make clinical decision-making challenging. This project aims to create a machine learning model to assist in predicting variant classification based on publicly available ClinVar data.

🚀 Features
Preprocessing of genetic data

Visualization of missing data patterns

Feature encoding with category_encoders

Classification using CatBoostClassifier

Evaluation using accuracy and other metrics

📦 Requirements
Install required Python libraries:

pip install catboost category_encoders

Additional dependencies:

pandas

numpy

matplotlib

seaborn

missingno

📈 Models Used
CatBoostClassifier, XGBoost (Extreme Gradient Boosting), and LightGBM: Chosen for its efficiency with categorical features and high performance on tabular data.

📊 Results
Model accuracy and confusion matrix are generated to evaluate prediction performance. You can run the notebook end-to-end to reproduce the results.
