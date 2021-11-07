# Neural_Network_Charity_Analysis

# Overview of the Analysis
Use the features in the provided dataset to create a binary classifier that is capable of predicting
whether applicants will be successful if funded by Alphabet Soup.


# Results

Data Preprocessing
        -What variable(s) are considered the target(s) for your model?   IS_SUCCESSFUL
        -What variable(s) are considered to be the features for your model?   APPLICATION_TYPE, CLASSIFICATION,
        USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, AFFILIATION
        -What variable(s) are neither targets nor features, and should be removed from the input data?   'EIN' and 'NAME'
        
Compiling, Training, and Evaluating the Model
        -How many neurons, layers, and activation functions did you select for your neural network model, and why?   110 total
        neurons, 2 hidden layers, relu for the two input layers and sigmoid for the output layer
        -Were you able to achieve the target model performance?   Only achieved Accuracy: 0.7302623987197876
        -What steps did you take to try and increase model performance?   In my first attempt I raised epochs from
        50 to 100. This gave me an Accuracy: 0.7280466556549072. 
        In my 2nd attempt I added a third hidden layer with 20 neurons. This gave me a score Accuracy: 0.7294460535049438.
        In my 3rd attempt I change my activation output function to "tanh", and I got a score of Accuracy: 0.46565598249435425.
        
        
# Summary
I was not able to achieve an Accuracy score above 75%. I probably over complicated the model and should have used less neurons
and not changed the output activation function. 
