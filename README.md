# MNIST Digit Recognition Model

## Project Overview
This repository hosts a TensorFlow-based neural network model designed to classify handwritten digits from the MNIST dataset. The project demonstrates the application of deep learning techniques to recognize numerical digits, providing a foundation for further exploration into machine learning and image processing.

## Features
- **Data Visualization**: Initial display of MNIST dataset images.
- **Preprocessing**: Normalization of images to prepare data for training.
- **Neural Network Architecture**: A sequential model with multiple dense layers.
- **Training and Evaluation**: Model training and accuracy evaluation on the MNIST test set.

## Technologies Used
- Python
- TensorFlow
- Keras
- Matplotlib

## Getting Started
To run this project, follow these steps:

1. **Clone the repository:**


2. **Install required libraries:**


3. **Run the notebook:**
Navigate to the notebook directory and launch Jupyter Notebook:



## Model Architecture
The model consists of:
- Input layer: Flatten the 28x28 image data.
- Hidden layers: Two layers with 128 nodes each, using ReLU activation.
- Output layer: A softmax layer with 10 nodes corresponding to the digit classes.

## Results
- After training for 3 epochs, the model achieves an accuracy of approximately 97% on the test set. 

## Authors
- Youssef

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
