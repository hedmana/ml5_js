# Machine learning with ml5.js
I created this repository for me to try out different machine learning methods using the ml5.js library:

- ml5.js: https://ml5js.org/

To test out the different programs just open their corresponding "index.html" file in your browser.

## Animal Classification
The image_classification folder contains a simple web app based on the pre-trained MobileNet image classification model, found in the ml5.js library. Here's a list of what the model has been trained to recognize: https://github.com/ml5js/ml5-library/blob/main/src/utils/IMAGENET_CLASSES.js. To test the app just wait for the MobileNet model to load, and drop an image (JPG) in the box. 

![Alt Text](gifs/animal_classification.gif)

## Neural Network
Under the neural_network folder you'll find a simple web app that visualizes the training process of a neural network. The program includes three stages: data collection, model training, and predictions.

### Data Collection
During the data collection stage, the user is able to place different characters within a square. Characters are placed by clicking the desired character on the keyboard and the placing it with a mouse click. Make sure to place at least to types of characters before training the model. 

![Alt Text](gifs/data_collection.gif)

### Model Training
When the user is happy with the placed characters, the model is trained by pressing ENTER.

![Alt Text](gifs/model_training.gif)

### Predictions
After the training is done, the user can now click the square to plot predictions generated by the model.
![Alt Text](gifs/predictions.gif)