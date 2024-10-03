# Military-Vehicle-Recognition
This project aims to develop a classification model for distinguishing between normal and military vehicles using image datasets. The project utilizes the TensorFlow and Keras libraries to build and train a convolutional neural network (CNN) model. The dataset includes images of both normal and military vehicles, which are processed and augmented using ImageDataGenerator. The model is built using the MobileNetV2 architecture, fine-tuned for this specific task.

# Key components of the project:
- Dataset Loading and Preprocessing: Images are loaded from a directory, split into training and testing sets, and augmented for better model performance.
- Model Architecture: MobileNetV2, a pre-trained model, is used as the base, with additional layers added for classification.
- Model Training and Evaluation: The model is trained using early stopping and checkpoints, and its performance is evaluated using confusion matrices.
- Metrics: The model's accuracy is assessed with classification reports and confusion matrices, visualized using Matplotlib.
