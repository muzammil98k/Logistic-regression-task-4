# Logistic Regression Binary Classification

This project demonstrates **binary classification** using Logistic Regression on the Breast Cancer Wisconsin dataset.

## Steps Performed
1. **Dataset Loading & Preprocessing**
   - Loaded the dataset from `data.csv`
   - Dropped unnecessary columns (`id`, `Unnamed: 32`)
   - Encoded target variable (`M=1`, `B=0`)

2. **Train/Test Split & Standardization**
   - Split data into 80% training and 20% testing
   - Standardized features using `StandardScaler`

3. **Model Training**
   - Used `LogisticRegression` with `max_iter=500`

4. **Evaluation**
   - Confusion Matrix (visualized with heatmap)
   - Precision, Recall, F1-score from Classification Report
   - ROC-AUC score and ROC Curve

5. **Threshold Tuning & Sigmoid Function**
   - Explained the sigmoid function
   - Adjusted classification threshold (default = 0.5, example = 0.3)
   - Compared metrics and confusion matrix

## Files
- `logistic_regression_classification.ipynb` → Jupyter notebook with code and explanations
- `data.csv` → Dataset used (Breast Cancer Wisconsin)

## Requirements
Install dependencies before running the notebook:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
