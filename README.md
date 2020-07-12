# Tumour-Classification-to-predict-breast-cancer

Problem is to build classification models to predict if the tumor of each of these patients present in the dataset is benign or malignant and also understand the correlations between the dependent variable and all the feature variables which are the clump thickness, the uniformity of cell size, the uniformity of cell shape, the marginal addition, Single epithelial cell size, bare nuclei, bland chromatin, normal nucleoli and mitoses.


Select quickly and efficiently the best classification model on the basic of "accuracy" metric for this particular dataset.

Different Classification Models used here are as follow :- • k nearest neighbors • kernel svm • decision tree classification • Random Forest Regression • logistic regression • naive bayes • support vector machine.

Data Description:- This is a classic dataset which belongs to the UCI machinery repository and is about breast cancer. In this dataset, each row corresponds to a different patient. It contains almost 683 patients details which is described using 9 features and has no missing data nad no categorical data.

Steps:- 1. Importing the libraries 2. Importing the dataset 3. Splitting the dataset into the Training set and Test set 5. Feature Scaling (if required) 4. Training the Different Classification models on the Training set 5. Predicting the Test set results 6. Making the Confusion Matrix.

Conclusion:- The Accuracy obtained from these models after applying on test set data are: • logistic regression - 94.7 % • k nearest neighbors - 94.7 % • naive bayes - 94.2 % • decision tree classification - 96 %  • Random Forest Regression - 93.5 % • support vector machine - 94.2 % • kernel svm - 95.3 %.

Decision Tree Classification out performs all other models with maximum Accuracy of 96 % for this dataset.
