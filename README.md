This notebook uses the Lending club data- obtained from Kaggle (https://www.kaggle.com/wendykan/lending-club-loan-data). The database contain records of all loans between 2008- 2015.
A data dictionary containing all feature names and what they represent is given in the data folder: LCDataDictionary.xlsx.

The objective of this notebook is to build and evaluate two machine learning models to predict whether a loan will be fully paid or charged off. 

SQL is used to extract info from the database for preliminary analyses of some study features is done.
Analyses of some features is also done, stratified by loan status.

Data is cleaned and prepared for used in the two machine learning models types- K-Nearest Neighbors and Logistic Regression.
Accuracy scores are obtained. Evaluation measures from confusion matrix are also given for the logistic regression.
2 new observations are also created and used to make predictions using the models.

Technologies used:
- SQL
- Python:
  * pandas
  * numpy
  * matplotlib
  * scikit-learn
  * seaborn
  * folium



