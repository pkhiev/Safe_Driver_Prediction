# Safe_Driver_Prediction
Data science project utilizing machine learning and customer data to predict whether insurance policy holders will initiate an auto insurance claim within the next year. This project is based on the Kaggle competition: Porto Seguro’s Safe Driver Predition competition [1]. In this repository you will find a Jupyter notebook containing code and explainations for the entirety of this project including exploratory data analysis, feature engineering, machine learning model training and validation, prediction results etc.

Problem Description: Car insurance rates are based on predictions of the probability that a policy holder will file a claim.
As such, it is important that insurers are able to accurately predict claim probability. Inaccuracies
in claim prediction results in higher rates which systematically penalizes “good” drivers for the
mistakes of “bad” drivers. The objective of this project is to build a model that predicts the probability
that a driver will initiate an auto insurance claim within the next year.
The data is obtained from the Kaggle Porto Seguro’s Safe Driver Predition competition [1]. The
test and train datasets contains features that are labeled (e.g., ind, reg, car, calc) to group them by
type. They are also labeled by postfix bin to indicate binary features and cat to indicate categorical
features. Features that are not labeled by this postfix are either continuous or ordinal. Missing
features were given a value of -1. The target column denotes whether a claim was filed for a
particular policy holder. A detailed summary of the dataset can be found at [1].

[1]: https://www.kaggle.com/competitions/porto-seguro-safe-driver-prediction/data
