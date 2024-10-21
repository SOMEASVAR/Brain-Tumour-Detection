# Brain-Tumour-Detection:
# Brain Tumour Detection

Brain tumor detection is a crucial aspect of medical diagnosis and treatment planning. 
The human brain is a complex organ, and the presence of a tumor can have significant implications for an individual's health. 
Early detection plays a key role in improving the chances of successful treatment and better outcomes.

## Features

### Image Preprocessing:

Normalization: Ensures consistent pixel values for improved model performance.
Resizing: Standardizes image dimensions for compatibility with the detection model.
Augmentation: Enhances the dataset by applying transformations like rotations or flips.

### Convolutional Neural Network (CNN):

Utilizes convolutional layers to automatically learn hierarchical features from input images.
Employs pooling layers for downsampling and reducing spatial dimensions.
Utilizes fully connected layers for making predictions based on learned features.

### Transfer Learning:

Leverages pre-trained CNN models (e.g., ResNet, VGG) for feature extraction.
Fine-tunes the model on a brain tumor detection-specific dataset.

### Data Splitting:

Segregates the dataset into training, validation, and test sets for model development and evaluation.

### Loss Function and Optimization:

Employs appropriate loss functions (e.g., binary cross-entropy) to measure model performance.
Optimizes model parameters using optimization algorithms (e.g., SGD, Adam).

### Metrics for Evaluation:

Utilizes metrics such as accuracy, precision, recall, F1-score, and ROC-AUC for model evaluation.

### Post-Processing Techniques:

Applies post-processing methods to refine model predictions, such as thresholding or morphological operations.

## Requirements

- Python 3.x
- Required Python packages: numoy,pandas,os,opendatasets,torchvision,transforms,datasets,torch

## Architecture Diagram/Flow

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/95655b3b-4cc0-4b7b-919c-e89c27f2c0c6)


## Usage

1. Open a Python file.

2. Import the necessary packages.

3. Load the dataset.

4. Split the dataset into training and testing images.

5. Create a neural classififcation function to classify the images.

6. Create an evaluation function that corresponds with the neural network classification function.

7. Compile and fit the neural model with appropriate optimizer,loss functions and also the epochs,batch_sizes etc respectively.

8. Prepare the loop for loading the testing images.


## Output:

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/a101f1f6-b042-4b62-aecd-17ce50e99aa2)

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/8d518eb7-238f-4f01-b5c8-e22077614ce6)

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/e6270987-8725-4585-a620-39e46499a4c7)

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/7c4db580-b650-4516-ad91-6d645b728fd7)

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/bee42948-7e75-4b52-8471-02a0637b311a)

![image](https://github.com/SaiDarshan2003/Mini-Project/assets/94692595/1ed0cbd7-1d6a-4e57-8a86-634cff42df34)


## Result:

In conclusion, the brain tumor detection program using CNN and torchvision demonstrates the potential for accurate and efficient automated diagnosis from MRI scans.
This approach can significantly improve early detection, reduce human error, and streamline the diagnostic process. It represents a promising tool in the field of medical imaging, 
with potential for enhancing patient outcomes and healthcare efficiency.However, it's essential to address ethical considerations, regulatory compliance, and the need for continuous
model improvement for real-world deployment.

