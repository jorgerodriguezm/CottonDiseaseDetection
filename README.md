![](https://github.com/jorgerodriguezm/CottonDiseaseDetection/blob/main/Assets/banner.png)

## About this Repository

The goal of this repository is to use the Cotton Disease Dataset to build a deep learning model to process image data and detect if a leaf or cotton plant shows signs of disease.

### Custom Convolutional Neural Network Accuracy: 0.90

### Transfer Learning Model Accuracy: 0.94

### Published Kaggle Kernel:

- [Cotton Disease: Custom CNN & Transfer Learning](https://www.kaggle.com/jorgerodriguezm/cotton-disease-custom-cnn-transfer-learning)

### Model in this Repository:

- [Cotton Disease Detection](https://github.com/jorgerodriguezm/CottonDiseaseDetection/blob/main/Model/cotton-disease-custom-cnn-transfer-learning.ipynb)

### Cotton Disease Detection

Repository for the Cotton Disease Detection Kaggle Notebook.

### Problem

Given the huge areas used for cotton production, how could we best detect disease present in the plants with minimun human effort?

### Proposed Solution

First, we would create a custom Convolutional Neural Network (CNN) and see how much precision could we get from it. Later, we would take advantage of the VGG16 model through transfer learning to find out if the accuracy improves in a considerable way to decide wich model is the most appropiate for this task.

### Dependencies

- Visualization
  - Matplotlib
  - Seaborn
- Data Processing
  - Numpy
  - Pandas
  - Random
- Deep Learning
  - Tensorflow
  - Keras
