# MNST-Image_Classification

#Google colab link: https://colab.research.google.com/drive/1TPLCwSPuu3X8dGksxDsdO_M0I_q587tq?usp=sharing

#1. What is the Fashion MNIST dataset? ANSWER: It is a large-scale dataset commonly used to train and evaluate image classification models, offering a more realistic and challenging alternative to the MNIST handwritten digits dataset.

#2. Why do we normalize image pixel values before training? ANSWER: We normalize image pixel values before training to keep all inputs on a similar scale, which helps the model learn faster, train more stably, and converge better. It will also prevents large pixel values from dominating the learning process and improves overall performance.

#3. List the layers used in the neural network and their functions. ANSWER: Input Layer – Receives the image pixel values as input to the network.
Flatten Layer – Converts the 2D image (28×28) into a 1D vector so it can be processed by dense layers.
Dense (Hidden) Layer(s) – Performs feature learning by applying weights, biases, and activation functions (e.g., ReLU).
Output Layer – Produces the final predictions, usually using Softmax to give class probabilities for each category.

#4. What does an epoch mean in model training? ANSWER: It means one complete pass of the entire training dataset through the model during training, allowing the model to update its weights based on all training samples once.

#5. Compare the predicted label and actual label for the first test image. ANSWER: The actual label is the true class assigned to the first test image in the dataset, while the predicted label is the class the trained model outputs for that image.

#6. What could be done to improve the model's accuracy? ANSWER: It can be improved by using a better network (like a CNN), training for more epochs, and tuning model parameters such as learning rate and number of layers.

