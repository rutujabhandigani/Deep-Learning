# Deep-Learning

1. Implementation of a simple Neural Network for AND logic gate with Binary Input
   
    ●  AND Gate 
       The output state of a digital logic AND gate only returns “LOW” again when ANY of its inputs are at a logic level “0”. 
       In other words for a logic AND gate, any LOW input will give a LOW output. Boolean Expression: A.B = Q. 
  
  
    ● Simple Neural Network (ANN) 
      A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain       operates.    
      An artificial neural network (ANN) is the piece of a computing system designed to simulate the way the human brain analyzes and processes information. 
   
    ● Activation Functions:
    ![image](https://user-images.githubusercontent.com/55191928/146051765-1d2d5559-5da3-4e10-98ac-88880e07df6c.png)

  
  
    Operations to be performed: 
      1) Import the required Python libraries 
      2) Define Activation Function: Sigmoid Function 
      3) Initialize neural network parameters (weights, bias) and define model hyperparameters (number of iterations, learning rate) 
      4) Perform Forward Propagation 
      5) Perform Backward Propagation 
      6) Update weight and bias parameters 
      7) Train the learning model 
      8) Plot Loss value vs Epoch 
      9) Test the model performance


2. Implementation of a Convolution Neural Network (CNN) for image dataset

    ● Architecture of Convolutional Neural Network
    ![image](https://user-images.githubusercontent.com/55191928/146385214-c1af78b8-42ee-43a5-a25b-642feb03d784.png)

      Convolution Layer:
      Convolution is the first layer to extract features from an input image. Convolution preserves the relationship between pixels by learning image features using small    squares of input data. It is a mathematical operation that takes two inputs such as image matrix and a filter or kernel. Convolution of an image with different filters can perform operations such as edge detection, blur and sharpen by applying filters.

      ReLU:
      ReLU’s purpose is to introduce non-linearity in our ConvNet. Since, the real world data would want our ConvNet to learn would be non-negative linear values. Most of the data scientists use ReLU since performance wise ReLU is better.
      
      Pooling Layer:
      Pooling layers section would reduce the number of parameters when the images are too large. Spatial pooling is also called subsampling or downsampling which reduces the dimensionality of each map but retains important information. Spatial pooling can be of different types: Max Pooling, Average Pooling and Sum Pooling.

      Fully Connected Layer:
      The layer we call the FC layer, we flattened our matrix into a vector and fed it into a fully connected layer like a neural network.
      
      
     • Description about Image Dataset Used
         1. The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples.
         2. It is a subset of a larger set available from NIST.
         3. The digits have been size-normalized and centered in a fixed-size image.
         4. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

     • Operations to be performed:
         1. Import the required Python libraries and dataset
         2. Normalizing dataset (reshaping training and testing images)
         3. Build the model: Identifying model requirement (number of convolution layers pooling layers, fully connected layers, size of filters/kernel used, activation function used)
         4. Compile the model: Optimize the model to adjust the weights to minimize the losses (which optimizer to be used) Identifying optimizer and loss function.
         5. Train the model with Image dataset
    
