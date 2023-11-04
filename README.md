# Parkinson's Disease Detection
## Description:
Parkinson’s disease (PD) is one of the primary vital degenerative diseases that affect the Central Nervous System among elderly patients. Several models have been presented earlier to detect the PD using various types of measurement data like speech, gait patterns, etc. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician, that’s why we are using here voice dataset. In this project, we have implemented Logistic Regression (LR), Decision Tree, Random Forest (RF), K-Nearest Neighbors and Support Vector Machine (SVM). 

Our objective of this project is to compare the accuracy of different models and the one which has the highest accuracy will be used for detection of Parkinson’s disease.

Dataset link: https://drive.google.com/drive/u/0/my-drive

## Working:
Step 1: Firstly, we have applied data preprocessing.

Step 2: Plotted a pie chart which demonstrates the distribution of status attribute.

Step 3: Defined the correlation features.

Step 4: Calculated the P_value of every column.

Step 5: Applied standardization over the given data.

Step 6: Splitted the data into training set and test set.

Step 7: Using RandomOverSampler class to handle the imbalanced data.

Step 8: Implemented different ML models like Logistic Regression, Random Forest, Decision Tree, SVM and KNN. We have also made the confusion matrix and AUC curves of the given model.

Step 9: Calculated the accuracy of different models.

Step 10: Made a function for comparison of these modelson the basis of there AUC score, train and test accuracy.

Step 11: Applied Cross validation to remove over fitting.

To see the working of the model, you can visit this link: https://colab.research.google.com/drive/10AruDzPfwVANmQSyrg64N4xv0v9fWODh?usp=sharing#scrollTo=lNrhM_rYZbFZ
