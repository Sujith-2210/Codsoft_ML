# RealWorld-ML-Projects

This repository combines three machine learning projects developed during my Codsoft internship:

- **Churn Prediction**
- **Credit Card Fraud Detection**
- **Spam Detection**

---

## 🚀 Projects Overview

| Project                        | Description                                                    |
|-------------------------------|----------------------------------------------------------------|
| Churn Prediction              | Predicts customer churn using data features like demographics and account info. |
| Credit Card Fraud Detection   | Detects fraudulent transactions using classification models.   |
| Spam Detection                | Classifies emails as spam or not spam using NLP techniques.     |

---

## 📁 Directory Structure

Codsoft_ML/
│
├─ Churn-Prediction/
│ ├─ Churn-Prediction-System.ipynb 
│ └─ Churn_Modelling.csv
│
├─ Credit-Card-Fraud/
│ ├─ Credit-Card-Transactions-Fraud-Detection-System.ipynb
│ └─ Datasets.txt
│
├─ Spam-Detection/
│ ├─ Spam-Detection-System.ipynb
│ └─ Spam.csv
│
└─ README.md # This unified readme

---

## 🛠 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Sujith-2210/RealWorld-ML-Projects.git
   cd RealWorld-ML-Projects
Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
```
Each project folder contains the respective notebook and code. Run notebooks or scripts as needed.

⚙️ Project Details
1. Churn Prediction
Explore and preprocess the Churn_Modelling.csv dataset.

Feature engineer user demographics and account-related metrics.

Train classification models (e.g. Logistic Regression, Random Forest).

Evaluate using accuracy, precision, recall, F1‑score.

Save predictions and model files in models/.

2. Credit Card Fraud Detection
Utilize imbalanced transaction datasets.

Perform sampling (SMOTE / undersampling) and feature scaling.

Train classifiers like XGBoost, Random Forest.

Metrics: ROC‑AUC, precision‑recall.

3. Spam Detection
Load and clean email datasets.

Text preprocessing: tokenization, stop‑word removal, TF‑IDF.

Use naive Bayes or similar classifier.

Evaluate accuracy and confusion matrix.

🧪 Usage Examples
To run any project, activate your environment and execute the relevant notebook or script. For example, for Churn Prediction:

```bash
cd Churn-Prediction
jupyter notebook Churn-Prediction-System.ipynb 
```
Replace with similar commands in other project directories.

📈 Evaluation Results
Churn Prediction: ~X% accuracy, recall, precision.

Fraud Detection: ROC‑AUC around Y%.

Spam Detection: ~Z% overall accuracy, F1‑score.
(Replace X, Y, Z with actual numbers from your notebooks.)
