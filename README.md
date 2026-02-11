# seed-classification-ml
# Wheat Seeds Classification (Machine Learning)

This project applies classical machine learning techniques to classify wheat seed varieties using the Seeds dataset, with a focus on preprocessing, model selection, and robust evaluation.

## Dataset
- Seeds dataset with 199 samples
- 7 numerical features describing physical characteristics of wheat kernels
- 3 balanced classes

## Data Preprocessing
- Checked for missing values and duplicates
- Applied feature standardization
- Verified class balance (no resampling required)
- Conducted feature selection experiments (RFE, SelectKBest)
- Trained final models using all features due to performance drop after feature removal

## Models Implemented
- Logistic Regression
- k-Nearest Neighbors (k-NN)

## Model Evaluation
- Stratified 10-Fold Cross-Validation
- F1-score as the primary evaluation metric
- Confusion Matrix for class-level analysis

Both models achieved strong performance (F1-score > 0.90).

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib


## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib

