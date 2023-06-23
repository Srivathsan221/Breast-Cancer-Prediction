# Breast-Cancer-Prediction

![breast_cancer](https://github.com/Srivathsan221/Breast-Cancer-Prediction/assets/61115411/c07f68b1-ed97-48fe-bda6-21c4b6eacf04)

**ABSTRACT**

Breast cancer represents one of the diseases that make a high number of deaths every year. Around 12% of breast cancer occurs in women 20-34 years. It is the most common type of all cancers and the main cause of women’s deaths worldwide. 

Classification and data mining methods are an effective way to classify data. Especially in the medical field, where those methods are widely used in diagnosis and analysis to make decisions.

The aim is to observe which features are most helpful in predicting malignant or benign cancer and to see general trends that may aid us in model selection and hyper parameter selection. The goal is to classify whether the breast cancer is benign or malignant.

**PROBLEM STATEMENT**
Given the details of cell nuclei from breast mass, predict whether or not a patient has breast cancer using the Ensembling techniques. Perform necessary exploratory data analysis before building the model and evaluate the model based on performance metrics than model accuracy.

**Dataset Information**
The dataset consists of several predictor variables and one target variable, Diagnosis. The target variable has values 'Benign' and 'Malignant', where 'Benign' means that the cells are not harmful or there is no cancer and 'Malignant' means that the patient has
cancer and the cells have a harmful effect:

Variable Description:
1. Radius - Mean of distances from center to points on the perimeter
2. Texture - Standard deviation of gray-scale values
3. Perimeter - Observed perimeter of the lump
4. Area - Observed area of lump
5. Smoothness - Local variation in radius lengths
6. Compactness - perimeter^2 / area - 1.0
7. Concavity - Severity of concave portions of the contour
8. Concave points - number of concave portions of the contour
9. Symmetry - Lump symmetry
10. Fractal dimension - "coastline approximation" - 1
11. Diagnosis - Whether the patient has cancer or not? ('Malignant','Benign')

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

**SCOPE**
  •	Analyzing the available data and exploring relationships among given variables.
  • Data pre-processing.
  •	Training SVM classifier to predict whether the patient has cancer or not.
  •	Assess the correctness in classifying data with respect to efficiency and effectiveness of the SVM classifier in terms of accuracy,       sensitivity, specificity and AUC ROC.
  •	Tuning the hyperparameters of SVM classifier provided by the scikit-learn library.



