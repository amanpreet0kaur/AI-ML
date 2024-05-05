Handwritten Digit Recognition with TensorFlow and Keras
This repository contains Python code for building a neural network model using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. The code demonstrates the process of data loading, preprocessing, model creation, training, evaluation, and performance analysis.

Key Features:
Data Loading: The MNIST dataset, comprising grayscale images of handwritten digits (0-9), is loaded into training and testing datasets.
Data Preprocessing: Pixel values of the images are normalized to the range [0, 1], and the images are flattened for model input.
Model Creation: Initially, a simple neural network with a single Dense layer is created. Later, a more complex model with a hidden layer is introduced to improve accuracy.
Model Training: The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function.
Model Evaluation: The trained model is evaluated on the test dataset to assess its accuracy.
Performance Analysis: Confusion matrices are generated to analyze the model's performance in classifying digits.
Instructions for Use:
Clone the repository to your local machine.
Ensure you have Python, TensorFlow, Keras, Matplotlib, and NumPy installed.
Run the Python script to train and evaluate the model.
Experiment with different model architectures, hyperparameters, and preprocessing techniques to improve performance.
