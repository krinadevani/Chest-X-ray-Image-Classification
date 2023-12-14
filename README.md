# Chest X-ray Image Classification 

## Description

This project aims to leverage deep learning techniques to automate the process of detecting pneumonia from chest X-ray images. To address this challenge, we employ advanced deep-learning techniques. Specifically, our focus is on utilizing Convolutional Neural Networks (CNNs) for their prowess in image recognition tasks. CNNs play a pivotal role in automating the detection of pneumonia from chest X-ray images. This approach provides a scalable and efficient solution, significantly enhancing diagnostic capabilities and contributing to timely medical interventions.

## Dataset

[Chest X-Ray Images (Pneumonia) Dataset (Kaggle)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

**Statistics of the dataset:**
- The dataset contains a total of 5,863 X-ray images.
- The distribution of the data is as follows:
    - Normal: 1341 images
    - Pneumonia: 3875 images
      
**Splitting of the dataset into training and testing sets:**
- The dataset is split into training and testing sets. The testing data comprises 10% of the total images.
  - Number of train samples 5216.
  - Number of test samples 624.
 

## Models used

- **CNN** : CNNs are a type of deep learning model that are highly effective for image classification tasks. They consist of an input layer, an output layer, and multiple hidden layers. The hidden layers of a CNN can number in the hundreds, compared to just one or two in a standard neural network.
- **VGG16** :  VGG16 is a convolutional neural network model with 16 layers, including 13 convolutional layers and 3 fully connected layers. It uses 3x3 filters in the convolutional layers and a max-pool of 2x2 size in the pooling layers.
- **VGG19** : VGG19 is a variant of the VGG model with 19 layers, including 16 convolutional layers, 3 fully connected layers, and 1 SoftMax layer. It’s an extension of VGG16 with more layers, allowing it to learn more complex features.
- **ResNet50**: ResNet50 is a convolutional neural network architecture. It is specifically designed to address the vanishing gradient problem in deep networks by introducing skip connections or residual connections. ResNet50 has 50 layers, and it includes shortcut connections that skip one or more layers, allowing the model to learn residual functions. This architecture has been widely used and has demonstrated great performance in various computer vision tasks, including image classification.

## Rationale
These models were chosen based on their proven effectiveness in image classification tasks, particularly in the medical field. VGG16 and VGG19 are known for their performance in many computer vision applications, while CNNs offer the flexibility to learn complex features from images.


## Result

- **Performance of VGG16 :**
  - The VGG16 model achieved an accuracy of 90%.
  - It had a precision of 93% for Pneumonia and 89% for Normal cases.
  - The recall was 79% for Pneumonia and 97% for Normal cases.
  - The F1-score was 86% for Pneumonia and 93% for Normal cases.

- **Performance of VGG19 :**
  - The VGG19 model achieved an accuracy of 91%.
  - It had a precision of 95% for Pneumonia and 90% for Normal cases.
  - The recall was 81% for Pneumonia and 97% for Normal cases.
  - The F1-score was 87% for Pneumonia and 93% for Normal cases.

- **Performance of CNN :**
  - The CNN model achieved an accuracy of 91%.
  - It had a precision of 87% for Pneumonia and 93% for Normal.
  - The recall was 89% for Pneumonia and 92% for Normal.
  - The F1-score was 88% for Pneumonia and 93% for Normal.

- **Performance of ResNet50 :**
    - The ResNet50 model achieved an accuracy of 87%.
    - It had a precision of 100% for Pneumonia and 67% for Normal.
    - The recall was 20% for Pneumonia and 100% for Normal.
    - The F1-score was 81% for Pneumonia and 33% for Normal.

All three models performed well with over 90% accuracy. The VGG19 model had the highest accuracy and precision, while the CNN model had the highest recall. The choice of model would depend on the specific requirements of the task, such as whether precision or recall is more important.


## How to use

- Download the dataset from the provided link.
- Download all 4 notebook files in the same folder.
- Now, our files are ready to use.


## Contributors

Deep Prajapati
Krina Devani
Shubham Mendapara
