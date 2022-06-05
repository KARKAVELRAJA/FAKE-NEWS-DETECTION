# FAKE-NEWS-DETECTION

### PYTHON CODE TO DETECT FAKE NEWS USING PASSIVE AGGRESSIVE CLASSIFIER

-----

### PASSIVE AGGRESSIVE CLASSIFIER

- Passive Aggressive Classifier is an Online-Learning Algorithm that gets a training example, update the classifier, and then throw away the example
- Passive: If the prediction is correct, keep the model and do not make any changes i.e., the data in the example is not enough to cause any changes in the model
- Aggressive: If the prediction is incorrect, make changes to the model i.e., some change to the model may correct it

-----

### WORKFLOW OF FAKE NEWS DETECTION

- Loading Libraries and dataset
- Pre-processing the Dataset
- Dataset is splitted into Training and Testing Data
- Applying Text Feature Extractor - TD-IDF Vectorizer
- Loading the PASSIVE AGGRESSIVE CLASSIFIER Algorithm
- Training the Model using the training dataset
- Testing the Model using the testing dataset
- Performing Classification
- Calculating the Accuracy
