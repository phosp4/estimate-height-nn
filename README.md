# estimate-height-nn

This project is a regression task that predicts human height using body measurements through a neural network built with TensorFlow and Keras.

## Key Details
- **Dataset**: Body measurements from [Kaggle](https://www.kaggle.com/datasets/mexwell/body-measurements).
- **Model**: A simple neural network with 3 hidden layers using ReLU activation.
- **Performance**: Achieves a test loss of ~5 cm.
- **Usage**:
  1. Load the dataset (`bdims.csv`).
  2. Train the model (100 epochs, batch size 8).
  3. Predict height for new samples.

## Requirements
- Python, TensorFlow, Keras, Pandas, NumPy, Matplotlib, Scikit-learn.
