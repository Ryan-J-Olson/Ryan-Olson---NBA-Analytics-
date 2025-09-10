# NBA Outcome Prediction — Ryan-Olson

Predict whether the home team will win an NBA game using historical team statistics and machine learning.
This repo contains a small pipeline: data generation (for demo), feature creation (no leakage), model training, evaluation, and a CLI for predicting new matchups.

## Repo structure
nba-outcome-prediction/
├─ data/ # raw + processed CSVs
├─ images/ # plots saved during evaluation
├─ models/ # saved model files (.joblib)
├─ notebooks/ # optional exploratory notebooks
├─ src/
│ ├─ generate_sample_data.py
│ ├─ data_prep.py
│ ├─ train_model.py
│ └─ predict.py
├─ requirements.txt
├─ .gitignore
└─ README.md
