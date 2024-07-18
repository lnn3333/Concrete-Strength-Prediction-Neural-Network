# Concrete Strength Prediction Project
This project aims to predict the concrete strength using a neural network built with the Keras library. The project is divided into four parts, each focusing on different aspects of model training and evaluation.

## Part A: Build a Baseline Model 
### Requirements
Keras
Scikit-learn
Numpy
Pandas

### Description
In this part, we build a baseline neural network model with the following specifications:
-One hidden layer with 10 nodes and a ReLU activation function.
*Adam optimizer and mean squared error as the loss function.
  
### Steps
1. **Data Splitting:** Randomly split the data into training and test sets by holding 30% of the data for testing using train_test_split from Scikit-learn.
2. **Model Training:** Train the model on the training data using 50 epochs.
3. **Model Evaluation:** Evaluate the model on the test data and compute the mean squared error between the predicted and actual concrete strength using mean_squared_error from Scikit-learn.
4. **Repetition:** Repeat steps 1-3, 50 times, to create a list of 50 mean squared errors.
5. **Reporting:** Report the mean and the standard deviation of the mean squared errors.

## Part B: Normalize the Data 
### Description
Repeat Part A but using a normalized version of the data. Normalization involves subtracting the mean and dividing by the standard deviation for each predictor.

### Steps
1. Normalize the data.
2. Repeat steps 1-5 from Part A.
   
## Part C: Increase the Number of Epochs 
### Description
Repeat Part B but train the model using 100 epochs.

### Steps
1. Normalize the data.
2. Train the model with 100 epochs.
3. Repeat steps 1-5 from Part A.
   
## Part D: Increase the Number of Hidden Layers 
### Description
Repeat Part B but use a neural network with three hidden layers, each with 10 nodes and a ReLU activation function.

## Credits
This project was inspired by and uses materials from the IBM course "Deep Learning and Neural Networks with Keras".
