# DSC 650 ConvNets Model with CIFAR-10 dataset
# Abstract
Using Convolutional Neural Networks (ConvNets/CNNs) for this project. These are neural networks that are suited for a variety of image recognition tasks including image classification and object detection. Build a ConvNet from labeled image data to perform multiple category image classification with CIFAR-10 dataset. Understand how to use existing models to classify images. Describe how to fine-tune existing models for specific classification tasks. Below are the guidelines for this project:

A. Using section 5.2 in Deep Learning with Python as a guide, create a ConvNet model that classifies images CIFAR10 small images classification dataset(https://keras.io/api/datasets/cifar10/). Do not use dropout or data-augmentation in this part. Save the model, predictions, metrics, and validation plots.

B. Using section 5.2 in Deep Learning with Python as a guide, create a ConvNet model that classifies images CIFAR10 small images classification dataset(https://keras.io/api/datasets/cifar10/). This time includes dropout and data-augmentation. Save the model, predictions, metrics, and validation plots.

# Preveiw

![Preview of the training and validation loss plot.](https://github.com/micgonzalez/DSC650_Summer_2020_ConvNets_model_with_CIFAR-10_dataset/blob/master/GonzalezMichael_assignment_6_2_A_cifar10_loss_val_plot.png)

This is a training and validation loss plot from this project.


![Preview of the training and validation accuracy plot.](https://github.com/micgonzalez/DSC650_Summer_2020_ConvNets_model_with_CIFAR-10_dataset/blob/master/GonzalezMichael_assignment_6_2_A_cifar10_accuracy_val_plot.png)

This is a training and validation accuracy plot from this project.


You can find the models used for this project in the repository.


# Findings
The models for both A and B were saved in the HDF format. The validation plots will display the accuracy & loss for each ConvNet models based on their training and validataion. 

# Challenges
The main challenge for this project was in correctly plotting the accuracy and loss data points. Another challenge was to have the ConvNet model identify the testing images correctly.

# Conclusion
This was a great project to learn about the ConvNet models that are able to identify images of different items and objects. I learned that validation plots give you a quick way to see if the model working correctly. I also learned that you can save a model for further experimentation.
