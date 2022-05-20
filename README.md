# Prediction-of-COVID-19-using-Chext-X-ray-Images-Convolutional-Neural-Network--CNN-

In this project, Built and trained a convolutional neural network in Keras with TensorFlow as backend from scratch to predict patients if they were infected with COVID-19 or not using their chest X-ray images. 
Matplotlib was used for data visualization. Data preprocessing and data augmentation was carried out using tensorflow 2.0
The model used was sequential with a combination of convolutional layers, pooling layers, dropout layers, dense layers with relu activation and output layer with sigmoid activation.  The dataset contained the lungs X-ray images of both groups i.e non-covid and covid infected patients. The dataset was obtained from kaggle. Metrics chosen for model evaluation were Training set, test set and validation set accuracy. Adam optimizer with learning rate of 0.001 was choosed for gradient descent
The entire project was carried out on the Google Colab environment
Results of the model were following:

1) Training Set Accuracy : 97.38 %
2) Training Set Loss : 0.0875

3) Validation Set Accuracy : 97.79 %
4) Validation Set Loss: 0.0744

5) Test Set Accuracy : 98.14 %
6) Test Set Loss : 0.06641

Google Colab Project Link : https://colab.research.google.com/drive/1oeA2Rp5B_8VWtOXEoY7R4dQMaO4pZe_y?usp=sharing

![image](https://user-images.githubusercontent.com/77073932/128634391-9ea593fd-87c6-4646-88d6-573adeb3b6a5.png)
