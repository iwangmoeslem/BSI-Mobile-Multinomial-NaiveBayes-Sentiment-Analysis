# Summary
Bank Syariah Indonesia (BSI) Mobile is an Indonesian M-Banking App largely used by the Indonesian spesifically by the muslims.
Their syariah system is one of the major reason why Indonesian muslims choose this app. A few times ago, their services recieved several attack attempts that led
to system collapse and many shared their opinions about this event on X. This project classifies netizen's mixed tweets into negative or positive
sentiment towards this event using Multinomial Naive Bayes Classifier.
Weighted with TF-IDF and validated with K-fold Cross Validation. This project utilize sastrawi library process Bahasa language.

## Tools
- Jupyter Notebooks
- Pandas
- Sklearn
- Matplotlib
- Sastrawi

# Language
- Python

# Steps
- Import dataset
- Preprocessing (Cleansing, Case folding, Tokenizing, Stopword Removal, Stemming)
- Weighting (Term Frequency - Inverse Document Frequency)
- Data Training (Validated with 10-fold Cross Validation)
- Evaluation (Confussion matrix)
