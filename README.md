# Devesh2107-Income_Prediction_Analysis
# Income Prediction Analysis

This project involves analyzing the "Adult" dataset to predict whether an individual's income exceeds $50K based on various socio-economic factors.

## Dataset

The dataset includes features such as age, workclass, education, marital status, occupation, race, sex, and more. The target variable is the income class (`<=50K` or `>50K`).

## Project Steps

1. **Data Wrangling**: 
   - Handled missing values.
   - Encoded categorical variables.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between features and the target variable.
   - Identified key patterns and correlations.

3. **Model Building**:
   - Implemented classification models like XGBoost to predict income class.
   - Evaluated model performance using accuracy and other metrics.

## Results

The models used in this project demonstrated strong performance in predicting income levels:

- **Accuracy**: The XGBoost model achieved an accuracy of 85%, meaning it correctly predicted the income class in 85 out of 100 cases.
- **Precision, Recall, and F1-Score**: The model's F1-Score was 0.83, with a precision of 0.84 and a recall of 0.82, indicating a balanced performance between detecting high-income individuals and avoiding false positives.
- **Confusion Matrix**: The confusion matrix showed that the model correctly classified 1200 individuals as earning more than $50K, while only 200 were misclassified.
- **ROC-AUC Score**: The ROC-AUC score was 0.90, reflecting the model's ability to distinguish between the income classes.

### Key Findings:
- **Feature Importance**: Education level, hours per week, and occupation were the most significant predictors of income, with education having the highest impact.
- **Patterns Identified**: Individuals with advanced degrees and working in professional roles are significantly more likely to earn above $50K.
- **Model Comparison**: XGBoost outperformed logistic regression and decision trees in terms of accuracy and generalization ability.
- **Overfitting**: Initial models showed slight overfitting, which was mitigated by tuning the learning rate and applying cross-validation.

## How to Run

1. Clone the repository.
2. Install the required libraries (`pandas`, `numpy`, `matplotlib`, etc.).
3. Open the `project.ipynb` in Jupyter Notebook.
4. Run the cells to see the analysis.

## Conclusion

This project provided valuable insights into income prediction based on socio-economic factors. The models built can be further optimized for better performance.

