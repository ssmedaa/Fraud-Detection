# Fraud-Detection
## Description 

In order to detect fraudulent transactions, this program uses supervised learning; a machine learning technique that is has training on a large datasets. Machine learning provides financial institutions advantages with detecting and flagging any suspicious activities that can potentially be a crime.

## Stages ##
**1. Data Collection**
- [Kaggle: Bank Payment Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1/)
- Number of samples: 1,048,575

**2. Data Preparation & Manipulation**
- The encoding relevant features: type and isFraud:
    - **Type**, refers to the transaction behaviour: *cash out, debit, payments, or transfers*
    - **isFraud**, represents binary values for *fraudulent* or *not fradulent* transactions
      
**3. Training Model**
- **Decision trees** utilise features in the dataset to predict the outcome of an event: is fraud or not fraud
- Dataset Split:
    - Training: 70%
    - Validation: 15%
    - Testing: 15%
      
**4. Evaluation**

| | precision | recall | f1-score |
| --- | --- | --- | --- |
| 0| 1.00 | 1.00 | 1.00 |
| 1 | 0.89 | 0.89 | 0.89 |
| | | | |
|accuracy| |  |1.00

```
False Positive Rate (FPR): 0.0001

False Negative Rate (FNR): 0.1100
```
```math
Confusion Matrix:  \begin{bmatrix}1906116&251\\266&2153\\\end{bmatrix}
```



