# Heart-disease-prediction
This project aims to create a classification model to predict the possibility of heart disease.

Dataset - https://www.kaggle.com/datasets/rashadrmammadov/heart-disease-prediction/data 

Every year tonnes of medical data is generated which contains information about the patients. Heart diseases have become very common all over the world. If our data is carefully analysed and models are created to predict the outcomes, it can help diagnose the diseases in their very early stages. This can help with better treatment plans and may even go on to save lives.

This notebook cleans and analyses the dataset to obtain some insights. With the help of these insights, models are created with different accuracies to make predictions.

### After importing the libraries, the dataset is checked for null values, and appropriate values are filled in the parts with null values. 

### Univariant analysis: 
All the variables are individually studied with the help of visualization techniques to gain some inferences and check for outliers. The numerical values are studied using histograms and boxplots whereas the categorical values are studied using countplots.

### A heatmap describing correlation is studied to establish dependencies among variables.

The data is encoded to all the numerical values which helps the machine to understand them. It is further normalized and scaled to obtain a common range of values.

The cleaned data is split into training and testing sets.

## The data is then fitted into the Logistic Regression model which is the simplest classification model. It yields an accuracy of 83% which is not bad but other complex models can be tried.

## The second model used is the Random Classifier model which yielded an accuracy of 100%.

This indicates that the Random Classifier is the best model for this case.

# A model that can predict if the person will have heart disease or not when some inputs are provided to the machine is successfully created.
