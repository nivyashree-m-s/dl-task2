# dl-task2

This project contains the implementation of three deep learning models as part of the Deep Learning course assignment. The project focuses on image classification, sequence learning, and image generation using different neural network architectures.

## Project description

The project is divided into three parts. Each part uses a different deep learning model and dataset to solve a specific problem.

Part A focuses on image classification using a convolutional neural network.
Part B focuses on sequence learning using recurrent neural networks.
Part C focuses on image generation using a generative adversarial network.

## Part A: CNN for image classification

In this part, a convolutional neural network was implemented using the CIFAR-10 dataset. The model includes convolution layers, activation functions, pooling layers, batch normalization, and dropout.

A transfer learning model using ResNet18 was also implemented and compared with the custom CNN.

Outputs generated:

* Training loss graph
* Accuracy values
* Confusion matrix
* Sample predictions

## Part B: RNN, LSTM, GRU

In this part, sequence models were implemented to understand how neural networks process sequential data. Three models were used: RNN, LSTM, and GRU.

These models were compared based on their performance and training behavior.

Outputs generated:

* Loss comparison graph
* Accuracy comparison
* Model behavior analysis

## Part C: GAN for image generation

In this part, a generative adversarial network was implemented using the Fashion-MNIST dataset.

The generator creates fake images from noise, and the discriminator tries to classify them as real or fake. Both models improve together during training.

Outputs generated:

* Generated images
* GAN loss graph
* Saved output images

## Technologies used

* Python
* PyTorch
* Torchvision
* Matplotlib
* Seaborn
* Google Colab

## Files in this repository

CNN_CIFAR10.ipynb
RNN_Text_classification.ipynb
GAN_FashionMNIST.ipynb
README.md
report.pdf

## How to run

1. Open the notebooks in Google Colab
2. Run all cells step by step
3. Train the models
4. View outputs and graphs


## Results summary

The CNN model achieved good accuracy on the CIFAR-10 dataset, and the transfer learning model performed better than the custom CNN.

The LSTM and GRU models performed better than the basic RNN because they can handle long-term dependencies in sequence data.

The GAN model was able to generate images that resemble the dataset, although some noise and instability were observed during training.


## Limitations

* Training was limited due to time constraints
* GAN output quality is not perfect
* Models can be improved with more tuning


## Conclusion

This project helped in understanding different deep learning models and their applications. It also provided practical experience in training models, analyzing results, and handling real datasets.

## Author

Name: Nivyashree
Course: Deep Learning
Semester: 6

---

## Note

This project is created for academic purposes only.
