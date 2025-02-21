# Phishing-Detection-Model
***Phishing is a type of fraud where an attacker impersonates a trusted entity or individual through email or other communication channels to obtain sensitive information, such as login credentials or account details.*** Typically, the victim receives a message that appears to come from a known contact or organization. This message may contain malicious software designed to compromise the user’s computer or include links to deceptive websites that trick victims into revealing personal and financial informations.<br>
The dataset contains many columns such as URL_length, use of @ symbols,double slash symbol is present or not, haveing sub domain etc where values like -1,0 and 1 is given where <br>
__1 means its Legitimate__ ✅ <br>
__0 means Suspicious__ 🤔🤨 <br>
__-1 means its Phishing__ 👎🙅‍♀️🙅‍♂️ <br>
A Support Vector Classifier, along with RandomForest, AdaBoost, and XGB Classifier, was developed to identify the model with the highest accuracy. <br>
Analysis revealed that RandomForest and XGB Classifier outperformed the others. <br<
Predictions were made on new data, and the models achieved an impressive overall accuracy of __97%__.
