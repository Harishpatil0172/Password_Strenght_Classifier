# Password_Strenght_Classifier

1. Importing necessary liabraries:
   import pandas as pd
   import numpy as np
   import seaborn as sns

2. Read the dataset:
   dataset includes 2 columns i.e. password and strength
   strength has 3 unique values 0,1,2
   strenght value is 2 means password is very strong
   if it is 1 then strong and for 0 it is weak password.

   2.1 Check for null values:
   at 367579 password column has one NaN value so we drop it.

   2.2 Check countplot of strenght column:
   we get 500000 strong passwords,100000 weak and very strong passwords each.

3. Apply TF-IDF Vectorizer on data:
   It converts String data into numerical data
   after applying TF-IDF we get 669639 rows and 126 columns

4. Spliting data into Train and Test:
   train data- to learn the relationship within data
   test data-To do prediction,(This test data is unseen by model)

5. Apply Logistic Regression:
   This is classification problem so we use Logistic regression which classifies the dataset into 3 categories
   weak password, strong password, very strong password.

6. Accuracy of the model:
   accuracy is measured by confusion matrix with accuracy score of 82.06%
   







