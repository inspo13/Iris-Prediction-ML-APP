# Iris-Prediction-ML-APP

#Contributor Prachi Bhatt


Iris Prediction ML Model Deployed on Android App:-

This project consists of a classification example called the iris species prediction. The dataset contains three classes of 50 instances each, where each class refers to the type of iris plant.
Attribute information:
sepal length in cm
sepal width in cm
petal length in cm
petal width in cm
Based on the information given in the input, the Android App will predict whether the plant is Iris Setosa, Iris Versicolour, or Iris Virginica. 

Steps to create the project:
Download the iris data set (file name: iris.data) from https://archive.ics.uci.edu/ml/machine-learning-databases/iris/
Create a new python file with a name iris in the Syder editor. Put the iris.data file in the same directory where model.py resides.
After executing the line open(‘iris.tflite’,’wb’).write(tfmodel) a new file named iris.tflite will get created in the same directory where iris.data resides. 
Open Android Studio. Create a new kotlin-android project.
Right-click on app > New > Other >TensorFlow Lite Model.
Click on the folder icon.
Navigate to iris.tflite file.
Click on OK.
Your model will look like this after clicking on the finish.
Copy the code and paste it in the click listener of a button in MainActivity.kt.

Wooohoo, App is ready to use! 
