# sentiment Analysis

## 📃 DataSet 

size : 50000 * 2 

nagative data Size : 25000 

Postive data Size : 25000 

count Null Values : 0

## 🛠 Lib

- pandas
 
- numpy

- scikit-learn

- matplotlib

- seaborn

- keras

## ✒ preprocessing

- Replace Postive and Nagative to 0 and 1

- tokeniztion

## model 

### 🧱 Architecture 

1 • embedding Layer output is 128 dim  

2 • Lstm Layer from 64 cell 

3 • Lstm Layer from 32 cell

4 • Dence from 1 cell and sigmoid activtion function

### traing setting

- regurilazition dropout 50%

- optimizer = adam

- epochs = 5

- batch size = 5 

## 🔻 model evaluate  ≌ 90 %  



