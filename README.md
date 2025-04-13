# 🚨 Bank Account Fraud Detection using Machine Learning

This project tackles the challenge of detecting fraudulent bank account openings using the **Bank Account Fraud (BAF)** dataset, released at **NeurIPS 2022**.  
The dataset is synthetic but realistic, containing over 1 million samples with extreme class imbalance and several types of bias to simulate real-world conditions.

## 📌 Dataset Highlights
- 1 million rows with 30 features
- Highly imbalanced (approx. 1% fraud cases)
- Includes protected attributes (e.g., age group, employment status, % income)
- Designed to test fairness, robustness, and real-world performance
- Released with 6 challenge variants — this project uses the **Base** variant  
- Official repo: [feedzai/bank-account-fraud](https://github.com/feedzai/bank-account-fraud)

## 🔍 Project Workflow
- 📊 **Data Analysis** and visualization
- 🧹 **Data Cleaning**: Missing values, -1 placeholders
- 🔎 **Feature Selection**: ExtraTreesClassifier & Chi²
- ⚖️ **Imbalanced Classes Handling**: SMOTE-ENN
- 🧠 **Model Training**:
  - Logistic Regression
  - Random Forest
  - AdaBoost
  - Bagging
  - Gradient Boosting
  - XGBoost
- ⚙️ **Ensemble Models**:
  - Voting Classifier
  - Stacking Classifier
- 🔎 **Evaluation Strategy**:
  - ROC AUC
  - Accuracy
  - Precision, Recall, F1
  - **Recall @ 5% FPR** *(as recommended by the BAF paper)*

## 📈 Best Model Results (Voting Classifier)
- **Recall @ 5% FPR**: `0.51`
- **ROC AUC**: `0.8772`
- **Accuracy**: `94.5%`

> The metric Recall@5%FPR was used due to the imbalanced nature of the dataset and the importance of reducing false negatives in fraud detection.


## 🔗 Links
- 💼 [LinkedIn – Rayan Saleh](https://www.linkedin.com/in/rayan-saleh-b12a3132a/)
- 🧠 [GitHub Profile](https://github.com/RayanAlDwlah)
- 📂 [Project Repository](https://github.com/RayanAlDwlah/bank-account-fraud-detection)

## 🙌 Acknowledgment
Thanks to [Feedzai Research](https://research.feedzai.com/) for releasing this rich dataset to the community.

---

*If you’re working on fraud detection or imbalanced data problems, I’d love to connect and hear your insights!*
