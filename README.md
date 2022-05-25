# Autism-Project

IN Autism Project, We have to identify whether the individual is suffering from autism disorder or not by predicting from Machine learning model.
So as it was classification problem, I've tried predicting this using classification algorithm. 
Here, After performing statistical analysis on the dataset. I've found out some of the features which were not relevant to the dataset. So I've Eliminated those Features and I've found out that some of the missing values present in the form of '?'.
So, I've filled the missing values with the mode as the feature was having categorical values and performed Standardization using the StandardScaler.
Then, I have converted categorical variables to numerical, before working on sklearn.
After Splitting into train/test, Ive created a model using logistic regression, SVM, KNN, Decision Tree, Random Forest, ADA Boost,Gradient Boosting ,XG Boost out of which logistic regression was giving better accuracy but not so promising.
So after doing some research on data, I found out that the data was imbalanced, so performed some resampling techniques like SMOTE, random sampling where random sampling was performing better. So to improve the Accuracy furthermore, I've tuned the model by Adjusting the threshold value in Logistic Regression and also tried K-fold Cross Validation for parameter tuning.
So the final model which I have used here is Logistic Regression.
