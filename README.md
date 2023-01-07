# Online-Payment-Detection-Fraud
10Alytics Capstone Project, A project aimed at building a model to detect online payment fraud system for Blossom bank PLC, a financial institution
**Steps taking and challenges faced;**
Necessary libraries were imported for data uploading and visualization, exploratory data analysis (EDA) was conducted as well, to gain data insight. Charts such as bar plot, histogram and subplot were also plotted to show the relationship between columns and also the most frequently used method of online transaction been used. A special feature (from imblearn.over sampling import SMOTE),this was imported and used to treat the imbalance in the target column of the dataset.
Two machine learning model were trained and tested on the training and test data set using a 30-70% splitting ratio, the models are K-nearest Neighbors classifier and DecisionTreeClassifier. K-nearest Neighbor classifier produces a fair result with the highest recall of 80% as against DecisionTreeClassifier which produces result with a recall of 75%.
A confusion matrix was also imported to determine the quantity of True-positive, False-negative, False-positive and True-positive values as well, K-nearest Neighbors classifier also produces the highest number of false negative as compared to DecisionTreeClassifier.
Since the aim of the project is to minimize the rate of fraudulent activities by scammers, K-nearest Neighbors seems to have produce a good number of false-negative in terms of prediction, hence it is been adopted.
