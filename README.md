# Machine Learning Projects

This repository contains a collection of machine learning projects implemented from scratch or using popular frameworks like PyTorch. Each project demonstrates fundamental concepts and techniques in machine learning, focusing on both theoretical understanding and practical implementation.

## Projects

### 1. CNN on CIFAR-10 Dataset
**Location:** `CNN_CIFAR-10_Dataset/`  
**File:** `CNN.ipynb`  
**Description:** Implementation of a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset using PyTorch. The project includes data preprocessing, model architecture design, training loop, and evaluation metrics.  
**Key Features:**
- Custom CNN architecture with convolutional and pooling layers
- Data normalization and augmentation
- Training/validation/test splits
- Accuracy tracking during training

### 2. CNN on FashionMNIST Dataset
**Location:** `CNN_FashionMNIST_Dataset/`  
**File:** `CNN_FashionMNIST_Dataset.ipynb`  
**Description:** Convolutional Neural Network implementation for classifying fashion items from the FashionMNIST dataset. Demonstrates CNN application on grayscale image classification.  
**Key Features:**
- PyTorch-based CNN implementation
- Fashion item classification (10 classes)
- Data visualization and preprocessing

### 3. CNN from Scratch
**Location:** `CNN_from_Scratch/`  
**File:** `Report.ipynb`  
**Description:** Building Convolutional Neural Networks from the ground up, implementing core components manually to understand the underlying mathematics and algorithms.  
**Key Features:**
- Manual implementation of CNN layers
- Forward and backward propagation
- Understanding of convolutional operations

### 4. KNN Model from Scratch
**Location:** `KNN_Model_From_Scratch/Folder/`  
**Files:** `Code.pdf`, `Report.pdf`  
**Description:** Implementation of the K-Nearest Neighbors (KNN) algorithm from scratch without using machine learning libraries.  
**Key Features:**
- Distance calculations (Euclidean, Manhattan, etc.)
- Voting mechanisms for classification
- Hyperparameter tuning (k-value selection)

### 5. Linear Regression from Scratch
**Location:** `Linear_Regression_From_Scratch/`  
**File:** `Code.ipynb`  
**Description:** Complete implementation of linear regression algorithm from scratch, including gradient descent optimization.  
**Key Features:**
- Cost function implementation
- Gradient descent algorithm
- Feature scaling and normalization
- Model evaluation metrics

### 6. Logistic Regression & Perceptron from Scratch
**Location:** `Logistic_Regression_&_Perceptron_From_Scratch/`  
**Files:** `LR_and_Perc.ipynb`, `Report.docx`  
**Description:** Implementation of logistic regression and perceptron algorithms from scratch, covering binary classification problems.  
**Key Features:**
- Sigmoid activation function
- Binary cross-entropy loss
- Perceptron learning rule
- Convergence analysis

## Prerequisites

- Python 3.7+
- PyTorch (for CNN projects)
- NumPy
- Matplotlib
- Scikit-learn (for some projects)
- Jupyter Notebook

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Machine-Learning-Projects
```

2. Install required packages:
```bash
pip install torch torchvision numpy matplotlib scikit-learn jupyter
```

## Usage

Each project is contained in its own directory with a Jupyter notebook or PDF documentation. To run a project:

1. Navigate to the project directory
2. Open the notebook: `jupyter notebook <notebook-name>.ipynb`
3. Follow the instructions in the notebook

## Dataset Information

- **CIFAR-10:** 60,000 32x32 color images in 10 classes
- **FashionMNIST:** 70,000 28x28 grayscale images of fashion items in 10 classes
- **MNIST:** 70,000 28x28 grayscale images of handwritten digits (used in some projects)

Datasets will be automatically downloaded when running the respective notebooks.

## Learning Objectives

These projects demonstrate:
- Understanding of fundamental machine learning algorithms
- Implementation of models from mathematical foundations
- Data preprocessing and feature engineering
- Model training and evaluation
- Hyperparameter tuning
- Neural network architectures and training

## Contributing

Feel free to contribute improvements, bug fixes, or additional machine learning projects to this repository.

## License

This project is open source and available under the [MIT License](LICENSE).