📈 **Stock Price Prediction using RNN & LSTM**

This project builds a **time series prediction model** for **stock price forecasting** using **Recurrent Neural Networks (RNNs) and LSTMs** in **Keras**. The model leverages historical stock price data to predict future trends, demonstrating the effectiveness of deep learning in financial time series forecasting.  

🚀 Project Overview  
- Implemented **RNN & LSTM models** for stock price prediction.  
- Preprocessed stock market data with **normalization & sequence preparation**.  
- Trained the model using **Keras & TensorFlow** with adjustable hyperparameters.  
- Evaluated predictions using **Mean Squared Error (MSE) & RMSE metrics**.  

📌 Features  
  **Deep Learning Model:**  
  - **Recurrent Neural Network (RNN) & LSTM-based time series forecasting**.  
  - **Uses historical stock price data** for future trend prediction.  
  - **Adjustable hyperparameters** (window size, batch size, optimizer, etc.).  
  
   **Data Processing & Training:**  
  - **Data Normalization:** Standardizes stock price values for stable training.  
  - **Sequence Creation:** Converts raw time series data into **supervised learning format**.  
  - **Hyperparameter Optimization:** Grid search for best model configuration.  
  
  **Evaluation & Visualization:**  
  - **Loss vs. Epochs graph** to analyze model convergence.  
  - **Actual vs. Predicted stock price plot** for trend comparison.  

📦 **Installation & Setup** 
  To set up and run the project locally, follow these steps:  
  
  1. **Clone this repository:**  
     ```bash
     git clone https://github.com/your-username/Stock-Price-Prediction.git
     cd Stock-Price-Prediction
  2. **Install dependencies:**
     ```bash
     pip install -r requirements.txt
  3. **Run the Jupyter Notebook:**
     ```bash
  4. **jupyter notebook**
     ```bash
     jupyter notebook

📊 **Dataset**
The model is trained on historical stock price data.
Data preprocessing includes scaling, windowing, and sequence conversion.

📈 **Results**
MSE & RMSE scores to evaluate prediction accuracy.
Visual comparison between actual vs. predicted stock prices.
