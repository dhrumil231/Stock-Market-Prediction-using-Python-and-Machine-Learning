-----

# 📈 Stock Market Prediction using Python & Machine Learning

An advanced machine learning project to forecast stock price trends by leveraging historical market data and multiple time-series models. This solution provides a data-driven framework to support **smarter investment decisions** by predicting future stock movements.

| 🚀 **Status** | 🐍 **Language** | 🛠️ **Models Used** | 📊 **Data Source** |
| :---: | :---: | :---: | :---: |
| **Complete** | **Python** | **ARIMA, LSTM, Prophet** | **Yahoo Finance** |

-----

## ⭐ Project Purpose & Value

The ability to accurately forecast stock price movements is crucial for investors and financial analysts. This project addresses that need by creating a comprehensive framework for **predicting stock prices** for selected financial assets.

Key project objectives include:

  * **🔍 Forecasting Accuracy:** Developing and comparing robust time-series models (ARIMA, LSTM, Prophet) to achieve the **highest possible prediction accuracy** over a short-term horizon.
  * **⚙️ Feature Engineering:** Utilizing essential features from daily stock data, including **past prices**, **macroeconomic indicators**, and **fundamental data**.
  * **💡 Informed Decisions:** Providing predicted stock price trends that can inform **investment strategies** and **mitigate risk**.

-----

## ✨ Key Features & Methodology

The analysis and prediction pipeline is fully documented in the provided Jupyter Notebook.

1.  **📥 Data Acquisition & Cleaning:** Automated daily stock data collection from **Yahoo Finance** followed by robust preprocessing, cleaning, and normalization to handle outliers.
2.  **🔧 Feature Engineering:** Calculation of various **Technical Indicators** (e.g., Moving Averages) to enrich the dataset for better model performance.
3.  **🧠 Multi-Model Approach:** Training and evaluating **three distinct machine learning models** to capture different time-series dynamics:
      * **ARIMA:** For capturing auto-correlation in the data.
      * **LSTM (Deep Learning):** A Recurrent Neural Network designed to learn long-term dependencies in sequences.
      * **Prophet (from Meta):** A model built for forecasting time series data with strong seasonal effects.
4.  **📉 Model Evaluation:** Performance is rigorously evaluated using standard metrics like **Root Mean Square Error (RMSE)** and **Mean Absolute Error (MAE)** to select the best-performing predictor.

-----

## 💻 Tech Stack & Dependencies

This project is built entirely on the Python data science ecosystem.

  * **Python** (3.x)
  * **Pandas & NumPy:** For data manipulation and numerical operations.
  * **Scikit-learn:** For general machine learning utilities.
  * **TensorFlow / Keras:** For building and training the **LSTM** deep learning model.
  * **`statsmodels`:** For the **ARIMA** model implementation.
  * **Prophet:** For the specialized time-series forecasting model.
  * **Matplotlib & Plotly:** For comprehensive **visualizations** of stock trends and predictions.

-----

## 🛠️ Getting Started (Run Locally)

Follow these steps to set up the project and run the prediction models on your local machine.

### Prerequisites

You need **Python** installed on your system. It is highly recommended to use a virtual environment.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/dhrumil231/Stock-Market-Prediction-using-Python-and-Machine-Learning.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Stock-Market-Prediction-using-Python-and-Machine-Learning
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    # Assuming a requirements.txt file exists or by installing manually:
    # pip install pandas numpy scikit-learn tensorflow matplotlib prophet statsmodels
    ```
4.  **Run the analysis:**
      * Launch the Jupyter environment: `jupyter notebook`
      * Open the file **`Stock_Market_Prediction_final_presentation.py`** or the main analysis notebook to execute the full data-to-prediction pipeline.

-----

## 📂 Repository Structure

```
.
├── Final_Project_Report_Stock_Market_Prediction.docx  # Project Report / Documentation
├── README.md                                        # This file
├── Stock_Market_Prediction_final_presentation.py    # Main Python script for running models
└── requirements.txt                                 # List of required Python packages
```

-----
-----

## 🤝 Contact

  * **Author:** Dhrumil Shah
  * **GitHub:** [@dhrumil231](https://github.com/dhrumil231)
