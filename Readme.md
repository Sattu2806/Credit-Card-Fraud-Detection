# Credit Card Fraud Detection

This project involves developing a credit card fraud detection system by implementing and comparing multiple machine learning models. The primary objective is to accurately identify fraudulent transactions from a highly imbalanced dataset.

---

## Project Overview

Fraudulent credit card transactions cause significant financial losses annually. This project leverages machine learning techniques to address this problem. We implemented multiple models to compare their effectiveness and improve fraud detection accuracy.

---

## Methods Used

1. **Data Preprocessing:**

   - Addressed class imbalance using undersampling techniques.
   - Scaled features to standardize the dataset for model training.
   - Explored the dataset using statistical summaries, histograms, and correlation matrices.

2. **Machine Learning Models:**

   - Decision Tree
   - Random Forest
   - AdaBoost
   - XGBoost

3. **Evaluation Metrics:**

   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC Curve

4. **Visualization Tools:**

   - Used libraries such as Matplotlib and Seaborn for creating insightful plots to understand data distribution and model performance.

---

## Key Learnings

- **Data Imbalance Handling:**
  - Learned the impact of class imbalance on machine learning models and addressed it using undersampling techniques.
- **Feature Scaling:**
  - Improved model performance by scaling features for uniformity.
- **Model Comparison:**
  - Gained insights into the strengths and weaknesses of various machine learning models.
- **Visualization:**
  - Leveraged data visualization to make data-driven decisions during preprocessing and model evaluation.

---

## Outputs

- **Data Analysis Outputs:**

  - Statistical summaries and visualizations highlighted key patterns in the dataset.
  - Identified correlations and trends to guide feature selection.

- **Model Results:**

  - Achieved high accuracy and AUC scores in detecting fraudulent transactions.
  - Demonstrated the effectiveness of ensemble methods (Random Forest, AdaBoost, XGBoost) in handling imbalanced datasets.

- **Visualizations:**

  - Plotted confusion matrices, feature importances, and ROC-AUC curves for comparative analysis.

---

## Technologies and Tools

- **Programming Language:** Python
- **Libraries:**
  - Pandas for data manipulation
  - Matplotlib and Seaborn for visualization
  - Scikit-learn for implementing machine learning models
  - XGBoost for gradient boosting

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Sattu2806/Credit-Card-Fraud-Detection
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Fraud_Detection_Credit_Card.ipynb
   ```

---

## Conclusion

This project highlights the importance of robust data preprocessing and model selection in achieving high accuracy in fraud detection. By comparing multiple models, we identified the most effective techniques for addressing imbalanced datasets and detecting anomalies.

