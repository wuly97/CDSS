# A clinical decision support system (CDSS) based on machine learning to predict the heart disease risk of patients 

1.Datasets
The UCI Heart Disease datasets listed have been downloaded from UCI Machine Learning data repository. There are one class label and 13 features in this dataset. The class label is ‘num’ (the presence of heart disease in the patient); the 13 features are ‘age’ (age in years), ‘sex’ (sex), ‘cp’ (chest pain type), ‘trestbps’ (resting blood pressure on admission to the hospital), ‘chol’ (serum cholesterol), ‘fbs’ (fasting blood sugar), ‘restecg’ (resting electrocardiographic results), ‘thalach’ (maximum heart rate achieved), ‘exang’ (exercise induced angina), ‘oldpeak’ (ST depression induced by exercise relative to rest), ‘slope’ (the slope of the peak exercise ST segment), ‘ca’ (number of major vessels colored by fluoroscopy) and ‘thal’ (displays the thalassemia).

2.Codes
To decide about the most promising classifier that better suits our dataset. In this regard, a series of supervised learning techniques have been adopted to train predictive models inclusing Random Forest, Linear Discriminant Analysis (LDA), Support Vector Machine (SVM) all kernels (linear, polynomial and RBF), Multilayer Perception (MLP), K-nearest neighbors and Decision Tree. Since prediction of categories rather than values were the aim, classification was the supervised learning method being utilized in this project. The classifiers had been trained and tested using the best dataset; based on the cross-validation and the evaluation metrics, the more accurate and stable model with higher value for the area under curve (AUC) and f1-score would be recognized as the most valid and reliable model to be hired for our main analysis.

3.System
We primarily designed our user interface based on the conceptual prototype we did and which is available in this link: https://xd.adobe.com/view/c32d9106-6dc0-43ab-47c2-35a64df0ab83-b51c/ 
