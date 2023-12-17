# Wear Particle Image Classification with Convolutional Neural Networks

This repository contains the code for a research project on the classification of ferrography images, or wear particle images. This task is crucial in the field of predictive maintenance of mechanical systems (Tribosystems).

In this study, we compared the performance of several popular convolutional neural network (CNN) architectures for wear particle image classification. The architectures we considered include:

1. VGG
2. ResNet
3. InceptionV3
4. DenseNet
5. Xception
6. MobileNet
7. MobileNetV2
8. EfficientNet
9. ConvNext-T

We used a small dataset consisting of 5 classes of wear particles for fine-tuning and performance evaluation of these CNN architectures. We evaluated the performance of each architecture using validation accuracy, F-score, and computational efficiency.

Our results indicated that certain CNN architectures are better suited for ferrography image classification than others. In particular, we found that the EfficientNet and DenseNet architectures outperformed the other architectures considered in this study with validation accuracy of 99.43% and 98.86% respectively.

In conclusion, our study provides valuable insights into the suitability of different CNN architectures for wear particle classification and highlights the potential of the EfficientNet and DenseNet architectures in this domain.

# Tools Used

This project uses the following tools:

- [Keras](https://keras.io/): A high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation.

- [Weights & Biases (wandb)](https://wandb.ai/site): A tool for tracking and visualizing machine learning experiments. It logs your hyperparameters and output metrics from your runs, then organizes them into a visual and shareable dashboard.

# Publication Details

- Jaybhaye, Sangita M., Vedmani A. Vaidya, Maheshwar D. Jaybhaye, and Sandeep R. Shinde. "A Resemblance of Convolutional Neural Network Architectures for Classifying Ferrograph Images." In Applied Computer Vision and Soft Computing with Interpretable AI, pp. 119-134. Chapman and Hall/CRC, 2024.

# Draft of the paper:
[**A Comparative Study of Convolutional Neural Network Architectures for Ferrograph Image Classification**](A_Comparative_Study_of_Convolutional_Neural_Network_Architectures_for_Ferrograph_Image_Classification.pdf)