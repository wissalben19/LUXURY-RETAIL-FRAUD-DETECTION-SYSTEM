# LUXURY-RETAIL-FRAUD-DETECTION-SYSTEM

##### **Project Description**:

This project explores the application of machine learning techniques for detecting fraudulent transactions in the luxury retail sector. Fraud detection in this domain is particularly challenging due to **the extreme class imbalance**, where fraudulent transactions represent only a small fraction of total activity, and the need to balance **security with customer experience.**

The study implements and compares multiple machine learning models, including Logistic Regression, Random Forest, Extreme Random Forest, XGBoost, and a Hybrid Model that combines supervised classification with unsupervised anomaly detection (Isolation Forest). Special attention is given to handling class imbalance, feature engineering, and selecting evaluation metrics appropriate for fraud detection rather than relying on misleading accuracy scores.

The final results demonstrate that higher fraud detection recall can be achieved **(up to 61.54%)** at the cost of low precision **(~4%)**, highlighting a fundamental trade-off in real-world fraud detection systems. The project emphasizes that detecting more fraud improves store protection but increases false alarms, which must be managed carefully in luxury retail environments.

---

##### **Dataset Source and Description**

**Dataset Name:** Card Fraud Detection in Luxury Retail Analytics Dataset
**Source:** Kaggle
**URL:** [https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/pratyushpuri/payment-card-fraud-detection-with-ml-models-2025)
**Type:** Synthetic dataset simulating real-world luxury retail transactions


##### **Dataset Characteristics:**
- **Total transactions:** 2,133
- **Fraudulent transactions:** 66 (3.09%)
- **Legitimate transactions:** 2,067 (96.91%)
- **Features:** 16 original features 
- **Target variable:** Fraud_Flag (0 = legitimate, 1 = fraud)
- **Time Period:** February 2025 - August 2025 (6-month span)
 
The dataset reflects realistic fraud patterns and severe class imbalance commonly observed in financial fraud detection problems.

---
##### **Instructions to Reproduce the Analysis**
**1. Clone the repository:**
git clone https://github.com/wissalben19/LUXURY-RETAIL-FRAUD-DETECTION-SYSTEM.git

**2. Navigate to the project directory:**
cd LUXURY-RETAIL-FRAUD-DETECTION-SYSTEM

**3. Create and activate a virtual environment (recommended):**
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

**4. Install required dependencies:**
pip install -r requirements.txt

**5. Open the Jupyter Notebook:**
jupyter notebook

**6. Run the notebook** Mini_Projet_ML2_Bnezahi_Wissal.ipynb 

---
##### **Required Dependencies and Versions***

The project was developed and tested using the following libraries:
- Python 3.9+
- numpy >= 1.23
- pandas >= 1.5
- scikit-learn >= 1.2
- imbalanced-learn >= 0.10
- xgboost >= 1.7
- matplotlib >= 3.6
- seaborn >= 0.12
- jupyter >= 1.0

---
