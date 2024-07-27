# Credit Card Fraud Detection

This project aims to build a robust model for detecting fraudulent credit card transactions. The project is divided into two main parts: Exploratory Data Analysis (EDA) and Modeling. The dataset used for this project is highly imbalanced, with a very low percentage of fraudulent transactions.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Credit card fraud detection is a significant challenge in the financial sector, as fraudulent activities cause substantial financial losses each year. This project focuses on identifying fraudulent transactions using machine learning techniques.

## Dataset

The dataset used for this project contains transactions made by credit cards in September 2013 by European cardholders. It is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

## Exploratory Data Analysis

The EDA section includes:

1. **Data Cleaning and Preprocessing:** Handling missing values, data normalization, and scaling.
2. **Data Visualization:** Visualizing transaction patterns, amount distributions, and correlations.
3. **Class Imbalance Handling:** Techniques used to address the imbalance in the dataset, such as under-sampling and over-sampling.

## Modeling

In the modeling section, various machine learning algorithms are implemented and evaluated:

1. **Logistic Regression**
2. **Decision Trees**
3. **Random Forest**
4. **Gradient Boosting**
5. **Support Vector Machines (SVM)**
6. **Neural Networks**

Performance metrics such as accuracy, precision, recall, F1-score, and AUC-ROC are used to evaluate the models.

## Results

The results of the models are compared, highlighting the most effective algorithm for detecting fraudulent transactions.

## Conclusion

The project demonstrates the effectiveness of machine learning algorithms in detecting credit card fraud. It also discusses the importance of handling class imbalance and selecting appropriate performance metrics.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yatharthgautam123/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install the required dependencies
4. Run the Jupyter notebooks

## Dependencies

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
