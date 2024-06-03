# Credit Card Fraud Detection

This project involves detecting fraudulent credit card transactions using a Logistic Regression model. The dataset used in this project is highly imbalanced, with a much larger number of legitimate transactions compared to fraudulent ones. To address this, undersampling is used to create a balanced dataset.

## Table of Contents
- Installation
- Usage
- Project Structure
- Methodology
- Results
- Contributing
- License
  
## Installation
To run this project, you need to have Python installed along with the following packages:

- numpy
- pandas
- scikit-learn

You can install the necessary packages using pip:

```bash

pip install numpy pandas scikit-learn
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```
2. Navigate to the project directory:

```bash

cd credit-card-fraud-detection
```
3. Open the Jupyter notebook:

```bash

jupyter notebook credit_card_fraud_detection.ipynb
```
4. Run the cells in the notebook to load the data, train the model, and evaluate its performance.

## Project Structure
```bash
credit-card-fraud-detection/
├── credit_card_fraud_detection.ipynb
└── README.md
```
## Methodology

### Data Loading and Exploration:

- Load the dataset and display basic information.
- Check for missing values and analyze the distribution of transactions.
### Data Preparation:

- Separate the data into legitimate and fraudulent transactions.
- Create a balanced dataset by undersampling the legitimate transactions.
### Feature and Target Splitting:

- Split the dataset into features (X) and target (Y).
### Model Training:

- Split the data into training and testing sets using train_test_split.
- Train a Logistic Regression model using the training data.
### Model Evaluation:

- Evaluate the model's accuracy on both training and testing data.
## Results
- The model's performance is evaluated based on its accuracy on the training and testing datasets.
- The detailed results and accuracy scores are available within the notebook.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
