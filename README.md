1. What is the Fashion MNIST dataset?

   
Answer: Fashion MNIST is a dataset of 70,000 grayscale images of clothing items such as shirts, shoes, and bags.
        Each image is 28×28 pixels and belongs to one of 10 classes, commonly used for training and testing image classification models.

2. Why do we normalize image pixel values before training?

Answer: So the model trains faster, more stably, and more accurately.


3. List the layers used in the neural network and their functions.

Answer: 1. layers.Flatten(input_shape=(28, 28))
        2. layers.Dense(64, activation='relu')
        3. layers.Dense(10)

4. What does an epoch mean in model training?

Answer: One complete pass of the entire training dataset through the neural network.


5. Compare the predicted label and actual label for the first test image.

Answer: The predicted label for the first test image is obtained using np.argmax(predictions[0]), while the actual label is test_labels[0].
If both values are the same, the model correctly classified the first test image; if they differ, the image was misclassified.


6. What could be done to improve the model’s accuracy?

Answer:  Model accuracy can be improved by using a more complex architecture such as CNNs, tuning hyperparameters, adding regularization,
and training the model for more epochs with well-preprocessed data.


[Link of Google Collab for image Classification: ]( https://colab.research.google.com/drive/1UX8nKmt6ty7ni_dlURSy46Wd-XIPPokC?usp=sharing)
