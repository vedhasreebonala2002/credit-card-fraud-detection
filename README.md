# credit-card-fraud-detection


CreditCardFraudDetection
About :
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. So,this system is used to identify whether a new transaction is fraudulent or not. Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.

Error:- 'data = pd.read_csv('C:\Users\Ravi\Downloads\creditcardfraud\creditcard.csv')'
File "", line 2 data = pd.read_csv('C:\Users\Ravi\Downloads\creditcardfraud\creditcard.csv') ^ SyntaxError: (unicode error) 'unicodeescape' codec can't decode bytes in position 2-3: truncated \UXXXXXXXX escape

Solution:- data = pd.read_csv(r'C:\Users\Ravi\Downloads\creditcardfraud\creditcard.csv')
Warning:- C:\ProgramData\Anaconda3\lib\site-packages\sklearn\ensemble\iforest.py:247: FutureWarning: behaviour="old" is deprecated and will be removed in version 0.22. Please use behaviour="new", which makes the decision_function change to match other anomaly detection algorithm API. FutureWarning) C:\ProgramData\Anaconda3\lib\site-packages\sklearn\ensemble\iforest.py:415: DeprecationWarning: threshold_ attribute is deprecated in 0.20 and will be removed in 0.22. " be removed in 0.22.", DeprecationWarning)

For Dataset:-
https://www.kaggle.com/mlg-ulb/creditcardfraud
For Documentation, Idea & some source code taken from here :-
https://www.kaggle.com/sundarshahi/credit-card-fraud-detection-eduonix-solution


