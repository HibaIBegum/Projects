# Projects
CREDIT CARD FRAUD remains one of the most significant problems. The initial step is to distinguish between different types of credit card fraud, as fraud can happen offline and online in many ways. These frauds can be detected using different measures by the banks, depending on different types of cards provided by them. The main objective of this project will be to compare all techniques and provide the most accurate algorithm to reduce fraud detection. As there are limitations with the existing algorithm, we will be providing a comparative result of Decision Tree, Support Vector Machines (SVMs), Naive Bayes and Random Forest Algorithms.
As mentioned, we have implemented the Random Forest tree and Decision Tree algorithm with the dataset from Kaggle. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not transformed with PCA are 'Time' and 'Amount'. The measures used to evaluate the performance are accuracy, precision and recall.
Random Forest Tree Algorithm has 99% accuracy Decision Tree has 94% accuracy. The steps followed to obtain this are as follows:
1. Import all the libraries required for this project. We import pandas,numpy,matplotlib, seaborn and sklearn.
2. Load the dataset
3. Perform data analysis like cleaning dataset, check for null values if any remove it and
data visualization. We can see the dataset does not include any null value. The visual representation is displayed using a heatmap with 50 x 50 dimensions where value 1 stands for fraud occurred.
4. The data class value of the dataset is 284315, 492
5. Handling imbalanced data by using “SMOTE- Synthetic Minority Over-Sampling Technique”
6. Feature selection and Data split: In this process, we will define the independent (X) and the dependent variables (Y). Using the variables, we will split the data into a training set and testing set that is further used for modelling and evaluating.
7. We have used Random Forest Tree and Decision Tree algorithms for testing the dataset. Here we have split the dataset into 60%-40% training and testing.
8. The Random forest tree algorithm selects features to construct multiple models, whereas the decision tree uses an entire dataset to construct a single model.
9. Here we have used the y_train sub dataset, which has 18 columns. The result is 0.99.
10. The decision tree uses max_depth to be 2, which means we are making the tree split only
twice and the criterion to be entropy. The result is 0.94.
Next we will be implementing Support Vector Machines (SVMs) and Naive Bayes algorithms to find accuracy,precision,F1-score and recall.
