Task-04
Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

Dataset : https://www.kaggle.com/datasets/gti-upm/leapgestrecog

Project includes : 
Data Loading and Preparation: Loads images of hand gestures from the LeapGestRecog dataset, preprocesses them (resizing, grayscale conversion), and prepares them for model training.

Model Architecture: Constructs a convolutional neural network (CNN) using Keras Sequential API with multiple convolutional layers, activation functions (ReLU), max-pooling layers, dropout regularization, and dense layers with softmax activation for classification.

Training and Evaluation: Compiles the model with categorical cross-entropy loss and RMSprop optimizer. Trains the model on the training data, evaluates its performance on the test data, and visualizes training/validation loss and accuracy over epochs.

Performance Evaluation: Computes and visualizes a confusion matrix to assess the model's performance in classifying hand gestures.
