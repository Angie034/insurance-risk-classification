# Machine Learning for Insurance Risk Classification

## Project overview
This project applies machine learning techniques to classify insurance policyholders into
low,medium and high insurance premium risk categories based on demographic and lifestyle characteristics.
The objective is to demonstrate how predictive analytics can support insurance underwriting and premium 
pricing decisions.

##**Business problem**
Insurance companies need reliable methods to assess customer risk and determine appropriate premium categories.
The project develops a classification model that predicts insurance premium risk using customer characteristics.

##**Dataset**
The dataset contains information such as:
 -Age
 -Gender
 -Body mass index
 -smoking status
 -region
 -Number of children
 -Insurance Premium Category(Target variable)

 ##**Technologies used**
  -python
  -pandas
  -numpy
  -Scikit-learn
  -matplot-lib
  -Jupyter Notebook
 
 ## Machine Learning Model
 -Decision Tree Classifier
 -Logistic regression
 -Random Forest Classifier
 -XGBoost classifier

 **Model Performance**
 Four classification models were evaluated using accuracy,precision,recall
 f1-score,confusion matrix,ROC-AUC curve and Feature Importance.
 Best performing model :
 -Decision tree 
 -Accuracy 65%

 ## results table
Model	Accuracy	Precision	Recall	F1-Score
0	Decision Tree	0.65	0.650	0.65	0.650
1	Logistic Regression	0.60	0.637	0.60	0.613
2	Random Forest	0.60	0.651	0.60	0.612
3	XGBoost	0.60	0.651	0.60	0.612

 ## Key Findings
  Feature important analysis showed that smoking status, age and BMI were 
  among the strongest predictors of insurance premium risk.

  ## Future imporovements
  -Hyperparameter tuning using GridSearchCv
  -Cross-validation
  -Larger real-world insurance datasets
  -Model deployment using streamlit or flask

  ##Author
  **Angeline Oyaro**
  Actuarial science Graduate 
  Interested in insurance Analytics, Underwriting and Machine Learning.
  







 
 
                       
