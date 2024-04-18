# Credit Card Fraud Detection
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset used in this project is sourced from Kaggle and contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, where 492 out of 284,807 transactions are fraudulent.

### Getting Started
To get started with this project, follow these instructions:

### Prerequisites
Make sure you have the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

### Installation
Clone the repository:
```
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```

### Usage
1. Download the dataset from the provided [link](https://www.kaggle.com/mlg-ulb/creditcardfraud/download).
2. Place the downloaded `creditcard.csv` file in the project directory.
3. Run the `credit_card_fraud_detection.ipynb` Jupyter Notebook or Python script to execute the code.

### Project Structure
- `credit_card_fraud_detection.ipynb`: Jupyter Notebook containing the project code.
- `creditcard.csv`: Dataset file (not included in the repository, download from Kaggle).
- `README.md`: Project documentation file.

### Code Overview
The Jupyter Notebook (`credit_card_fraud_detection.ipynb`) contains the following sections:

1. **Data Loading and Exploration**: Loading the dataset and exploring its structure.
2. **Data Preprocessing**: Preparing the data for training by removing unnecessary columns and splitting it into features and labels.
3. **Model Building**: Implementing a Random Forest Classifier to detect fraudulent transactions.
4. **Model Evaluation**: Evaluating the model's performance using various metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

### Results
The Random Forest Classifier achieved the following performance metrics:

- Accuracy: 99.95%
- Precision: 95.00%
- Recall: 77.55%
- F1-Score: 85.39%
- Matthews Correlation Coefficient: 0.86

### Acknowledgments
- **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) by Machine Learning Group - ULB
- This project is for educational purposes only and serves as a demonstration of machine learning techniques for fraud detection.

### Contributing
Contributions are welcome! Please feel free to submit issues and pull requests.

### License
This project is licensed under the MIT License.
