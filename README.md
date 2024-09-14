# car-color-detection
In this project, I developed a car color detection model using a deep learning approach, specifically by training a custom Convolutional Neural Network (CNN). The goal was to classify car images into one of four color categories: red, black, white, and blue. The model achieves an accuracy of 95%.

## Dataset:
The dataset consists of images of cars, each labeled with one of the four colors: red, black, white, or blue. Preprocessing steps were applied to ensure consistency in image size and quality. This included resizing the images to a uniform size, normalizing pixel values, and applying data augmentation techniques such as flipping and rotation to improve the model's robustness.

## Model Architecture:
The custom CNN architecture is designed to extract spatial features from the input images. The architecture consists of multiple layers:

Convolutional layers to detect features like edges, textures, and color patterns.
ReLU activation functions to introduce non-linearity.
Max pooling layers to down-sample the feature maps and reduce dimensionality.
Fully connected layers that act as the classifier, making predictions based on the extracted features.
Softmax output layer to provide probability distributions over the four color classes.
Training Process:
The model was trained using a categorical cross-entropy loss function, and the Adam optimizer was employed to efficiently adjust the weights during training. Various hyperparameters, such as learning rate, batch size, and number of epochs, were tuned to ensure optimal performance. Data augmentation helped enhance the model's generalization ability.

## Results:
After training, the model achieved a 95% accuracy in predicting car colors. This high accuracy demonstrates the effectiveness of the CNN in recognizing different colors based on the visual features in the images.

This model can be further enhanced by expanding the dataset to include more color categories and improving the generalization to different environments or lighting conditions.
