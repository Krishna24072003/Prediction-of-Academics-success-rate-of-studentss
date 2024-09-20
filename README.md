**Project:Student Success Prediction**

**Overview**

This project aims to predict the success of students in higher education institutions based on various factors such as demographics, academic background, and socio-economic factors.
The project uses a dataset containing information on students enrolled in different undergraduate degrees and their academic performance at the end of the first and second semesters.

**Dataset**

The dataset used in this project is a tabular dataset with 37 columns and 4424 rows. The dataset includes information on:

1.Demographics (marital status, nationality, etc.)
2.Academic background (previous qualification, admission grade, etc.)
3.Socio-economic factors (mother's occupation, father's occupation, etc.)
4.Academic performance (curricular units, grades, etc.)
**Methodology**

The project uses a machine learning approach to predict student success. The following steps were taken:

**1.Data preprocessing:** The dataset was cleaned and preprocessed to handle missing values and outliers.
**2.Feature engineering:** New features were created to improve the accuracy of the model.
**3.Model selection:** Different machine learning models were trained and tested to select the best model.
**4.Hyperparameter tuning:** The hyperparameters of the selected model were tuned to improve its performance.
**5.Model evaluation:** The performance of the model was evaluated using metrics such as accuracy, precision, recall, and F1-score.
**Results**

The best model selected was a Random Forest Classifier, which achieved an accuracy of 91.7% on the test set. 
The model was able to predict student success with a high degree of accuracy, indicating that the factors used in the model are relevant predictors of student success.

**Conclusion**

This project demonstrates the potential of machine learning in predicting student success in higher education institutions. 
The results of this project can be used to identify students who are at risk of dropping out or not succeeding, and to develop targeted interventions to support these students.

**Future Work**

1.Collect more data to improve the accuracy of the model
2.Use other machine learning models to compare their performance
3.Use feature selection techniques to reduce the number of features used in the model
4.Use the model to predict student success in other institutions or contexts

**Requirements**

1.Python 3.11
2.scikit-learn
3.pandas
4.numpy
5.matplotlib
6.seaborn
7.imbalanced-learn

**Usage**

1.Clone the repository
2.Install the required libraries
3.Run the notebook to train and test the model
4.Use the model to make predictions on new data
