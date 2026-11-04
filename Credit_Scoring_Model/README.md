# CodeAlpha Credit Scoring Model

## Project Overview

This project uses machine learning to classify credit applicants based on the German Credit dataset. The objective is to explore how classification algorithms can help identify applicants with different credit-risk profiles.

## Objectives

* Explore and preprocess credit data.
* Train machine-learning classification models.
* Compare model performance using evaluation metrics.
* Analyze the identification of bad-credit cases.

## Dataset

**Dataset:** German Credit Data

* 1,000 records
* 20 input features
* 1 target column

The target distinguishes good-credit and bad-credit applicants. In the standard dataset, the original labels are 1 (good credit) and 2 (bad credit).

Dataset file: `german.data`

## Technologies Used

* Python
* Jupyter Notebook
* pandas
* NumPy
* Matplotlib
* scikit-learn

## Machine Learning Models

The project compares four classification algorithms:

1. Logistic Regression
2. Decision Tree
3. Support Vector Machine (SVM)
4. Random Forest

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

A comparison chart is included in the notebook.

## Reported Model Comparison

| Model               | Accuracy | Bad-credit Recall | Bad-credit F1-score |
| ------------------- | -------: | ----------------: | ------------------: |
| Logistic Regression |      78% |             53.3% |               0.593 |
| Decision Tree       |      57% |             66.7% |               0.482 |
| SVM                 |      76% |             76.7% |               0.657 |
| Random Forest       |      77% |             50.0% |               0.566 |

These are the results currently reported by the project and should be verified against the final notebook outputs.

## How to Run the Project

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open `Credit_Scoring_Model.ipynb` in Jupyter Notebook or VS Code.
4. Ensure `german.data` is in the expected location.
5. Run the notebook cells from beginning to end.

## Conclusion

In the reported comparison, Logistic Regression achieved the highest overall accuracy, while SVM achieved the highest bad-credit recall and F1-score. The preferred model depends on the relative costs of different classification errors and should be selected after appropriate validation.

## Limitations

This project is educational and uses a historical dataset. Its results do not establish that the model is suitable for real lending decisions. Further validation, fairness assessment, and testing on appropriate data would be required before practical use.

## Author

Sudais Khan

## Internship

CodeAlpha — Machine Learning Internship

