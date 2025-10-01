This repository contains an implementation of a deep neural network (DNN) using TensorFlow/Keras to classify images from the Fashion MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images of clothing items (such as shirts, shoes, and bags), each represented as a 28×28 grayscale image.

🔑 Key Features

Data Preprocessing

Normalizes image pixel values from [0,255] to [0,1].

Splits data into training and test sets.

Visualizes sample images using matplotlib.

Model Architecture (15 Layers Total)

Input layer: Shape (28,28) images.

Flatten layer: Converts 2D images into 1D vectors.

Dense hidden layers with ReLU activation (512 → 256 → 128 → 64 → 32 → 16).

Output layer: 10 units with softmax activation for multi-class classification.

Training & Evaluation

Optimizer: Adam

Loss: Sparse Categorical Crossentropy

Metric: Accuracy

Trains for 10 epochs with batch size 128.

Validates model on the test dataset.

Prints test accuracy and loss after evaluation.

Visualization

Displays the first 9 training images in a 3×3 grid.

📊 Results

Prints training/validation accuracy during training.

Outputs final test accuracy and loss.

Provides visualization of sample images for quick inspection.

🛠️ Tech Stack

Python

TensorFlow / Keras

NumPy

Matplotlib
