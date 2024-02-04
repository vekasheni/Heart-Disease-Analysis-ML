# Heart-Disease-Analysis

#**Importing the required libraries** like 

  Numpy, Pandas, Seaborn, Matplotlib, Decision Tree, Random forest, Logistic regression, Support Vector Machines.

#**About the dataset**

1.age

2.sex

3.chest pain type (4 values)

value 0: typical angina

value 1: atypical angina

value 2: non-anginal pain

value 3: asymptomatic

4.trestbps: resting blood pressure (in mm Hg on admission to the hospital)

5.chol: serum cholestrol in mg/dl

6.fbs: (fasting blood sugar> 120 mg/dl)(1 = true; 0 = false)

7.restecg: resting electrocardiographic results

value 0: normal

value 1: having ST-T wave abnormality(T wave inversions and/or ST elevation or depression of> 0.05 mV)

value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

8.thalach: maximum heart rate achieved

9.exang: exercise induced angina (1=yes; 0=no)

10.oldpeak = ST depression induced by exercise relative to rest

11.slope: the slope of the peak exercise ST segment

value 1: upsloping

value 2: flat

value 3: downloping

12.ca: number of major vessels (0-3) colored by flourosopy

13.thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

14.target: 0=less chance of heart attack, 1 = more chance of heart attack

#**Loading the dataset and doing data analysis**

1.Load the dataset

2.Display first 10 rows

3.Getting info about the dataset

4.Checking for null values

#**Data Visualization**

1.Countplot for persons having disease and not having disease

![image](https://github.com/vekasheni/Heart-Disease-Analysis/assets/146317452/4546b627-dfae-4c7f-9e7f-a6030eb58205)

2.**Correlation Matrix- Heatmap**

  A correlation matrix is a statistical technique used to evaluate the relationship between two variables in a data set. The matrix is a table in which every cell contains a correlation coefficient, where 1 is considered a strong relationship between variables, 0 a neutral relationship and -1 a not strong relationship.
  
![image](https://github.com/vekasheni/Heart-Disease-Analysis/assets/146317452/88acbd31-b4bd-433d-80e9-4811f725cf1c)


#**Logistic Regression Classifier**

  Logistic Regression is a classification algorithm, used to classify elements of a set into two groups (binary classification) by calculating the probability of each element of the set Logistic Regression is the appropriate regression analysis to conduct when the dependent variable has a binary solution, we predict the values of categorical variables.

  **Accuracy** of the Logistic Regression classifier is about **88%**
  
  ![image](https://github.com/vekasheni/Heart-Disease-Analysis/assets/146317452/f03c54ec-5f96-4972-8411-420291c83f78)


#**Decision Tree Classifier**

   **Accuracy** of the Decision Tree classifier is about **97%.**

     Logistic Regression is a classification algorithm, used to classify elements of a set into two groups (binary classification) by calculating the probability of each element of the set Logistic Regression is the appropriate regression analysis to conduct when the dependent variable has a binary solution, we predict the values of categorical variables.
   
   ![image](https://github.com/vekasheni/Heart-Disease-Analysis/assets/146317452/e8dd365c-af43-4993-9522-80807f7d6bd7)


 #**Random forest classifier**

   Random Forest is a robust machine learning algorithm that can be used for a variety of tasks including regression and classification. It is an ensemble method, meaning that a random forest model is made up of a large number of small decision trees, called estimators, which each produce their own predictions. The random forest model combines the predictions of the estimators to produce a more accurate prediction.

   **Accuracy** of the Random Forest classifier is about **86%.**
   
   ![image](https://github.com/vekasheni/Heart-Disease-Analysis/assets/146317452/ad64b241-9c5c-4d32-a064-1f67eadee2f4)


 #**Support Vector Machines**

   It is a supervised machine learning problem where we try to find a hyperplane that best separates the two classes. Note: Don’t get confused between SVM and logistic regression. Both the algorithms try to find the best hyperplane, but the main difference is logistic regression is a probabilistic approach whereas support vector machine is based on statistical approaches.

   **Accuracy** of the Support Vector Machines is about **87%.**
   
   ![image](https://github.com/vekasheni/Heart-Disease-Analysis/assets/146317452/b9065568-1087-457c-b945-ee5856bda676)

