# Alphabet Soup Neural Network Challenge Module 13

Objective: The goal is the challenge is to create a model that predicts whether start up applicants will become successful if funded by Alphabet Soup.  The approach is to use different neural network models using python coding in a jupyter notebook.  The code to then compares metrics of the models for accuracy to determine which one is best.
The file containing the python coding for the neural network coding is named: 
venture_funding_with_deep_learning.ipynb
The filkes containing the 3 separate  neural network models are: AlphabetSoup.h5, nn_A1.h5, and nn_A2.h5

## Prepare the data for use on a neural network model.
The code first reads the CVS file that has the data we will use as our dataframe for the neural model.  The code then cleans the data by removing 2 colukns and then using OneHotEncoder modifies the categorical variables of the dataframe. The code them concatenates the original numerical variables with the encoded categorical variables in one main dataframe.
Before we set up our neural models the last preparation step is to set the target variables (Y and x) and split the data for the training and testing data sets to be used.

## Neural network , Optimization and comparison
Next we set up  neural model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.  The code then runs 3 different models with changes in the number of layers, nodes and epoch variables of 3 neural models. The code also saves the models as a HDF5 file
The code finally shows the summary metrics of the 3 neural models to determine which one has the better metrics for potential application.

#### Resources
Fintech bootcamp class materials and in class examples
Tutoring session 3/21/24 





