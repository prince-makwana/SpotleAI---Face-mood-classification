# SpotleAI---Face-mood-classification

The mood detector app is used for classifying 3 classes – sad, happy and fear. There were outliers in datasets. So, we removed those outliers and enhance the image by histogram equalization techniques. There was class imbalancing in datasets. Therefore, to split in datasets in train-test, Stratified Shuffle Split method. We have first applied transfer learning on given datasets. But it was found to be not great in accuracy. So, we have designed our customed model for mood detection. We have fine tuned our customed model on the basis of different hyperparameters i.e., hidden layer, learning rate, optimizers, algorithms, etc. and selected the best custom model. We have used early stopping criteria to protect from overfitting the model and ReduceLROnPlateau to reduce the learning rate if performance of model does not increase. We observed the model reaches a validation accuracy around 91%.

