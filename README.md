Enhanced ResNeXt-50 Model for Leaf Disease Classification

Overview
This repository contains the implementation of an Enhanced ResNeXt-50 model for leaf disease classification. The model utilizes a combination of Stochastic Pooling, Swish Activation, Cardinality Blocks, and Cat Swarm Optimization (CSO) to improve the performance of classifying leaf diseases, specifically focusing on okra leaf disease severity classification.

The model is designed to predict the severity level of diseases from images of okra leaves. The output classes are Low, Moderate, and Severe. This model is based on the ResNeXt-50 architecture, which is enhanced with custom blocks and layers to optimize performance.

Features
Swish Activation Function: A novel activation function to improve non-linearity.

Stochastic Pooling: Replaces traditional pooling with stochastic pooling to increase the representational power.

Cardinality Block: Utilizes multiple branches of convolutions for better feature extraction.

Cat Swarm Optimization (CSO): Applied to optimize the training process.

Customizable: The model is highly customizable with adjustable hyperparameters and configurable layers.

Model Architecture
Swish Activation: Used instead of ReLU to enhance model performance.

Stochastic Pooling: Replaces traditional pooling layers to improve feature learning.

Cardinality Blocks: Provides a better feature extraction mechanism by introducing multiple convolutional branches.

ResNeXt-50 Backbone: The main architecture that handles feature extraction from the images.

Training Hyperparameters
Learning Rate: 1e-4

Optimizer: Cat Swarm Optimization

Loss Function: Cross-Entropy Loss

Batch Size: Configurable

Epochs: 100 (Can be adjusted for longer training)

Performance Metrics
Accuracy: Measures the percentage of correctly predicted labels.

Precision: Precision of the model in identifying the correct class.

Recall: The model's ability to find all instances of each class.

F1 Score: Harmonic mean of precision and recall.

Confusion Matrix: Visualization of model performance in classifying each class.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
The model is inspired by the ResNeXt architecture.

Special thanks to the PyTorch team for providing tools to build and train deep learning models.

