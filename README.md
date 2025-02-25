Dataset

Source: NSE-Tata-Global-Beverages-Limited.csv

Columns:

Date

Open

High

Low

Close

Volume

The dataset is preprocessed, sorted by date, and scaled using MinMaxScaler.

Technologies Used

Programming Language: Python

Libraries:

TensorFlow/Keras

Pandas

NumPy

Matplotlib

Scikit-Learn

Model Architecture

The model consists of:

Two LSTM layers:

First LSTM layer: 64 units, ReLU activation, returns sequences.

Second LSTM layer: 32 units, ReLU activation.

One Dense output layer with 1 unit for predicting the closing price.

Optimized using Adam optimizer with Mean Squared Error (MSE) as the loss function.
