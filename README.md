## CodTech_02
# Fraud Detection System

## Overview
This project focuses on developing a fraud detection system using machine learning techniques to identify fraudulent transactions in financial datasets. The system leverages anomaly detection algorithms to distinguish between normal and fraudulent transactions effectively.

## Dataset
The dataset used in this project contains transaction data with the following columns:

- **Time**: Seconds elapsed between the first transaction and the subsequent transactions.
- **V1, V2, ..., V28**: Principal components obtained from PCA transformation of the original feature set.
- **Amount**: Transaction amount.
- **Class**: Target variable (0 for non-fraudulent, 1 for fraudulent transactions).

## Key Features
1. **Data Loading and Preprocessing**:
   - Handles missing files and errors gracefully.
   - Ensures all features are scaled for model compatibility.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes the distribution of fraudulent vs. non-fraudulent transactions.
   - Analyzes the transaction amounts and time distributions.

3. **Model Training**:
   - Implements anomaly detection algorithms such as Isolation Forest and Local Outlier Factor.
   - Evaluates models using metrics like accuracy, precision, recall, and F1-score.

## Project Structure
- **`fraud_detection.py`**: Contains the main implementation.
- **Dataset**: `card_detection.csv` is the dataset used for this analysis.
- **Visualizations**: EDA plots generated for better insights.

## Prerequisites
- Python 3.7+
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the dataset (`card_detection.csv`) in the project directory.

## Usage
Run the following command to execute the project:
```bash
python fraud_detection.py
```

## Results
The system identifies anomalies in the dataset, flagging fraudulent transactions. Visualizations and performance metrics are displayed during execution.

## Key Learnings
- Practical experience in handling financial datasets.
- Understanding and implementing anomaly detection techniques.
- Evaluating model performance using classification metrics.
- Visualizing results for better interpretability.

## Future Scope
- Enhance the model using advanced techniques such as deep learning.
- Explore more datasets for better generalization.
- Implement real-time fraud detection mechanisms.

---
Feel free to contribute to this project by reporting issues or suggesting enhancements!

