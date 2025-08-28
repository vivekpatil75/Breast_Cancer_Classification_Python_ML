# Breast_Cancer_Classification_Python_ML
## About
In this project we analyzed the Breast Cancer Dataset. The dataset contains various measurements of breast tumor which can be used as an indicators to check whether the tumor is cancerous or not. Then after thoroughly cleaning the data we standardize the data to feed it to the ML Random Forest algo. Then we try to predict the person has cancer or not.

## Dataset Information

- Dataset consists of 33 columns which are basically various measurements of the breasts. There are total 569 entries in the dataset which are used to learn the ML model.The shape of dataset is 569 x 33. This data is cleaned and there are no null values. The Column named 'Unnamed : 32' is droped becuase it has null values and does not specifically add any importance to the data.
  > <img width="608" height="806" alt="image" src="https://github.com/user-attachments/assets/0521fcae-b842-4a1a-ae82-24b63757ab59" />

- The Dataset have 357 **'Benign(has cancer)'** and 212 **'Malignant(no cancer)'** cases
  > <img width="352" height="126" alt="image" src="https://github.com/user-attachments/assets/0d305974-9256-49dc-9c21-13ba9ce392fd" />

## Steps used for Analysis and Classification

1. **Data Loading using Pandas**
   
##
2. **Data Cleaning**
   
   > - Checking for null values and deleting/imputing values if null values found.Fortunately we only had one column with all values as null so we drop coloumn "Unnamed : 32".
   > - We also drop "id" column cause it represents just personal identification and is of no use for Ml learning purpose.

##
3. **Basic EDA to understand data**

##
4. **Normalizng/Standardizing data ML**
   
   > - Changing **B** as **1** and **M** as **0** in diagnosis column which is our target column for classification.
   > - Using Standard Scaler to scale the data to minimize the error caused because for Different ranges or values in data. This Scaled data is then used to train the Machine Learning Model.
   > - We have used Random Forest Classifier in this project.

##
5. **Building Clssification Model**
   
   > - We separte the **Features[x]** and **Target[y]** columns and then split them in tarining and testing data.
   > - We train the Rf classifier model on **x_train** and **y_train** data and try to classify the data.
   > - Calculating metrics to score the model performnace. we have used confsuion matrix,accuracy score,cross validation score and classification report.

##
6. **Creating a model to predict/classify the data to check whether the person has cancer or not**


##
##
##
##
##
## *THANK YOU*
