# MNIST Dataset Handwirriten Digit Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using PyTorch.

## Introduction

The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. This project uses a CNN to classify the digits with high accuracy.

## Installation

To run this project, you need to have Python and the following libraries installed:

- PyTorch
- torchvision
- numpy
- matplotlib
- tqdm
- scikit-learn

You can install the required libraries using the following command:

```bash
pip install torch torchvision numpy matplotlib tqdm scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/mnist-cnn.git
cd mnist-cnn
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook "MNIST Dataset CNN.ipynb"
```

3. Run the notebook cells to train and evaluate the model.

## Model Architecture

The CNN model used in this project consists of the following layers:

- Convolutional layers with ReLU activation
- MaxPooling layers
- Fully connected layers

## Results

The model achieves a high accuracy on the MNIST test set. Detailed performance metrics and confusion matrix can be found in the notebook.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
