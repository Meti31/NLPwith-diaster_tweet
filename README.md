<img width="221" alt="image" src="https://user-images.githubusercontent.com/89664911/167133072-f666276a-3bf0-48a0-89ce-572d15417ef4.png">

# Natural Language Processing with Disaster Tweets #
  ##### This repository holds an attempt to apply Linear model to predict whether a tweets is  disaster or not using data from "Natural Language Processing with Disaster Tweets" Kaggle challenge (https://www.kaggle.com/competitions/nlp-getting-started/data).
 ### Overview
    
  ##### The task, as defined by the Kaggle challenge is to use Natural Language processing to predict whether a given tweet is about a real disaster or not.  #####
   ##### The approach in this repository  is using text tweets as an input and train Linear model to predict whether it is a real disaster or not.The model had  average accuracy score of 0.6024.  #####
### Summary of WorkDone
   ##### Data
   ##### Type: CSV file (train csv file and test csv file)
   ##### Input: CSV file of features, output: target ==> 1 or 0.
   ##### Size: How much data? 10,876
### Exploratory Data Analysis
#### The train data contains ID , Keyword ,Location ,Text ,Target
<img width="463" alt="image" src="https://user-images.githubusercontent.com/89664911/167162764-9c13aad4-3570-4f80-8ccf-c809cb7e3e9b.png">

#### The test data contains ID , Keyword ,Location ,Text
<img width="327" alt="image" src="https://user-images.githubusercontent.com/89664911/167162863-540a2ab9-c2ca-4886-9049-9b4fb897c12d.png">
 
 ### Data Visualization

#### The first barchart shows how many of the tweets are diaster not and the second one shows the length of the tweets 
<img width="362" alt="image" src="https://user-images.githubusercontent.com/89664911/167163357-9fa8ba47-7173-4651-91e3-ddfb6a9543c4.png">
<img width="467" alt="image" src="https://user-images.githubusercontent.com/89664911/167164760-5b7b45e2-69bf-46fc-b59e-56c34a0a60d3.png">

#### Data cleaning 
###### Remove URL from the 
###### Remove special charctersics 
###### Remove HTML Tags from the texts
###### Remove Emoji







