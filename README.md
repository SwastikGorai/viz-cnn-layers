# Visualize Outputs of CNN Layers

This repository contains code and necessary files for creating a submodel from a trained model by selecting certain layers from it. The trained model is taken from the repository at ```https://github.com/SwastikGorai/automatic-octo-umbrella``` . The submodel can then be used for prediction on a set of images, allowing you to visualize the outputs of the intermediate CNN layers.


### To use this code, you will need to:
* Provide the names of the layers you want to use 
* A set of images to run prediction on..

Once you have these, you are good to go.

### Steps to follow:
* Import the necessary modules and functions from the repository
* Load the trained model and select the desired layers by name
* Create a submodel using the selected layers
* Compile the submodel with the appropriate loss function and optimizer
* Run prediction on the set of images using the submodel
###

You can then visualize the outputs of the intermediate CNN layers using the visualization functions of matplotlib module.
