# Credit Card Fraud Detection

Detect the Undetectable – Secure Every Transaction.

This project uses machine learning techniques to identify fraudulent credit card transactions. It addresses the challenges of class imbalance and real-world data preprocessing to build an accurate and efficient fraud detection system.

## Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Total Transactions: 284,807
- Fraudulent Cases: 492
- Features: 30 anonymized numerical features (PCA-transformed), including `Time`, `Amount`, and `Class` (target label)

---

## How to Run

1. Clone the repository
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
  

2. Create and activate a virtual environment (optional but recommended)

   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
    

3. Install the required packages
   pip install -r requirements.txt
    

4. Run the Python script
   python src/fraud_detection.py
    

---

## Techniques Used

- Data Preprocessing
  - Feature scaling using StandardScaler
  - Removal of irrelevant columns
- Model Training
  - Random Forest Classifier
- Evaluation Metrics
  - Confusion Matrix
  - Classification Report (Accuracy, Precision, Recall, F1 Score)
- Optional: Handling Class Imbalance (e.g., SMOTE or undersampling)

---

## Results and Performance

The model is evaluated on various classification metrics, with a special focus on precision and recall for detecting the minority fraud class. The aim is to minimize false negatives and false positives in a highly imbalanced dataset.

