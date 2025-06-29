# IMAGE-CLASSIFICATION-MODEL

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : MURARI YAMINI
 
*INTERN ID* : CT04DF2780

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION* : This project shows how to create a Convolutional Neural Network (CNN) with TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. The model learns to identify digits 0-9 from grayscale 28x28 pixels images. CNNs are a robust form of neural network particularly well-suited for image classification problems because they have an innate ability to automatically and adaptively learn spatial hierarchies of features in a process called backpropagation.

This project includes:

- Data loading and preprocessing

- CNN architecture construction

- Model compilation and training

- Model evaluation

- Visualization of training and validation performance
  
### Tools and Technologies Used
| Tool/Technology    | Use case |
|-------------------|-------------|
| Python     | programming language used for implementation  |
|  Tensorflow    | library used to build and train CNN           |
|  Keras          | to download dataset and model building        |
|  Matplotlib     |  for plotting accuracy and loss graphs        |
|  VS code/jupyter | for running and experimenting code          |

### Dataset : 
The MNIST dataset contains 70,000 grayscale images:

- 60,000 for training

- 10,000 for testing
- each image is a 28x28 pixel square representing a single digit from 0 to 9

### Model Details
The architecture of CNN used in this task consists of the following layers:

1.Conv2D Layer(32 filters,3x3 kernel,ReLU activation) – Conscientious to learn simple edges and textures.

2.MaxPooling2D Layer – Used to reduce dimensionality and computation.

3.Conv2D Layer(64 filters,x3 kernel,ReLU activation) – Conscientious to learn complicated features and patterns. 

4.MaxPooling2D Layer – Further reduces the dimensionality.

5.Flatten Layer – Converts 2D feature maps to a 1D vector for fully connected layers.

6.Dense Layer (64 units,ReLU activation) – Hidden layer for learning non-linear combinations of features.

7.Dense Output Layer (10 units,Softmax activation) – Outputs probability distribution over 10 digit classes.


