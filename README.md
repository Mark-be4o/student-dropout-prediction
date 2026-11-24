# Student Dropout Prediction

Predicting student academic outcomes (Dropout, Enrolled, Graduate) with a neural network and XGBoost.

## What it does

Multi-class classification of student outcomes from academic and demographic features, with EDA, preprocessing and a neural network compared against XGBoost.

## Files

- `student_outcomes_classification.ipynb`

## Tools

TensorFlow/Keras, XGBoost, scikit-learn, pandas, Plotly, seaborn

## Dataset

Academic success sample CSV (not included). Based on the public UCI dataset Predict Students' Dropout and Academic Success: https://archive.ics.uci.edu/dataset/697

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Per-class F1 on the test set: Graduate 0.73, Dropout 0.62, Enrolled 0.37 (Enrolled is the hardest class).

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
