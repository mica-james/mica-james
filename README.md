- 👋 Hi, I’m @mica-james
- This Project is called Spam vs Legitimate Email Detector
- The project's purpose was to take an existing database of spam and legitimate emails and seperate them.
- For the project, the user would need to download the SpamAssassin database of spam and legitimate emails.  
- The user would also need to have Thonny or any other IDE that can run Python code.
- A test that I ran was the code below... This seperates the emails with 0 being legitimate and 1 being spam.
    result = model_4.predict(['your microsoft account has been compromised, you must update before or else your account going to close click to update'])
    print(result)

    result = model_4.predict(['Today we want to inform you that the application period for 15.000 free Udacity Scholarships in Data Science is now open! Please apply by November 16th, 2020 via https://www.udacity.com/bertelsmann-tech-scholarships.'])
    print(result)
- I also used 4 different classifiers to show accuracy, precision, and recall. The example below is the Confusion Matrix.
    y_pred = model.predict(X_test)
    confusion_matrix(y_pred, y_test)

    print("Confusion Matrix:")
    print(confusion_matrix(y_pred, y_test))
    print("Accuracy :", accuracy_score(y_pred, y_test))
    print("Precision :", precision_score(y_pred, y_test, average = 'weighted'))
    print("Recall :", recall_score(y_pred, y_test, average = 'weighted'))
- My name is Mica James and below is my LinkedIn link as well as my email.
    - https://www.linkedin.com/in/micajames/
    - mica.james19@gmail.com 

<!---
mica-james/mica-james is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
