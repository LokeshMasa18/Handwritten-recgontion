# ML Project



## Project Description
### 1. Data Pre-processing
We utilized the MNIST and EMNIST datasets, comprising over 400,000 handwritten words for character recognition. The data was divided into training (331,059), testing (41,382), and validation sets (41,382). The preprocessing involved flattening images into a 1D array and using Principal Component Analysis (PCA) for dimensionality reduction (64 components).

A sample images from the training and validation dataset:

<img src="Train/&/__0_1344062.png" alt="And character" width="300"/>

<img src="Train/0/_1_2.jpg" alt="zero character" width="300"/>

<img src="Train/C/20.jpg" alt="zero character" width="300"/>

A sample image from the testing dataset:

<img src="Test/Test_005.jpg" alt="testing dataset" width="300"/>


### 2. Models Used
Our project successfully identified handwriting in images, achieving a commendable accuracy
of approximately 93%. We conducted extensive experiments, exploring various models such as
Convolutional Neural Networks (CNN)-7 models used,Resnet -3 models used Support Vector Machines (SVM), K-Means
clustering, and Hidden Markov Models (HMMs) for character recognition.We have successfully implemented an ensemble approach using the three models that yielded the highest accuracy. This ensemble leverages the predictive power of the top-performing models to enhance the overall performance, resulting in a more robust and accurate system


