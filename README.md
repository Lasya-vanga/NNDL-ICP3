Neural-Networks-Deep-Learning---ICP-3 Summer 2024: CS5720: Neural Network Deep Learning: In Class Programming Assignment-3
Name: Lasya Vanga ID: 700762893

Use Case Description:
Predicting the diabetes disease
Programming elements:
Keras Basics
1. Use the use case in the class:
a. Add more Dense layers to the existing code and check how the accuracy changes.
2. Change the data source to Breast Cancer dataset * available in the source code folder and make required
changes. Report accuracy of the model.
3. Normalize the data before feeding the data to the model and check how the normalization change your
accuracy (code given below). from sklearn.preprocessing import StandardScaler sc = StandardScaler()
Use Image Classification on the hand written digits data set (mnist)
1. Plot the loss and accuracy for both training data and validation data using the history object in the source
code.
2. Plot one of the images in the test data, and then do inferencing to check what is the prediction of the model
on that single image.
3. We had used 2 hidden layers and Relu activation. Try to change the number of hidden layer and the
activation to tanh or sigmoid and see what happens.
4. Run the same code without scaling the images and check the performance?

Code File - NNDL-ICP3-700762893.ipynb Document- NNDL-ICP3-700762893.pdf
