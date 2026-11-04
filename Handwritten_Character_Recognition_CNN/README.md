# Handwritten Character Recognition Using CNN

## Project Overview
This project uses Convolutional Neural Networks (CNNs) to recognize handwritten digits and letters from images. It was developed as part of the CodeAlpha Machine Learning Internship tasks.

## Objectives
- Recognize handwritten digits from 0 to 9.
- Recognize handwritten English letters from A to Z.
- Train CNN models using PyTorch.
- Evaluate model performance using accuracy and classification metrics.

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Datasets
### 1. MNIST
- 60,000 training images
- 10,000 testing images
- 10 digit classes (0–9)

### 2. EMNIST Letters
- 124,800 training images
- 20,800 testing images
- 26 letter classes (A–Z)

## Model Architecture
The CNN models use:
- Two convolutional layers
- ReLU activation functions
- Max-pooling layers
- Fully connected layers
- Cross-entropy loss
- Adam optimizer

The digit model has 10 output classes, while the letter model has 26 output classes.

## Results

| Dataset | Test Accuracy |
|---|---:|
| MNIST Digits | 98.91% |
| EMNIST Letters | 92.79% |

## Saved Models
- `models/handwritten_cnn_mnist.pth`
- `models/handwritten_letters_cnn.pth`

## Evaluation Results
- `results/letter_classification_report.txt`
- `results/letter_confusion_matrix.png`

## How to Run
1. Open the project folder in VS Code.
2. Activate your Python virtual environment.
3. Open `Handwritten_Character_Recognition_CNN.ipynb`.
4. Run the notebook cells in order to train and evaluate the models.

## Conclusion
The project demonstrates how CNNs can classify handwritten digits and letters using deep learning. The trained models achieved 98.91% accuracy on MNIST digits and 92.79% accuracy on EMNIST letters.

## Internship
Developed for the CodeAlpha Machine Learning Internship.
