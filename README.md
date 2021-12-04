# Classification
**HR analytics uses employee data to improve talent management and business outcome.**

In this python script, Analytics Vidhya Jobathon dataset has been used to predict the attrition of employees.
In this script we have used classification technique to predict if an employee is likely to leave the company.
The features which has been considered in this model are:
a) Date of Joining
b) City
c) Education Level
d) Gender
e) Quarterly Rating
f) Total Business Value
g) Designation (Joining and current)
h) Age
i) Salary
And date of last working day has been used as the target column (which has been converted into Target of 0 and 1, 
where 0 means person has served the last working day and 1 means employee is still part of the organization)


**Text Classification**

In text classification script, binary class dataset has been used where label is 1 for Sincere patient and 0 InSincere patient.
This classification model is build using BERT transformation model. BERT is a pre-trained transformer model developed by Google.
Accuracy of this model is 87%, this can be increased by increasing number of epochs
(Note:- increase in no. of epochs can also lead to overfitting. Hence it is important to iterate training data for right number of epochs, 
therefore giving a large number as epochs and using "early stop" technique is a common practise to avoid overfitting. 
In this technique, model stop training when the error rate of validation data is minimum.)
The major feature used in this model is "Link". Link has been used as the feature because the link is consist of the "Topic" and "Host".
Another feature that can be considered for the classification is "Source", this can improve the performence by including more context.
