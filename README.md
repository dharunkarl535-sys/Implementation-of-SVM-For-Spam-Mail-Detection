# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
/*
Program to implement the SVM For Spam Mail Detection..
import chardet
file='spam.csv'
with open(file, 'rb') as rawdata:
    result = chardet.detect (rawdata.read(100000))
result
import pandas as pd
data=pd.read_csv('spam.csv', encoding='Windows-1252')
data.info()
data.isnull().sum()
x=data["v1"].values
y=data["v2"].values
from sklearn.model_selection import train_test_split
x_train, x_test, y_train,y_test=train_test_split(x,y,test_size=0.2, random_state=0)
from sklearn.feature_extraction.text import CountVectorizer
cv = CountVectorizer()
x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)
from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train, y_train)
y_pred=svc.predict(x_test)
y_pred
from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy

*/
```

## Output:

<img width="708" height="150" alt="530320122-804afc3b-da33-406d-b796-e54eecb70787" src="https://github.com/user-attachments/assets/863319ce-fec8-4caf-8ee4-8441949ddb02" />
<img width="726" height="237" alt="530320144-f6bbcec5-7f79-4636-9f85-878f9b1b96f7" src="https://github.com/user-attachments/assets/5cc85c44-d869-49dc-b525-31ba702d2385" />


## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
