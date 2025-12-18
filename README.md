# Liver patients classification

This project applies machine learning to a medical classification task. The goal is to predict whether a person suffers from a liver disease or not, based on several clinical measurements. We work with a dataset that contains information about several liver-related indicators for a number of patients. We try different classification models, including Discriminant Analysis, Naive Bayes, Logistic Regression, K-Nearest Neighbors, Random Forest, and Support Vector Machines (SVM). 

After testing and comparing them using F1-score as the main evaluation metric, we find many models with a very good performance, but we consider the Support Vector Machine to be the best. To obtain the best possible configuration, we tuned carefully its hyperparameters using a grid-search with cross validation, and finally tested it on unseen data. The results show that SVM has a very good performance, especially when the data is scaled properly and we balance the classes correctly. This confirms that SVM is a good option for this kind of medical prediction problem. Overall, the project shows how machine learning can be very helpful in real world health problems.

All explanations and details can be found in the attached Report file. 
