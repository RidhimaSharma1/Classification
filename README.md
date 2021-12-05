# Classification
**1. HR analytics uses employee data to improve talent management and business outcome.**

In this python script, Analytics Vidhya Jobathon dataset has been used to predict the attrition of employees.
In this script we have used classification technique to predict if an employee is likely to leave the company.<br/>
The features which has been considered in this model are:<br/>
a) Date of Joining<br/>
b) City<br/>
c) Education Level<br/>
d) Gender<br/>
e) Quarterly Rating<br/>
f) Total Business Value<br/>
g) Designation (Joining and current)<br/>
h) Age<br/>
i) Salary<br/>
And date of last working day has been used as the target column (which has been converted into Target of 0 and 1, 
where 0 means person has served the last working day and 1 means employee is still part of the organization)



**2. Text Classification problem to assign a category to text data**

In text classification script, binary class dataset has been used where label is 1 for actual patient and 0 fake patient.<br/>
This classification model is build using BERT transformation model. BERT is a pre-trained transformer model developed by Google.<br/>
Accuracy of this model is 87%, this can be increased by increasing number of epochs<br/>
(Note:- increase in no. of epochs can also lead to overfitting. Hence it is important to iterate training data for right number of epochs, 
therefore giving a large number as epochs and using "early stop" technique is a common practise to avoid overfitting. 
In this technique, model stop training when the error rate of validation data is minimum.)<br/>
The major feature used in this model is "Link" as it cover text in other features of the dataset including "Topic" and "Host".
Another feature that can be considered for the classification is "Source", this can improve the performence by including more context.



**3. Linear Classification to classify records into two groups using the features and their relations with target category**

In this classification problem, kaggles titanic dataset has been used. The target variable has categories 0 "Not Survived" and 1 "Survived".<br/>
To create this classification data pre processing was required as Linear model does't support categorical or qualitative parameters.<br/> The features which are
considered in this model are - <br/> a) "Age"<br/> b) "Fare"<br/> c) "Pclass - Ticket class"<br/> d) "SibSp - siblings / spouses aboard" <br/> e) "Parch - parents / children aboard" <br/> f)"Sex_male"<br/> g) 'Embarked_Q'<br/> h) 'Embarked_S' <br/> i) "Fare"<br/>
To train this model multiple models has been tried including SVM, Naive Bayes, Logistic Regression and stacking of Random forest with other models. Logistic regression has performed the best with 81% accuracy, hence LR has been used to predict the unseen test data.
