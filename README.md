Description 
## Part I: Data Preparation

Data Description:
The Leaf Classification dataset contains images of various types of leaves.
Data Cleaning:
Identify and address any inconsistencies or anomalies in the dataset.
Handling Missing Values and Duplicates:
Check for missing values and duplicates in the dataset and apply appropriate correction methods.
Data Visualization:
Utilize proper visualization methods to gain insights into the dataset.
Image Display:
Display some sample images from the dataset.
Correlation Analysis:
Perform correlation analysis to understand the relationships between different features.

## Part II: Training a Neural Network

Data Splitting:

Divide the dataset into training and test sets, allocating approximately 80% for training.
Data Standardization:

Determine if standardization is necessary by computing the mean and standard deviation for each feature dimension using only the training set.
Label Encoding:

Encode the labels for classification tasks.
Model Implementation:

Design and implement a CNN model for leaf classification.
Training Function:

Develop a training function to train the CNN model and explore various hyperparameter settings:
Batch size
Number of layers
Dropout rate
Optimizer (e.g., SGD, Adam, RMSProp)
Regularization (weight decay)
Learning rate and learning rate scheduler
Evaluation Function:

Write an evaluation function to assess the performance of the trained model on both the train and test sets.
