# Classification-of-MNIST-and-USPS-Image-Dataset-Using-Machine-Learning
The goal of this project is to implement machine learning models for the task of classification 

At first I implemented an ensemble of four classifiers for a given task. Then the results of the individual classifiers are combined to make a final decision.

The classification task will be that of recognizing a 28×28 grayscale handwritten digit image and
identify it as a digit among 0, 1, 2, ... , 9. Training was done with the following four classifiers using
MNIST digit images.

1. Logistic regression, which I implemented using backpropagtion and tuning hyperparameters.
2. Multilayer Perceptron Neural Network
3. Random Forest 
4. Support Vector Machine (SVM)
5. Ensemble Classifier ( Majority Voting)

After trainining the models on the MNIST image dataset, the model was used to predict image dataset of USPS.

Confusion Matrices were made for each classification models.

The image dataset of USPS can be found here - https://drive.google.com/file/d/1nbnN6pGagQVuZXIcbeRrktOZpHygq2n1/view?usp=sharing


