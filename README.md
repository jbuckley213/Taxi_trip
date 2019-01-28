# Taxi_trip

Overview
========
This project is to build a model to predict the length of a taxi journey in New York city. This project was a competition on Kaggle in which the validation metric must be in Root Mean Sqaure Logarithmic Error (rmsle).

Dependencies
========
* Numpy(http://www.numpy.org/)
* Pandas ```pip3 imstall pandas```
* Matplotlib 
* Sklearn ```pip3 install sklearn```
* Xgboost ```pip3 install xgboost```

Performance
=========
Xgboost was used for modelling for its accuracy and speed. The model had a rmsle value of 0.395767 which is a good performance considering the range of the output is (0.69 to 11.36). 
