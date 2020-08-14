# Titanic-dataset---classification
The classic Kaggle Titanic ML competition.   
The goal: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.  
In this competition, two similar datasets are used that include passenger information like name, age, gender, socio-economic class, etc.   
One dataset is titled `train.csv` and the other is titled `test.csv`.   
'Train.csv' contains the details of a subset of the passengers on board (891) and reveals whether they survived or not.    
`test.csv` dataset contains similar information but does not disclose if the passengers survived or not.   
The goal is to predict whether the other 418 passengers on board (found in test.csv) survived.   
  
You submit a csv file with exactly 418 entries plus a header row.   
The file has exactly 2 columns:   
PassengerId (sorted in any order)   
Survived (contains your binary predictions: 1 for survived, 0 for deceased)   
   
The score is the percentage of passengers correctly predicted, ie., accuracy.    
