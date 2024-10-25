# Deep Learning Challenge

---

## Overview

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With our knowledge of machine learning and neural networks, we'll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

---

## Results

- **Data Processing**
    - The variable that was the target of our model was the 'IS_SUCCESSFUL' column of the data frame that contained 1 and 0 values that states whether an applicant was successful or not when funded by Alphabet Soup
    - The features for our model were every column except 'IS_SUCCESSFUL'
    - The variables that should be removed from the input data are 'EIN', and 'NAME'

- **Compiling, Training, and Evaluating the Model**
    - We had 2 hidden layers, first one with 80 neurons and the second one with 30 neurons. Activation function were relu for the two hidden layers and sigmoid for the output layer. 
    - Our target model performance was 75 percent or greater, however we were not able to achieve this with our model only having the accuracty of around 72.8 percent
    - We took some steps to attempt to increase the model performance. We increased the neurons in each layer, added another hidden layer, and changed the activation function for two of the three hidden layers. Our accuracy after doing these changes was still around the same at 72.81 percent.
