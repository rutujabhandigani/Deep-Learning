# Deep-Learning

1. Implementation of a simple Neural Network for AND logic gate with Binary Input
   
    ●  AND Gate<br> 
       The output state of a digital logic AND gate only returns “LOW” again when ANY of its inputs are at a logic level “0”. 
       In other words for a logic AND gate, any LOW input will give a LOW output. Boolean Expression: A.B = Q. 
  
  
    ● Simple Neural Network (ANN) <br>
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

      Convolution Layer: <br>
      Convolution is the first layer to extract features from an input image. Convolution preserves the relationship between pixels by learning image features using small    squares of input data. It is a mathematical operation that takes two inputs such as image matrix and a filter or kernel. Convolution of an image with different filters can perform operations such as edge detection, blur and sharpen by applying filters.

      ReLU: <br>
      ReLU’s purpose is to introduce non-linearity in our ConvNet. Since, the real world data would want our ConvNet to learn would be non-negative linear values. Most of the data scientists use ReLU since performance wise ReLU is better.
      
      Pooling Layer: <br>
      Pooling layers section would reduce the number of parameters when the images are too large. Spatial pooling is also called subsampling or downsampling which reduces the dimensionality of each map but retains important information. Spatial pooling can be of different types: Max Pooling, Average Pooling and Sum Pooling.

      Fully Connected Layer: <br>
      The layer we call the FC layer, we flattened our matrix into a vector and fed it into a fully connected layer like a neural network.
      
      
     • Description about Image Dataset Used <br>
         1. The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. <br>
         2. It is a subset of a larger set available from NIST. <br>
         3. The digits have been size-normalized and centered in a fixed-size image. <br>
         4. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting. <br>

     • Operations to be performed: <br>
         1. Import the required Python libraries and dataset <br>
         2. Normalizing dataset (reshaping training and testing images) <br>
         3. Build the model: Identifying model requirement (number of convolution layers pooling layers, fully connected layers, size of filters/kernel used, activation function used) <br>
         4. Compile the model: Optimize the model to adjust the weights to minimize the losses (which optimizer to be used) Identifying optimizer and loss function. <br>
         5. Train the model with Image dataset <br>
         6. Predict/Test the model <br>
         7. Model performance visualization in terms of accuracy and loss <br>
          
 
 3. Implementation of a prediction model for time series data using pre-trained architecture <br>
      Different deep learning pre-trained Architectures available:
      1. squeezenet<br>
      2. googlenet<br>
      3. inceptionv3<br>
      4. densenet201<br>
      5. mobilenetv2<br>
      6. resnet18<br>
      7. resnet50<br>
      8. resnet101<br>
      9. xception<br>
      10. inceptionresnetv2<br>
      11. shufflenet<br>
      12. nasnetmobile<br>
      13. nasnetlarge<br>
      14. darknet19<br>
      15. darknet53<br>
      16. efficientnetb0<br>
      17. alexnet<br>
      18. vgg16<br>
      19. vgg19<br>

   • Pretrained architecture used: <br>
        Long Short-Term Memory: <br>
        LSTM is one of the most widely used recurrent structures in sequence modeling. It uses gates to control information flow in the recurrent computations.LSTM networks are         very good at holding long term memories. The memory may or may not be retained by the network depending on the data. Preserving the long term dependencies in the network         is done by its Gating mechanisms. The network can store or release memory on the go through the gating mechanism. <br>
        
   • Time Series Data: <br>
         Shampoo Sales Dataset <br>
         This dataset describes the monthly number of sales of shampoo over a 3-year period. The units are a sales count and there are 36 observations.
         The original dataset is credited to Makridakis, Wheelwright, and Hyndman(1998). <br>
         
   • Operations to be performed:<br>
      1. Import the required Python libraries and dataset. <br>
      2. Normalizing dataset.<br>
      3. Identifying the pretrained model to be used.<br>
      4. As per the need, fine tune the pretrained architecture.<br>
      5. Train the model with a training dataset.<br>
      6. Predict the model with a testing dataset.<br>
      7. Model performance visualization in terms of accuracy and loss.<br>
    
