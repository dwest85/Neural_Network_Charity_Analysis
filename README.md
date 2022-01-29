# Neural_Network_Charity_Analysis

# Overview of the analysis
* The purpose of this analysis was to measure to success, or accuracy of the Charity using our deep-learning neural network, with our TensorFlow packaging. 

# Results
* The results can be measured through both attached AlphabetSoupCharity.h5 and AlphabetSoupCharityOptimization.h5 files. These were direct output prints of the many attemps using different weights and layers, while modeling the Charity Data through the "relu" and "sigmoid" functions. Several steps of data cleaning/processing was performing before running the neural network. Based on several attempts with different variables, the model accuracy only increased from 0.7285131216049194 to 0.7309620976448059, which was under the 75% projected output. 

![accuracy]()
![accuracy_opt]()

* The IS_SUCCESSFUL column from the Charity Data was considered our target data for the model.
![target_features]()

* The features were the following column data:
![features]()

# Compiling, Training, and Evaluating
* The weights and layers, along with the functional methods for the first accuracy model were as follows:
![weightsandlayers]()

* The optimized weights, layers, and functions (to achieve a projected goal of 75% or higher) were as follows:
![weightsandlayersopt]()

# Summary
* After several attemps to optimize the model accuracy (several methods overtrained resulting in a reduced accuracy), it has shown that the model is underperforming based on the projected results. A classifier model may produce better machine learning results.
