
### Handwritten-Digit-Classification-using-ANN

____

The model employs an Artificial Neural Network (ANN) to recognize and classify handwritten digits ranging from 0 to 9. The MNIST dataset, which contains 60,000 training images and 10,000 testing images of handwritten digits, is used for training and evaluating the model.
Key features of the model are as follows:

1. **Input Data**:
   - **Dataset**: MNIST, which includes grayscale images of handwritten digits, each of size 28x28 pixels.
   - **Preprocessing**: Images are normalized to ensure pixel values range between 0 and 1. This is achieved by dividing the pixel values by 255.

2. **Model Architecture**:
   - **Input Layer**: Accepts flattened 28x28 pixel images (i.e., a vector of 784 elements).
   - **Hidden Layers**: One or more dense (fully connected) layers with activation function ReLU to introduce non-linearity and learn complex patterns in the data.
   - **Output Layer**: A dense layer with 10 neurons (one for each digit) and a softmax activation function to produce probability distributions over the 10 classes.

3. **Training**:
   - **Loss Function**: Categorical cross-entropy, suitable for multi-class classification tasks.
   - **Optimizer**: An optimization algorithm Adam to update the model weights during training.
   - **Metrics**: Accuracy is used to evaluate the model's performance during training and testing.

4. **Evaluation**:
  
   The trained model is evaluated on the test set to determine its accuracy in recognizing and classifying handwritten digits.
