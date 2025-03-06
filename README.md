# 📈 LSTM-based-Bitcoin-prediction

## 🚀 Overview

This project leverages **Long Short-Term Memory (LSTM)** networks to predict bitcoin prices using historical data. The dataset is sourced from **Kaggle** and preprocessed to fit into an LSTM-based deep learning model for time series forecasting.

## 📊 Dataset

The dataset is obtained from **Kaggle**, containing historical stock prices with essential features like **Open, High, Low, Close, Volume**, and **Date**.

## 🔧 Features & Tech Stack

✅ **LSTM Model** for sequential data prediction\
✅ **Data Preprocessing** (Normalization, Scaling, Reshaping)\
✅ **Visualization** with Matplotlib & Seaborn\
✅ **TensorFlow/Keras** for deep learning implementation\
✅ **Pandas & NumPy** for data manipulation

## 🛠 Installation

To run the project, install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn tensorflow keras
```

## 📌 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/momina02/LSTM-based-Bitcoin-prediction.git
   cd LSTM-based-Bitcoin-prediction
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Prediction using LSTM.ipynb` and execute the cells.

## 📉 Model Architecture

The LSTM model consists of:

- **Input Layer**: Stock price features
- **LSTM Layers**: Capturing temporal dependencies
- **Dense Layer**: Outputting predicted prices

## 📊 Results & Visualization

📌 The model outputs predicted stock prices, which are plotted against actual prices for comparison.

## 🎯 Future Improvements

🔹 Hyperparameter tuning for better accuracy\
🔹 Experiment with additional features\
🔹 Integrate real-time stock data API

## 🤝 Contributing

Feel free to fork and contribute! Pull requests are welcome.

🔥 **Star this repo if you found it helpful!** ⭐

