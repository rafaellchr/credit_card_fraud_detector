# credit_card_fraud_detector
Built a machine learning model to detect credit card fraud using Kaggle data (European bank, 2 days). Tools used: Python, pandas, matplotlib, NumPy, and scikit-learn.

This project is a machine learning solution to detect fraudulent credit card transactions using a dataset from a European bank over two days. The project demonstrates the end-to-end process from data preprocessing to model evaluation.

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Records: 284,807 transactions
- Features: Numerical features (V1–V28), `Amount`, `Time`, and a `Class` label (1 = fraud, 0 = normal)

## 🛠️ Tools & Libraries

- Python
- NumPy
- pandas
- matplotlib & seaborn
- scikit-learn
- Jupyter Notebook

## 📌 Project Steps

1. **Data Loading & Exploration**
   - View structure, check missing values
   - Visualize class imbalance

2. **Data Preprocessing**
   - Normalize `Amount` and `Time` columns
   - Split data into training and test sets

3. **Modeling**
   - Logistic Regression
   - (Optionally test Decision Tree or Random Forest)

4. **Evaluation**
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Curve

## 📈 Results

- The model was able to detect fraud effectively despite class imbalance.
- High precision and recall were achieved with logistic regression after tuning.

## 📁 Project Structure

