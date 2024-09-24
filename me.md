# Machine Learning and Statistical Models to Predict All-cause Mortality in Type 2 Diabetes

## Overview
This repository contains the necessary scripts and guidelines for data selection, preprocessing, model training, testing, and result exporting in the paper Machine Learning and Statistical Models to Predict All-cause Mortality in Type 2 Diabetes: Results from the UK Biobank Study
## Data Selection
- **Dataset**: Located in `/data`. 
- **Selection Criteria**: Refer to `selection_criteria.md` for details on dataset criteria.

## Data Preprocessing
- **Scripts**: Located in `/preprocessing`.
- **Steps**: 
  1. Run `clean_data.py` to remove duplicates and handle missing values.
  2. Execute `feature_engineering.py` to create and select features.
  3. Use `split_data.py` to divide the data into training, validation, and test sets.

## Model Training
- **Scripts**: Located in `/training`.
- **Process**: 
  1. Choose a model from the models described in `model_selection.md`.
  2. Train the model using `train_model.py` with the preprocessed data.
  3. Adjust hyperparameters as needed in `hyperparameter_tuning.py`.

## Model Testing
- **Scripts**: Located in `/testing`.
- **Evaluation**: 
  1. Test the model with `test_model.py`.
  2. Evaluate performance using metrics defined in `evaluate_model.py`.

## Result Exporting
- **Scripts**: Located in `/export`.
- **Output**: 
  1. Generate predictions with `generate_predictions.py`.
  2. Export results to a CSV file using `export_results.py`.
