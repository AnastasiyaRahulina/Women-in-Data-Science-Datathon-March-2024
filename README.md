# Women-in-Data-Science-Datathon-March-2024
This reposotory contains EDA, and predictive models build during participation in Women in Data Science Datathon 2024, Challenge #1

Datathon was held on Kaggle platform https://www.kaggle.com/competitions/widsdatathon2024-challenge1

The main task was to made a predictive model for classification if patients received metastatic cancer diagnosis within 90 days of screening.

Dataset contained different medical, socioeconomical, as well as enviromental features.

Feature preperation included NLP-coding of diagnosis description text.

Other technicues used was: 

- SMOTE for target balancing/SMOTE-NC for balancing categorical features
- SHAP for feature selection
- Optuna for hyperperemeters tuning
- Autogluon for searching of the best performed models
- Stacking and Voting Classifiers
- Ensemble of different models including SVM, RF, GB and Catboost

During the competition numerous models were bild. The best performance was tracked on the models, based on XGBoost algorythm.

# XGBoost
