# Diabetes Prediction Using Machine Learning

![Test Image 1](https://res.cloudinary.com/grohealth/image/upload/c_fill,f_auto,fl_lossy,h_650,q_auto,w_1085/v1581695681/DCUK/Content/causes-of-diabetes.png)
# Introduction
Diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. Symptoms of high blood sugar include frequent urination, increased thirst, and increased hunger. If left untreated, diabetes can cause many complications. Acute complications can include diabetic ketoacidosis, hyperosmolar hyperglycemic state, or death. Serious long-term complications include cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

# Objective
We will try to build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes or not?

# Method
In this section we shall learn about the various classifiers used in machine learning to predict diabetes. We shall also explain our proposed methodology to improve the accuracy. The Pima Indians Diabetes Dataset is used in this study. Grid Search is a technique in machine learning used to search for the best set of hyperparameters for a given model is used in this study. The proposed framework is divided into different phases. Python Jupyter Note was used for the entire implementation. Different packages such as NumPy, pandas, scikit, and Matplotlib have been used in analyzing the data. The model is developed using the Python programming language.

# Details about the dataset
The Pima Indian Diabetes Dataset (PIDD) is a widely used dataset in the field of machine learning and diabetes research. We can accessible this dataset from the University of California, Irvine (UCI) AI repository under the name "Pima Indians Diabetes Dataset" and is available online in free. PIDD consists of medical data collected from Pima Indian women in Arizona, United States. The dataset contains various features such as the number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, body mass index (BMI), diabetes pedigree function, and age, along with the target variable indicating whether or not an individual has diabetes. The PID dataset contains 768 records each with 9 attributes.The dataset consists of two classes,the number of non-diabetic patients is 500 and it is labelled as 0,the number of patients with diabetes is 268 and is labelled as 1. The PID dataset is divided into two a training and test dataset. The training dataset consists of 614 records. The training dataset was used to train the machine learning models. The test dataset consists of 154 records. The test dataset is used to test the performance of the machine learning models that have been trained.Table 1 shows the attributes and description of the PID dataset.

# Result 
Machine learning (ML), a subset of artificial intelligence, has the potential to revolutionize diabetes risk prediction and early identification. Early detection and accurate prediction of diabetes can significantly contribute to effective management and prevention of complications.The fundamental goal of this study was to prepare and imsplement Diabetes Prediction using various machine learning techniques, followed by an output analysis to identify the best classifier with the highest accuracy, that we have successfully achieved this goal. This work focuses on improving the accuracy of diabetes prediction by tuning the hyperparameters of the proposed model and evaluating different machine learning classification techniques.Among these techniques, KNN is more effective and produce better results than other ML classification techniques. The KNN algorithm achieved a classification accuracy of 82.47%.

