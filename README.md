# Kaggle-HousingPrice-Classification

In this project, the data set of Housing Price competition of Kaggle, which is a public data set, has been chosen. https://www.kaggle.com/c/home-data-for-ml-course/data
Kaggle data set consists of two data files: train and test data files. In this project, I worked on train data file, which I included in the file. The name of file is 'KaggleHousingDataFile.csv'. All evaluations were performed on this data file.
Generally, housing price is a regression problem. However, in this project, I evaluated housing price as a classification problem. Therefore, I have binned the housing price in five categories, i.e. Low, Med Low, Med, Med High, and High.
In this project, I have done the follwing steps:
1) Read and evaluate data file. 2) Check missing values. 3) Select features from input data file. 4) Feature normalization. 5) Bin Sale Price for Classification. 6) Develope ML Model. 7) Evaluate the performacne of ML models based on defined metrics.
After defining SalePrice into five categories, I defined ML models in two parts.
In the first part, I used Random Forest Classifier to predic the categories of SalePrice. In this part, I used grid search method to find the optimum parameters for Random Forest Classifier.
In the second part, I used six classification ML models includig: 1) Random Forest Classifier 2) Logistic Regression 3) Gaussian Naive Baysian 4) K Neighbor Classifier 5) SVC 6) Decision Tree Classifier
to predic SalePrice. In this part, I evaluated: model train and test accuracies, model precision, and model recall.
