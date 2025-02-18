This project focuses on applying these tasks to image classification problems using two popular datasets: 
  - Fashion-MNIST
  - Fruits-360.
    
PART 1:
  The goal is to apply feature extraction techniques to these image datasets and evaluate the performance of various machine learning classifiers.
  - The Fashion-MNIST dataset consists of 70,000 grayscale images, each 32x32 pixels, representing 10 different types of clothing items, such as t-shirts, pants, and boots. 
  - The Fruits-360 dataset contains around 55,000 RGB images, representing 80 different types of individual fruits. The objective for both datasets is to classify the images into the correct categories using machine learning algorithms.
  
  The primary tasks of this report are:
  - Feature Extraction: To identify and extract meaningful features from images using two methods: Histogram of Oriented Gradients (HOG) and Principal Component Analysis (PCA).
  - Model Classification: To train and evaluate several machine learning algorithms, including Logistic Regression, Support Vector Machines (SVM), Random Forest, and Gradient Boosted Trees, to perform the classification task.
  - Model Optimization: Hyperparameters of the models will be optimized using techniques like Grid Search and Cross-Validation to improve classification performance.
  This report will detail the methods and results of each of these steps, providing insights into the utility of the feature extraction methods and their impact on the classification results.

PART 2:
  - Purpose of the Report: To analyze and compare the performance of various neural network models on the Fashion-MNIST and Fruits-360 datasets.
  - Overview of Approaches: MLP on extracted features, MLP on raw images, convolutional network, and fine-tuning with ResNet-18
