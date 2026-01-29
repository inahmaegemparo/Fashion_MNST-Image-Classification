# Gemparo-Inah-Mae_LW1-Image-Classification

Questions: (February 8, 2026)
1. What is the Fashion MNIST dataset?
  Fashion MNIST is a dataset of 70,000 grayscale images of clothing items such as shirts, shoes, and bags.
  It is commonly used for training and testing machine learning models.

2. Why do we normalize image pixel values before training?
  Image pixel values are normalized to scale them between 0 and 1. This helps the model train faster and more efficiently.
  It also improves numerical stability during learning.

3. List the layers used in the neural network and their functions.
  The Flatten layer converts the 2D image into a 1D array. The Dense layer with 128 neurons and ReLU activation learns important features from the data.
  The final Dense layer outputs 10 values corresponding to the clothing classes.

4. What does an epoch mean in model training?
  An epoch means one complete pass of the entire training dataset through the neural network.
  During each epoch, the model updates its weights based on errors. More epochs generally help the model learn better, up to a point.

5. Compare the predicted label and actual label for the first test image.
   For the first test image, the actual label is the same as the predicted label, therefor the model successfully classified the image. 

6. What could be done to improve the model’s accuracy?
  Accuracy can be improved by adding more hidden layers or neurons. Increasing the number of training epochs can also help.
