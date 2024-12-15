# Self-Driving Cars using Convolutional Neural Network

<img src="https://github.com/user-attachments/assets/c80a0035-2c54-4ade-9d75-85e6f26b15b0" alt="Descriptive Image Text" width="600" height="600">


## Introduction
This project develops an end-to-end deep learning model using Convolutional Neural Networks (CNNs) to enable autonomous driving. The model, referred to as the DAVE-2 System, learns to mimic human driving behavior by mapping raw pixel data from front-facing cameras to steering commands. This approach allows the vehicle to navigate diverse environments, from well-marked highways to less structured settings like parking lots and unpaved roads.

## Features
- **End-to-End Learning**: The system learns the entire processing pipeline needed to steer a car directly from the human steering angle without the need for explicit intermediate tasks such as lane detection.
- **Data Augmentation**: Implements various augmentation techniques to enhance the robustness and accuracy of the model under different environmental conditions.
- **Autonomous Navigation**: Capable of driving autonomously on both seen and unseen tracks in a simulated environment, adjusting the steering angle in real-time.

## Technology Stack
- **Languages**: Jupyter notebook,python
- **Libraries**: TensorFlow, Keras, NumPy, OpenCV

The study demonstrates that CNNs can effectively learn complex driving tasks like lane and road following without manual decomposition into subtasks, relying on minimal training data. It highlights the need for further improvement in network robustness and better methods for verification and visualization of internal processes. This progress sets the stage for more reliable and scalable autonomous driving technologies.
