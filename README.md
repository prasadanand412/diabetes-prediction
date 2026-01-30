# Diabetes Prediction using LightGBM

End-to-end machine learning project built on a Kaggle healthcare dataset
to predict diabetes risk using tree-based models and cross-validation.

## Models Used
- Decision Tree
- Random Forest
- XGBoost
- LightGBM (final model)

## Techniques
- Native categorical handling (LightGBM)
- Feature engineering
- Stratified K-Fold Cross-Validation
- Out-of-fold prediction blending
- ROC-AUC evaluation

## Results
- Cross-validated ROC-AUC ≈ 0.72–0.73
- Stable generalization across folds

## Project Structure
- `decision_tree.ipynb` – baseline model
- `random_forest.ipynb` – bagging ensemble
- `xgboost.ipynb` – boosting model
- `lightgbm_cv.ipynb` – final CV-blended model
- `submission_lightGBM-cv.csv` – final submission (competition closed)

## Notes
- Raw Kaggle data not included due to licensing.
