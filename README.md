# Student Academic Risk Prediction

## Objective
Build a binary classification system that predicts whether a student is
academically at risk (`at_risk`) from academic, attendance, behavioral and
support-related variables.

## Existing notebook
`notebooks/student_risk_prediction.ipynb` contains the original project work.

## Reproducible pipeline
The `src/train.py` script provides a leakage-safe preprocessing/model pipeline:
- train/test split with stratification
- numerical/categorical preprocessing
- OneHotEncoder with unknown-category handling
- class-weighted Random Forest
- 5-fold stratified cross-validation
- F1-based GridSearchCV
- model serialization

## Run
1. Put the original dataset at `data/student_risk_ml_dataset.csv`.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Run:
   `python src/train.py`
4. The trained model is written to:
   `models/student_risk_model.pkl`

## Prediction
Use `src/predict.py` with the same feature schema used for training.

## Important
The official Track 2 problem statement and the original CSV provenance were
not included in the notebook itself. Do not invent an official Problem ID,
dataset source, or performance claim. Add those from the official materials
before submission.
