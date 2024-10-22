**Fish Species Classification Project**

This project aims to build an Artificial Neural Network (ANN) model to classify fish species using image data. Below is a detailed explanation of the project steps and the techniques used.

**Kaggle Code Link :** https://www.kaggle.com/code/ozlemkaykc/akbankdeeplearning-ann

**Dataset Link : ** https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

**Project Steps**

**1. Importing Libraries**

The following libraries were utilized in the project:

numpy, pandas (Data processing)
matplotlib (Visualization)
tensorflow, keras (Deep learning model creation and training)
sklearn (Model evaluation)

**2. Data Preparation**

Data Loading and Preprocessing: The fish dataset was obtained from Kaggle, and the ImageDataGenerator was used for loading the data. Images were resized and normalized (pixel values between 0-1). Data augmentation, such as rotation and flipping, was applied to increase the diversity of the dataset.
Data Splitting: The dataset was split into 80% training and 20% validation.


**4. Building the Artificial Neural Network (ANN) Model**

Model Structure: The model is built using a Sequential structure, including fully connected layers (Dense), batch normalization, and dropout layers.
Output Layer: The final layer is designed based on the number of fish species, using the softmax activation function.

**6. Model Training**

Callback Functions: EarlyStopping, ModelCheckpoint, and ReduceLROnPlateau callbacks were used to optimize the training process. These callbacks help to prevent overfitting and save the best-performing model during validation.
Optimization: The model was optimized during training, and accuracy and loss were monitored throughout the process.

**8. Evaluating Model Performance**

Accuracy and Loss Graphs: Accuracy and loss values for both the training and validation sets were visualized and analyzed.
Classification Performance: The performance of the model was evaluated using a confusion matrix and classification report, measuring metrics such as precision, recall, and F1-score.

**10. Visualization and Interpretation of Results**

Graphical Analysis: Accuracy and loss values obtained during the training process were visualized using graphs.
Classification Success: The classification results for fish species were analyzed with a confusion matrix and other evaluation metrics.

**Project Goal**

The goal of this project is to develop an artificial neural network model capable of accurately classifying fish species from images. The use of data augmentation and optimization techniques improved the model's generalization ability. Additionally, the model's success was thoroughly evaluated using multiple metrics such as precision, recall, and F1-score.

