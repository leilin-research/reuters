# Multi-label Multi-class Classification based on Reuters-21578

- We take the ApteMod subset of the Reuters-21578 corpus

- For feature engineering, TF-IDF and Word2Vec are implemented

- For classificiation model, Linear SVC, Feedforward Neural Network and Bi-LSTM are applied

- The classification accuracy, Macro F1 and Weighted F1 are shown below:

**Feature Extraction**|**Model**|**Accuracy**|**Macro F1**|**Weighted F1**
:-----:|:-----:|:-----:|:-----:|:-----:
TF-IDF|SVC|0.81|0.47|0.84
 |Feedforward|0.78|0.46|0.83
Word2Vec (Pre-trained)|SVC|0.73|0.29|0.75
 |Feedforward|0.76|0.43|0.8
 |Bi-LSTM|0.8|0.39|0.82