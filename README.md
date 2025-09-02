# MNIST Neural Network (WIP)


> Work in Progress — this repo explores building a neural network from scratch (NumPy) to classify MNIST digits. This is part of my learning journey.


## Status
-  Data loading and preprocessing (train/dev split)
-  Basic setup with NumPy arrays
-  Forward propagation implementation
-  Backpropagation & parameter updates
-  Accuracy evaluation & confusion matrix


## Dataset
- Source: Kaggle Digit Recognizer (MNIST), 28×28 grayscale digits
- `train.csv` must be placed in repo root or adjust path.


## Quickstart
### 1) Environment
```bash
python -m venv .venv
source .venv/bin/activate # Windows: .venv\Scripts\activate
pip install -r requirements.txt
