----------------------------
##Details of the Project-
----------------------------
Language Used-Python
----------------------------
Code editor and compiler used- Visual Studio Code
------------------------------------------------------------------------------------
##Information of every column of the dateset used for the project-
----------------------------
1.Number of times Pregnant
----------------------------
2.Plasma Glucose Concentration og 2 hours in an oral glucose
----------------------------
3.Diastolic blood Pressure (mm Hg)
----------------------------
4.Triceps Skin fold Thickness (mm)
----------------------------
5.2-Hour serum Insulin (mu m/ml)
----------------------------
6.Body mass Index (weight in kg/(height in metre)^2)
----------------------------
7.Diabetes Pedigree Function
----------------------------
8.Age (in years)
----------------------------
9.Class Function (0 or 1)
----------------------------
These were the parameters used in the dataset for detecting diabaties in a person.
-------------------------------------------------------------------------------------
##Additional Information-
----------------------------
Deep Neuaral Network(DNN) model was used in the project for training the model.
----------------------------
As data was limited training and testing data used is the same.
-------------------------------------------------------------------------------------
##Code Information-
----------------------------
#Libraries Used-
----------------------------
Loadtxt-To handle the dateset file
----------------------------
Sequential-It is used for creating an empty stack of hidden layers for the neural network
----------------------------
Dense-Used to indicate which type of layers will be used. Dense indicates we will be using Dense layers, whereas, using conv would indicate using convolutional layers.
----------------------------
model_from_json-Used to store the trained model in a json file for the test code and further deployment.
----------------------------
The Activation function used is Sigmoid function as the output is the form of binary. For the hidden layers Relu function is used.
----------------------------
While setting the epochs, small and very large values were avoided in order to avoid underfitting and overfitting.
