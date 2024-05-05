## 🤖 Handwritten Digits Classifier with PyTorch

This project focuses on building a neural network model to perform optical character recognition (OCR) on handwritten digits from the MNIST database. The primary objective is to achieve high accuracy on the test set.

### 🔑 Key Components:

- **Data Preprocessing**: The dataset will be loaded from `torchvision.datasets`, converted to tensors, normalized, and flattened using PyTorch methods. A `DataLoader` will be created for efficient data loading during training.

- **Data Visualization and Exploration**: Visualization of the dataset will be performed to understand the input format. Exploration of the data's size and shape will aid in preprocessing decisions. Any necessary preprocessing steps will be justified.

- **Neural Network Implementation**: A neural network will be built using PyTorch to predict the class of each input image. An optimizer will be defined to update the network's weights during training. The network will be trained using the training DataLoader.

- **Model Evaluation and Tuning**: The accuracy of the neural network on the test set will be evaluated. Model hyperparameters and architecture will be tuned to achieve high accuracy on the test set.

<<<<<<< HEAD
- **Improved Model**: Changes to hyperparameters or architecture will be made to improve model performance. The goal is to achieve 96% accuracy on the test set.
=======
- **Improved Model**: Changes to hyperparameters or architecture will be made to improve model performance. The goal is to achieve 100% accuracy on the test set.
>>>>>>> master

### 📁 Repository Structure:

- **requirements.txt**: Contains all required modules for the project.
- **README.md**: Provides an overview of the project, instructions, and steps involved.
- **notebook.ipynb**: Jupyter Notebook containing code implementation and explanations.

### 📊 Model Evaluation:

- **First Model Evaluation**:
  - Accuracy: 94.53%
- **Model after Hyperparameter Tuning**:
  - Accuracy: 96.62%

By following these components and steps, we aim to develop a robust neural network model for handwritten digit recognition, showcasing the effectiveness of deep learning in computer vision tasks. The project's progress will be documented in the notebook, facilitating reproducibility and experimentation.
