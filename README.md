# Dog breeds classification with Transfer Learning


![img](https://user-images.githubusercontent.com/85156782/202886939-a8e47b1a-3602-4ead-b9e2-f76c4b3fc5b2.jpg)
![im (1)](https://user-images.githubusercontent.com/85156782/202887001-3a5bdb24-9a13-47d7-8517-12dbc2401f24.jpg)

# Problem statement
Given a simple, yet beautiful, dog picture, can a model guess his breed?

# Results
Managed to obtain a 90.8% accuracy training the model on the full dataset.

# About the data
The original set comes from Kaggle dog breed identification competition. It consists of a collection of 10,000+ labelled images of 120 different dog breeds (that means we'll be dealing with unstructured data).

This kind of problem is called 'multi-class' image classification. It's multi-class because we're trying to classify multiple different breeds of dog.

# Workflow
1. Prepare the data (preprocessing, the 3 sets, X & y)
2. Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping).
3. Evaluating a model (making predictions, comparing them with the ground truth labels).
4. Improve the model through experimentation (starting with a sample of images and slowly increase the number)
5. Save our model

# Also had a bit of fun with custom predictions 
![image](https://user-images.githubusercontent.com/85156782/202887254-725e652a-55ce-4fe4-aa7c-0d2a0c099588.png)
