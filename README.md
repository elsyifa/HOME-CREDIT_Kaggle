# HOME-CREDIT_Kaggle

## Overview

![alt text](https://github.com/elsyifa/HOME-CREDIT_Kaggle/blob/master/Images/HomeCredit.png)

Many people struggle to get loans due to insufficient or non- existent credit histories. Home credit strives to focus on responsible lending primarily to people with little or no credit history.Aiming of Kaggle competition is to predict their clients' repayment abilities. Doing so will ascertain capable clients are not rejected.  

I used Zeppelin and pyspark as environment in this prediction and this is a classification prediction.
![alt text](https://github.com/elsyifa/HOME-CREDIT_Kaggle/blob/master/Images/Zeppelin.png)

Zeppelin is Interactive web-based notebooks, we can do anything like data ingestion, data exploration, visualization and sharing data in Zeppelin notebooks.

![alt text](https://github.com/elsyifa/HOME-CREDIT_Kaggle/blob/master/Images/Spark.png)
While Spark is Analytic engine for big data processing and easy of use. Spark uses Java, Scala, Python, R, and SQL as programming language, and I used Python (Pyspark) as a programming language. One of the advantages of Spark is speed,which is can run workloads 100x faster.

## DATA

I will little bit explain about the data.
Actually, the data is huge and many tables are related but just focus on application_train|test.csv to buid up the understanding and to avoid diving all and getting lost. The diagram below shows relation between tables.
![alt text](https://github.com/elsyifa/HOME-CREDIT_Kaggle/blob/master/Images/relation_tables.png)


This data has 8 categorical variables and 9 numerical variables. 

![alt text](https://github.com/elsyifa/HOME-CREDIT_Kaggle/blob/master/Images/data1.png)

And this data categorized as imbalance classification. Imbalance classification is a condition where the difference number of observations between one class with other class is huge. There are some method to handle imbalance data: Down sampling and Over sampling. 

![alt text](https://github.com/elsyifa/HOME-CREDIT_Kaggle/blob/master/Images/imbalance.png)


I used Down sampling method that I run in pyspark environment and Over sampling method in python environment. From those method, Down sampling given better accuracy with Random Forest modelling. As information I used three different modelling, they are logistic Regression, Decision Tree and Random Forest. 

More details about how the codes are explained in syifa_Home-Credit-DownSampling (3).json and syifa_Home-Credit-OverSampling.ipynb. While the explanation regarding data explanatory, handle missing values, handle outlier, modelling, model evaluation and the result of prediction are written in my slide persentation, called Home_Credit_Default_Risk.pdf. All those files, I upload in this repository. 

Thanks. 
