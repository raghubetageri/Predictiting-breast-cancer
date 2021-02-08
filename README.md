# Predict-breast-cancer
Predicts whether the type of breast cancer is Malignant or Benign.
AS i am in beginner level i used to learn things and update this project.

Breast cancer is the most common type of cancer in women. When cancers are found early, they can often be cured. There are some devices that detect the breast cancer but many times they lead to false positives, which results is patients undergoing painful, expensive surgeries that were not even necessary. These type of cancers are called benign which do not require surgeries and we can reduce these unnecessary surgeries by using Machine Learning. We take a dataset of the previous breast cancer patients and train the model to predict whether the cancer is benign or malignant. These predictions will help doctors to do surgeries only when the cancer is malignant, thus reducing the unnecessary surgeries for woman.

For building the project we have used Wisconsin Breast cancer data which has 569 rows of which 357 are benign and 212 are malignant.we have trained on LOGISTIC REGRESSION,DECISION TREE CLASSIFIER,RANDOM FOREST CLASSIFIER,UPPORT VECTOR CLASSIFIER which gives the best accuracy 98.2% . 

#Dataset link

https://raw.githubusercontent.com/ingledarshan/AIML-B2/main/data.csv

#Libraries
python:Language
Numpy : library for data numerical caluculation
Pandas :library for data manipulation and analysis
sklearn:library which features various classification,regression and clustering algorithms


#To use this Project

$ git clone https://github.com/raghubetageri/Predicting-breast-cancer.git

$ pip install -r requirements.txt

$ python mlbrst.py
 
