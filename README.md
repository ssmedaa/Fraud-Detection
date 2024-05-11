# Fraud-Detection
This is program uses supervised learning, it is a type of machine learning that supplies an algoithm with a set of datasets for training purposes to detect fraudlent transactions. Machine learning are used to recognize patterens that finacial instutuons utilizes with detecting and flagging suspicious activities. 

The dataset used for this was from [Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1/).
  - Total number of samples 1,048,575
    - 1,142 are positive detection of money laundering transaction
The encoding relevant features: type and isFraud:
    - Type, refers to the transaction behaviour: cash out, debit, payments, or transfers
    - isFraud, represents in binary values for not or is fraudulent transactions

Dataset experiment setting splits the data into the following 3 categories: 
  1. Training set (70%)
  2. Test set (15%)
  3. Validating set(15%)



Imbalancing of datasets is why financial crime detection or even in general fraud detection
problems accuracy is not reliable. Thus, in the case of imbalanced dataset precision, recall, f1 score are the metrics that handle these datasets.

