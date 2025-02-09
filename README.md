# CIFAR-100 Image Classification

## Overview
This repository contains a Jupyter Notebook that trains and evaluates two different models for CIFAR-100 classification:

1. **Pretrained ResNet Model**
2. **Self-Made Custom Model**

Each model has separate training, testing, and evaluation functions, allowing users to compare performance.

## How to Use
Follow these steps to run the models in the Jupyter Notebook:

### 1. Setup
Ensure you have the required libraries installed. You can install them using:
```bash
pip install torch torchvision matplotlib numpy tqdm
```

### 2. Running the Models
Open the notebook and decide which model you want to run:
- **For Pretrained ResNet Model**, run all cells in the `ResNetBlock` section.
- **For Self-Made Custom Model**, run all cells in the `SelfModel` section.

### 3. Training
- Both models have separate training loops.
- The loss and accuracy for each epoch will be displayed.

### 4. Testing
- After training, each model has a dedicated testing section to evaluate its accuracy on the CIFAR-100 dataset.

### NOTE
- do remeber that to download the all the images you want to evaluate should be put inside of a list in the evaluate part  

## Future Updates (V2)
In the next version, the repository will include:
- A direct comparison of both models' performance.
- More insights into training dynamics and potential improvements.

## Contribution
Feel free to fork this repository and experiment with different architectures or hyperparameters!

## License
This project is open-source and free to use.

