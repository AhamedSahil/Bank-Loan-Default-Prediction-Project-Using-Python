# <p align="center"> Bank-Loan-Defaulter-Prediction-Project-Using-Python </p>
 
# <p align="center">![image](https://github.com/AhamedSahil/Bank-Loan-Default-Prediction-Project-Using-Python/assets/164605797/5ebc19c1-d7fd-4287-aae0-267d1d10b400)

</p>

### + Introduction

Loan default prediction is a crucial task for banks and financial institutions to mitigate risks associated with lending.This project utilizes machine learning algorithms to analyze 
customer data and predict whether a customer is likely to default on their loan.

###Dependencies

To run this project, you need the following dependencies:

- python3
- pandas
- numpy
- sk learn
- seaborn
- matplotlib
- jupyter lab
- Excel

[Dataset Used](https://github.com/AhamedSahil/Bank-Loan-Defaulter-Prediction-Project-Using-Python/blob/36cace2def289bf8d78cad40bafe89359988c61a/bankloans%20data.xls)

[Python Script](Bank_loans_script.ipynb)

### Information about our dataset

```py
data_ex.info()
```

###### result

![image](https://github.com/AhamedSahil/Bank-Loan-Defaulter-Prediction-Project-Using-Python/assets/164605797/f67f1aba-b496-4191-a304-e7e15766a78a)

 - ##### We are not having any null values.

```py
#2.missing values treatment
data_ex.isnull().sum()
```

###### Result

![image](https://github.com/AhamedSahil/Bank-Loan-Defaulter-Prediction-Project-Using-Python/assets/164605797/b94bf840-eec4-49c8-aa27-7a1172899649)

### Outlier treatment 

##### We have used box plot for Outlier detection.

```py
#3.outliar treatment 

for column in data_ex:
    plt.figure(figsize=(10,1))
    sns.boxplot(x=data_ex[column])
    plt.title(f"Boxplot of {column}")
    plt.show() 
```
###### Result 

![image](https://github.com/AhamedSahil/Bank-Loan-Defaulter-Prediction-Project-Using-Python/assets/164605797/367f6427-c3aa-467f-9b23-e9b45fcb2669)

![image](https://github.com/AhamedSahil/Bank-Loan-Defaulter-Prediction-Project-Using-Python/assets/164605797/adfe04cb-7e05-4fee-9ac4-40c5effc185e)

![image](https://github.com/AhamedSahil/Bank-Loan-Defaulter-Prediction-Project-Using-Python/assets/164605797/3aa4322b-a8e8-4a6b-b0a8-c4d27bb33784)








