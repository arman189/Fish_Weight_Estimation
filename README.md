# Fish_Weight_Estimation
Fish Weight Estimation is a predictive model using machine learning algorithm named logistic regression which predicts the weight of fish based on various factor.

<br/>**Objectives:-**  To estimate the fish weight.
<br/>**Software Used:-** Anaconda, Jupyter Notebook, pyqt5
<br/>**Algorithm Used:-** Logistic Regression
<br/>**Definition:-** Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.
<br/>**Data Processing Techniques:-**
<br/>1. Labelling string values using LabelEncoder().
<br/>**How to:-**
<br/>1. Read the csv file using pandas opencv() function.
<br/>2. Apply Data Processing technique to clean the data.
<br/>3. Divide data set into x and y; x having independents values and y having dependents variables.
<br/>4. Further dividing x and y into x_test, x_train, and y_test, y_train respectively using train_test_split().
<br/>5. Initialize the model by importing  LogisticRegression from sklearn.linear_model.
           <br/>-> from sklearn.linear_model import LogisticRegression
           <br/>-> model=LogisticRegression()
<br/>6. Train the model.
           <br/>-> model.fit(x_train,encoded)
<br/>7. Estimate the weight of fish .


**OUTPUT**

![Screenshot (40)](https://user-images.githubusercontent.com/70680425/135617282-84b52693-4957-41c8-a5b1-0499e781ff15.png)

