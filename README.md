## datacastle Financial Billing Prediction


##File description

```
-RawData                 #Raw data for the Project
-java_feature            #java feature extraction
-python_feature          #python feature extraction
-JavaCode                #java feature extraction code
-PythonCode              #Python project code
-Rcode                   #Rcode for xgboost model
-result                  #Results of storage
```
##Java and Python code description

```
-JavaCode
          -infoClass.java             #Data Structure Definition
          -bankRecord2.java           #Characteristic Bank record 
          -billRecord.java            #Credict card Bill record 
          -browseRecord.java          #Characteristic bank
          -longestOverdue.java        #Overdue improvement 
          -Data_clean.java            #clean-up data files
          -FeatureGet.java            #combined features 

-PythonCode
          -bank_train.py,bank_test.py         #Bank feature files
          -browse_train.py,browse_test.py     #Browsing record characteristics
          -bill_train.py,bill_test.py         #Credit card 
          -feature_combine.py                 #combined feature records
          -lgb_5fold.py                       #lightgbm model
          -bill_feature_select          #Credit card selected features selection
```
