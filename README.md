# brain-tumor-classification

Description
This project classifies brain MRI scans into four categories using a Convolutional Neural Network (CNN):

Glioma Tumor
Meningioma Tumor
No Tumor
Pituitary Tumor
The dataset used is from Kaggle’s Brain Tumor MRI Dataset.

Dataset
The dataset consists of MRI images divided into:

Training Set: Contains images for training the model.
Testing Set: Contains images for evaluating the model’s performance.
Each set contains four categories of brain tumors.

Model Architecture
The model is a Convolutional Neural Network (CNN) built using TensorFlow and Keras. The architecture includes:

Convolutional Layers: Three layers with increasing filter sizes (32, 64, 128) and ReLU activation.
Max Pooling Layers: Applied after each convolutional layer to reduce spatial dimensions.
Flatten Layer: Flattens the output from the convolutional layers to a 1D vector.
Dense Layers:
One fully connected dense layer with 128 neurons and ReLU activation.
A dropout layer with a rate of 0.5 to prevent overfitting.
Output Layer: A dense layer with 4 neurons (corresponding to the 4 tumor categories) and softmax activation.

Test Accuracy: 72% (example result, update with your actual result)
Confusion Matrix:
The confusion matrix shows how well the model predicted each class.

Classification Report:
The classification report includes Precision, Recall, and F1-score for each category
