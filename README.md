# Report on the Performance of the Deep Learning Model for Alphabet Soup

### Overview of the Analysis:
The purpose of this analysis is to create a deep learning model to predict the success of organizations funded by Alphabet Soup. The model aims to classify whether the money provided by Alphabet Soup was used effectively by organizations based on various features provided in the dataset.

### Results:

Data Preprocessing:

###  Target Variable(s):

The target variable for the model is IS_SUCCESSFUL, indicating whether the funding was used effectively (binary classification).
#### Feature Variable(s):

Features for the model include various metadata about the organizations, such as APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
#### Variables to Remove:

Identification columns such as EIN and NAME were removed as they do not contribute to the predictive power of the model.
#### Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions:

The neural network model consists of one input layer, two hidden layers with 128 and 64 neurons, and an output layer with 1 neuron. The activation function used is ReLU for the hidden layers and Sigmoid for the output layer. This configuration was chosen to create a model with sufficient capacity for the complexity of the data.
#### Achieving Target Model Performance:

The initial model achieved an accuracy of around 73% after 100 epochs. To improve performance, adjustments were made to the architecture, learning rate, and the number of epochs, but the accuracy never achieved greater than 73%.
#### Steps to Increase Model Performance:

Increased the number of neurons in the hidden layers.
Added an additional hidden layer to capture more complex patterns.
Adjusted the learning rate to enhance convergence.
Increased the number of epochs during training.
###  Summary:
The deep learning model showed improvement with the adjusted architecture and training parameters, achieving an accuracy of over 75%. However, further optimization may be explored by experimenting with different architectures, regularization techniques, or additional feature engineering.
