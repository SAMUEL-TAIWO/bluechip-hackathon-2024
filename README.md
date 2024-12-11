# Bluechip Data & AI 2024 Summit Hackathon: Predicting Loan Approval

## Overview
I participated in the **Bluechip Data & AI 2024 Summit Hackathon**, where the challenge was to develop accurate and robust machine learning models for predicting loan creditworthiness. The goal was to identify individuals most likely to repay loans, thereby minimizing financial risk for lending institutions. The challenge emphasized creating models that balance precision and recall to enable informed lending decisions in a dynamic environment.

## Objective
The main objective was to develop machine learning models capable of predicting whether a borrower would be approved for a loan based on their creditworthiness. The evaluation focused on:

- **Model Accuracy**: The precision of predictions.
- **Feature Engineering**: How well participants extracted insights from the data.
- **Precision vs. Recall**: Balancing false positives and false negatives.

## Approach

| Step                     | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Data Preprocessing**    | Cleaned the dataset, handled missing values, and encoded categorical variables. |
| **Feature Engineering**   | Selected and derived relevant features influencing creditworthiness. |
| **Model Development**     | Built multiple models, including Logistic Regression, Random Forest, and XGBoost. |
| **Model Evaluation**      | Evaluated models using metrics like accuracy, precision, recall, and F1-score. |
| **Hyperparameter Tuning** | Tuned model parameters using grid search and cross-validation for optimal performance. |
| **Final Prediction**      | Generated final predictions on the test set based on the trained models and submitted results for evaluation. |

## Submission
The final submission required predicting the probability for the TARGET variable for each ID in the test set.

## Evaluation Metrics
Submissions were evaluated based on the accuracy of the predictions, with a particular focus on how well the models balanced precision and recall to minimize risk while making accurate creditworthiness predictions.

## Results
The model I built was evaluated on the hackathon's system, achieving an **accuracy of 0.834** on the test set. The dataset provided included training, validation, and test sets, and I was able to make predictions on the test set. Several algorithms were explored, including **Logistic Regression**, **Random Forest**, **XGBoost**, **LightGBM**, **CatBoost**, and **LightSVM** (Support Vector Machine). **LightGBM** emerged as the best-performing model, yielding the highest accuracy.

## Conclusion
By participating in this hackathon, I gained valuable experience in **financial analytics**, **predictive modeling**, and working with real-world datasets to make data-driven decisions in the financial services sector.

Feel free to explore the notebook where I implemented the models and fine-tuned them for better performance. You can dive deeper into the approach, data processing, and model selection in the repository.

## Contact
For more information or collaboration, feel free to reach out via email: [samueltaiwo856@gmail.com].

