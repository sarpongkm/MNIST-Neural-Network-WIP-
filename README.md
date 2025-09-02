# MNIST Neural Network (WIP)


> Work in Progress — this repo explores building a neural network from scratch (NumPy) to classify MNIST digits. This is part of my learning journey.


## Status
-  Data loading and preprocessing (train/dev split)
-  Basic setup with NumPy arrays
-  Forward propagation implementation
-  Backpropagation & parameter updates
-  Accuracy evaluation & confusion matrix


## Dataset

This project uses the **Kaggle Digit Recognizer (MNIST)** dataset.

- Download `train.csv` and `test.csv` from the Kaggle competition page:  
   [https://www.kaggle.com/c/digit-recognizer/data](https://www.kaggle.com/c/digit-recognizer/data)



## Quickstart
### 1) Environment
```bash
python -m venv .venv
source .venv/bin/activate # Windows: .venv\Scripts\activate
pip install -r requirements.txt
