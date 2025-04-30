# ML-Pipeline-Runner
This project parses a JSON configuration file to build an end-to-end machine learning pipeline using `scikit-learn`. It supports both regression and classification, based on the prediction type and selected models in the JSON.


## Features
- JSON-driven configuration
- Feature imputation (custom values)
- Feature generation (pairwise interactions)
- Feature reduction (PCA, Tree-based)
- Classification using selected models (e.g., RandomForestClassifier)
- GridSearchCV for hyperparameter tuning
- Model evaluation using accuracy and classification report

## How to Run

1. Launch google colab

2. Open `solution.ipynb`.

3. Run all cells to execute the pipeline.
