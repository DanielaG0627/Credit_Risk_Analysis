# Credit Risk Analysis

## Analysis Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Analysis Results

Balanced accuracy score, precision and recall score for the 6 machine learning models can be found below.

- Naive Random Oversampling
![Screen Shot 2021-09-29 at 3 35 27 PM](https://user-images.githubusercontent.com/17945476/135336600-a68f1c6f-107e-452d-8ca2-5dba5dee9b0a.png)

- SMOTE Oversampling
![Screen Shot 2021-09-29 at 3 35 42 PM](https://user-images.githubusercontent.com/17945476/135336645-9688607f-8040-4c35-9ceb-b61f4dd3548b.png)

- Cluster Centroids
![Screen Shot 2021-09-29 at 3 36 00 PM](https://user-images.githubusercontent.com/17945476/135336691-6f74a1e8-2085-49c1-acbf-89a9a893bc4f.png)

- SMOTEENN
![Screen Shot 2021-09-29 at 3 36 12 PM](https://user-images.githubusercontent.com/17945476/135336726-d24fef32-f42c-4875-a643-999e9a8fa87d.png)

- Balanced Random Forest Classifier
![Screen Shot 2021-09-29 at 3 36 55 PM](https://user-images.githubusercontent.com/17945476/135336822-8b258791-c6c3-4103-9ff9-ac963e05a3f2.png)

- Easy Ensemble AdaBoost Classifier
![Screen Shot 2021-09-29 at 3 37 18 PM](https://user-images.githubusercontent.com/17945476/135336890-87d4f2bf-f40c-48ff-b41a-2e94e8dd7c86.png)


## Summary
Based on the results, it is recommended to use the AdaBoost model because it's accuracy score and recall is far better than the rest of the models.
