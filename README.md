# house_price_pridiction_yhills_capstone_project1
# Fraud Detection in Financial Transactions

## Project Description
This project focuses on detecting fraudulent financial transactions using machine learning models. It employs classification techniques and anomaly detection to identify suspicious activities. The dataset used is the Credit Card Fraud Detection Dataset, which contains a mix of normal and fraudulent transactions.

## Features Implemented
- Data Preprocessing (Normalization, Feature Scaling, Handling Imbalanced Data)
- Classification Models (Random Forest, XGBoost)
- Anomaly Detection using Isolation Forest
- Performance Evaluation (Confusion Matrix, Classification Report, Precision-Recall)
- Visualization with PCA for anomaly detection insights

## Technologies Used
- Python
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Pandas
- Matplotlib
- Seaborn

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/fraud-detection.git
   cd fraud-detection
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset and place it in the project directory.
4. Run the script:
   ```bash
   python fraud_detection.py
   ```

## Dataset
The dataset used is the **Credit Card Fraud Detection Dataset**, which consists of numerical features extracted using PCA. The **Class** column indicates whether a transaction is fraudulent (1) or not (0).

## Model Evaluation Metrics
- **Confusion Matrix**: To analyze the classification performance.
- **Precision, Recall, and F1-score**: To handle imbalanced class distribution effectively.
- **PCA Visualization**: To visualize fraud distribution using anomaly detection.

## Results & Insights
- SMOTE is used to handle class imbalance and improve detection.
- Random Forest and XGBoost provide high accuracy in fraud detection.
- Isolation Forest helps in identifying anomalies effectively.

## Future Enhancements
- Experiment with other anomaly detection models like Autoencoders.
- Implement real-time fraud detection.
- Deploy the model as an API for real-world applications.

## Contributors
- Dhanushni.N
