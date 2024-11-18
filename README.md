## Project Topic
Machine Learning Model For Flood Prediction

## Dataset Description
This dataset is a csv file. It has  20544 entries, 0 to 20543 with  19 columns and has missing data more than half of the entire dataset

## Techniques
In this project, I leveraged on data cleaning techniques to check for missing data and used the standard scaler to scale my data. I splitted the data into two - one with missing data set and the other without. I used the former to build a logistics Regressor model that predicted the missing values in  the latter. After which i concatenayed the predicted columnto get a complete dataset. I developed multiple algorithms to achieve the final prediction 


![image](https://github.com/user-attachments/assets/7f6e228a-c408-4d14-ab7c-62be245758ee)



![image](https://github.com/user-attachments/assets/c9c853b9-9408-4629-8b7e-6b596f859e92)



![image](https://github.com/user-attachments/assets/856f721c-d121-4b24-b395-df4ddca2e4e4)


![image](https://github.com/user-attachments/assets/09bd880b-9ae8-4a2d-ad14-a353e7da9b02)


![image](https://github.com/user-attachments/assets/99fd67b5-fea2-4ddb-af2e-e499aae5f9cb)


![image](https://github.com/user-attachments/assets/9cc7c566-9896-4715-9f1b-7df796749314)



![image](https://github.com/user-attachments/assets/84180e1e-049f-4ad0-bffc-6c5992e7ecff)


![image](https://github.com/user-attachments/assets/0b7bdeda-597f-42d4-bc86-601aa8de9b72)


![image](https://github.com/user-attachments/assets/f66fcc4c-d9f8-4fbe-9781-5dec32a8a223)


![image](https://github.com/user-attachments/assets/2e00a529-c6ae-4429-bfcf-819e285068e6)


## Model Development
In thius project I developed 5 models which includes:
- Random Forest Classifier

  
 ![image](https://github.com/user-attachments/assets/8a8ffc24-23f0-44c9-9bc0-eb0ec98734a7)

- Logistic Regression

  
 ![image](https://github.com/user-attachments/assets/f45d6e44-095e-4db9-8c17-7ae66270c29e)


- Support Vector Machine

  
  ![image](https://github.com/user-attachments/assets/324d67ff-1e72-4a70-b174-3ddef484008a)

- Decision Tree Classifier

  
 ![image](https://github.com/user-attachments/assets/039e5276-b4ad-4b27-a22f-192057bf1605)


 I tested the accuracy of the models checking the confusion matrix, accuracy score,precision score, recall score ,auc_score and curve. Of all four models. Random forest model gave the best results .


 ![image](https://github.com/user-attachments/assets/07d749dc-0e9f-48b5-9fee-f6d1cb92a251)


 ![image](https://github.com/user-attachments/assets/67c8c650-c103-42c4-b43d-25a3ca68487d)



## flood-prediction-project
This project uses data from a flood prone zone to show a unconventional approach to handling missing data

## Conclusion
The dropna() approach of handling missing data is not suitable for all cases.Data imbalance is also iportant in getting unbias model. Random Forest model could be preferred for flood related dataset analysis

## Email
ogahngozibon@gmail.com
