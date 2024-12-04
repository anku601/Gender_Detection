# Gender Detection by Face Using CNN-Based Model
# Gender-Detection-by-Face
 Dataset Link - https://www.kaggle.com/datasets/rashikrahmanpritom/gender-recognition-dataset/data

## Features  
- **Real-time Gender Detection**: Leverages OpenCV and a pre-trained CNN model to detect and classify gender through webcam video.  
- **Custom CNN Architecture**: Optimized architecture with convolutional layers, batch normalization, and dropout for efficient feature extraction and classification.  
- **Data Augmentation**: Improves model generalization using transformations such as rotation, flipping, and zooming.  
- **Performance Metrics**: Includes ROC Curve, Confusion Matrix, and accuracy/loss plots for model evaluation.  

---

## Table of Contents  
1. [Installation](#installation)  
2. [Dataset](#dataset)  
3. [Model Architecture](#model-architecture)  
4. [Usage](#usage)  
5. [Results](#results)  
6. [Technologies Used](#technologies-used)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/gender-detection-cnn.git
   cd gender-detection-cnn


## Model Architecture
The CNN architecture is optimized for gender classification and consists of:

Convolutional Layers: Extract spatial features from the images.

Batch Normalization: Speeds up convergence and stabilizes training.

MaxPooling Layers: Reduces spatial dimensions for computational efficiency.

Dropout Layers: Prevents overfitting by randomly dropping neurons during training.

Dense Layers: Fully connected layers for classification.


## Compilation Details:
Optimizer: Adam
Loss Function: Binary Crossentropy
Metrics: Accuracy

