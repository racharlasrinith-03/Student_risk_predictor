# Student Academic Risk Prediction — Final Report

## 1. Executive Summary
Develop a binary ML classifier to identify students who may be academically at
risk early enough for appropriate support.

## 2. Problem Definition
**Task:** Binary classification.

**Target:** `at_risk`.

**Inputs:** Student academic, attendance, participation, behavioral and
support-related variables.

## 3. Real-World Value
Early identification can help institutions prioritize students for academic
support. Predictions should be treated as decision support, not as a final
judgment about a student.

## 4. Research / Existing Approaches
Document literature or authoritative sources on academic-risk prediction,
classification, class imbalance, and interpretable ML. Add citations here
after completing the required literature review.

## 5. Dataset and Provenance
Document the exact CSV source, collection/generation process, license,
dimensions, target definition, and limitations. See `data/DATASET_SOURCE.md`.

## 6. Features
See `data/DATA_DICTIONARY.csv`.

## 7. Data Preparation
Describe missing values, duplicates, categorical encoding, class distribution,
train/test split, and prevention of data leakage.

## 8. Models Compared
- Logistic Regression
- Decision Tree
- Random Forest

Report the exact results from the executed notebook.

## 9. Validation and Tuning
Describe 5-fold cross-validation and GridSearchCV. Report best parameters and
validation score from the executed run.

## 10. Final Evaluation
Report Accuracy, Precision, Recall, F1-score, confusion matrix and any other
appropriate metrics on an untouched test set.

## 11. Failure Analysis
Discuss false positives and false negatives separately. Explain why missed
at-risk students are important and what data limitations could contribute.

## 12. Feature Interpretation
Report feature importance or another appropriate explainability method.
Do not interpret feature importance as causal evidence.

## 13. Engineering
Explain project structure, requirements, model serialization and prediction
workflow.

## 14. Reproducibility
Document Python version, package versions, random seeds, dataset path and
exact commands used.

## 15. Limitations and Risks
Discuss dataset representativeness, label quality, potential bias, temporal
drift, privacy and the consequences of prediction errors.

## 16. Future Work
Consider external validation, probability calibration, stronger leakage
checks, additional models, explainability and deployment monitoring.

## 17. Conclusion
Summarize the selected model and evidence from the final evaluation.
