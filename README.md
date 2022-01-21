# Exit-Poll-Prediction
The dataset contains US election data.The dataset consists of 9 column details filled by 1525 voters.
## Head of the dataset looks like:
![image](https://user-images.githubusercontent.com/95558910/150524429-65fc4ca0-7740-44df-a987-552551e5948c.png)
## Data Distionary:
![image](https://user-images.githubusercontent.com/95558910/150524700-1d720c8e-4ac8-474b-8713-a02c395e44a5.png)
## EDA
- All preprocesseing steps like checking missing values,duplicate values,random error checking,outliers checking were performed and necessary steps taken.
- An Exploratory Data Analysis were performed on the dataset by doing univariate,bivariate and multivariate analysis.
- From EDA some insights were noted down.
## Data Encoding
The categorical columns were converted into numerical value after performing get_dummies encoding technique.
## Data Splitting
The dataset were splitted into 70:30 ratio of 70% of data as train set and rest 30% as test set.
## Model Building
- Different classification models like Logistic Regression,Linear Disciminant Analysis(LDA),KNN,Naive Bayes,Decision Tree were implemented.
- These models were tuned for better results.
- Some ensemble techniques like Random Forest,Bagging,Adaptive Boosting,Gradient Boosting were applied to get best results.
## Model Evaluation
All the models were evaluated based on some performance metrics like confusion matrix,ROC-AUC scores,F1 Scores,Accuracy score.
## Model Comparison
![image](https://user-images.githubusercontent.com/95558910/150532138-0ac40799-8ca0-4595-83b0-3c1a56efb8d3.png)
![image](https://user-images.githubusercontent.com/95558910/150532718-7ecf0c75-dff9-445c-b90c-5f15c0991be6.png)
![image](https://user-images.githubusercontent.com/95558910/150532267-b1411cc6-4cdd-42a7-a75b-6c3cdb7d52d3.png)
## Final Model Selection
Based on F1 score ensemble Gradient Boost Classifier model has performed very well on both train as well as test data.
