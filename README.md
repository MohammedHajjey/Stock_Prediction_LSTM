# 📈 Stock Price Prediction using LSTM

This project uses an LSTM (Long Short-Term Memory) neural network to predict stock prices based on historical data using TensorFlow/Keras. It demonstrates time series preprocessing, model training, and visualization of both predicted and actual prices.

---

## Project Structure

- `Stock_Prediction_LSTM.ipynb`: Main notebook for preprocessing, model training, evaluation, and visualization.
- `model.keras`: Trained model saved in Keras format.
- `bimas-bim-magazalar.csv`: Sample dataset used for training/testing.
- `README.md`: Project documentation.

---

## Features

- Data preprocessing and scaling with `MinMaxScaler`
- Sequence generation for time series prediction
- LSTM-based deep learning model with:
  - Two LSTM layers
  - Dropout for regularization
  - Dense layers for output
- Early stopping and model checkpointing
- Visualization of training loss and predictions
- Real vs predicted plots for last 10 days

---

## Libraries Used

- Python 3
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## Sample Visualizations

-  Loss per epoch (training vs validation)
-  Real vs predicted prices over time
-  Comparison of actual vs predicted values for the last 10 days

---
---

##  How to Run

1. Upload your dataset as `bimas-bim-magazalar.csv`.
2. Run all cells in `Stock_Prediction_LSTM.ipynb`.
3. Visualize the model’s prediction accuracy.

---

##  Dataset Format

Your CSV should have at least the following column:
- `Date`: time series index
- `open`: stock open price

---

##  Contact

If you have questions or suggestions, feel free to open an issue or reach out!
mhaci200188@gmail.com

Made with by [MohammedHajjey](https://github.com/MohammedHajjey)
 


