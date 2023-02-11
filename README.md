# online-serving-of-ML-model
online-serving of ML model
In this assignment, we will build a docker container to perform online serving of a ML
model. 
We need the following files:
● Dockerfile
● Train.py
● Inference.py
This is the EEG brainwave data that has been processed using statistical extraction.
There are totally 1300 rows and 162 columns in the train dataset. The feature Letter is
used as the target column. It has 26 classes which is a representation of the 26
alphabets.

Task:
train.py
1. Add one more model apart from the one used in TA Session (any machine
learning model of your choice) in the train.py file and save it. 
2. Modify the inference.py file to display the output of the above model. 
3. Build the docker image of the final application and run it and submit the
screenshot of the output. 
a. Build the Docker File
b. running the api.py file provides different flask routes for prediction and score using LDA and neural network
