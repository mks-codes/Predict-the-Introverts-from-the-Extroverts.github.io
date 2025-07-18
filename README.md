# Personality Prediction from Social Behavior Data

This project is part of a Kaggle competition focused on classifying individuals as Extrovert or Introvert based on their behavioral attributes using machine learning algorithms. I achieved a public leaderboard score of 0.973279, aiming to further improve toward 1.0 accuracy.

Problem Statement
Predict whether a person is an Extrovert or Introvert based on social behavior metrics like:

Time Spent Alone

Stage Fear

Social Event Attendance

Drained After Socializing

Friends Circle Size

Frequency of Posting on Social Media

Going Outside

The goal is to build a highly accurate classification model that can generalize well on unseen data.

Dataset
Columns:

id: Unique identifier for each entry

Time_spent_Alone

Stage_fear

Social_event_attendance

Going_outside

Drained_after_socializing

Friends_circle_size

Post_frequency

Personality (Target: Extrovert or Introvert)

Rows: 18,000 training samples

Missing Values: Handled via KNNImputer

Models Used
Random Forest Classifier (Best Performing: 0.973279)

Support Vector Machine (SVM)

XGBoost Classifier

Ensemble (Voting & Stacking planned for improvement)

⚙Workflow
Preprocessing

Imputed missing values using KNNImputer

Feature scaling with StandardScaler

Label encoding for target

Training

RandomForest, SVM, XGBoost trained independently

GridSearchCV planned for fine-tuning

Prediction

Predictions exported to CSV as:

python-repl
Copy
Edit
id,Personality
0,Extrovert
1,Introvert
...
Performance
RandomForest Score on Kaggle: 0.973279

Leaderboard Rank: 2205 (as of submission)

Files
train.csv: Training dataset

test.csv: Test dataset

submission.csv: Final predictions with id and Personality

notebook.ipynb: Jupyter notebook with full pipeline

README.md: This file

To Do
 Add ensemble voting

 Add stacking classifier

 Perform hyperparameter tuning

 Explore deep learning (optional)

Kaggle Comment (Posted)
“Achieved 0.973279 with RandomForest!  Working on ensemble and hyperparameter tuning to push toward that perfect 1.0 score. Excited to see how far we can optimize!  #ML #Kaggle #PersonalityPrediction”

 Author
Magdum Shaikh
Machine Learning Enthusiast | Data Visualizer | Python Developer
Kaggle Profile | GitHub
