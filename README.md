# Prediction of Suicidality during Covid-19 Pandemic in Bangladesh using different Machines Learning Techniques

## Purpose
The COVID-19 pandemic has resulted in an unprecedented global lockdown, which may have serious psychological implications. We aimed to predict early suicide thoughts in people living in lockdown or during a pandemic based on their behavioral patterns and available pandemic material.

## Dataset
However, the dataset used for this study from the Harvard Dataverse had a critical issue of class imbalance that could make machine learning models less accurate. Here's the link: [COVIDdata](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YKH9C1)

## Methods
To handle this, we trained machine learning classifiers such as KNN (K-Nearest Neighbour), Random Forest, XG Boost, Logistic Regression, Naive Bayes, and SVM on the imbalanced dataset using various data sampling methods like Under Sampling, Over Sampling, SMOTE, SMOTE+ENN.
## Results
After necessary pre-processing and comparative analysis among all the results, we found that the Random Forest Classifier had the highest accuracy of 97%. Additionally, the application of SMOTE+ENN to the dataset gave the best results.

Our study showcases how machine learning classifiers can be used to predict suicidality during lockdown or pandemic situations.
### Results from Hybridization(SMOTE+ENN)  with 5 fold cross validation:
| Classifier | Precision     |Accuracy                       |
| :-------- | :------- | :-------------------------------- |
|  Decision Tree   | 0.93 | 0.94 |
|  Logistic Regression   | 0.73 | 0.75 |
|  Random Forest   | 0.98 | 097 |
|  KNN   | 0.99 | 0.95 |
|  XG Boost   | 0.94 | 0.95 |
|  Naive Bayes   | 0.73 | 075 |

## Conclusion
These classifiers enable accurate diagnosis and identification of people with severe mental illness who are contemplating or have actually  planned  suicide.  As a result, we can offer them appropriate couseling at  the  appropriate time,  saving both their family and themselves from irreparable harm.
