# Lenet-5HandwrittenDigitsClassification

*Problem Statement*: Classifying handwritten digits into their respective digital labels

*Architecture used*: Lenet-5

*ABOUT LENET-5*
LENET-5 is a Convolutional Neural network architecture. It consists of several convolutional and pooling layers, followed by fully connected layers. The convolutional layers are responsible for learning features from the input image, while the pooling layers reduce the spatial dimensions of the feature maps. The fully connected layers are used for classification.

![image](https://github.com/Jyoti200/Lenet-5HandwrittenDigitsClassification/assets/86410759/ab55518f-d06e-4652-9010-ef5dd99bd53e)


The LeNet architecture consists of the following layers:

Input layer
Convolutional layers
Pooling layers
Fully connected layer
Output layer

1. Input Layer: The input shape is (28, 28, 1), which corresponds to grayscale images of size 28x28 pixels.

2. C1 - Convolutional Layer1: This layer has 6 filters with a kernel size of 5x5 and a hyperbolic tangent (tanh) activation function.

3. Pooling Layer 1 - Average: This layer performs average pooling with a pool size of 2x2 and a stride of 2x2.

4. C2 - Convolutional Layer: This layer has 16 filters with a kernel size of 5x5 and a tanh activation function.

5. Pooling Layer 2 - Average: Another average pooling layer with a pool size of 2x2 and a stride of 2x2.

6. Flatten Layer: This layer flattens the output from the previous layers into a 1D vector to be fed into the fully connected layers.

7. Fully Connected Layers:
   - Hidden Layer 1: Dense layer with 120 neurons and a tanh activation function.
   - Hidden Layer 2: Dense layer with 84 neurons and a tanh activation function.
   - Output Layer: Dense layer with 10 neurons (for 10 classes) and a softmax activation function.

*RESULT* 
Validation Accuracy: 98.50
Validation Loss: 0.0481
