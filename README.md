---

# Forecasting Second-Hand Textile Demand and Associated Waste Generation Using Recurrent Neural Networks in Nairobi County

## 📌 Overview
This project applies **Long Short-Term Memory (LSTM)**, a type of Recurrent Neural Network (RNN), to forecast the **demand for second-hand textiles** and the **associated waste generation** in **Nairobi County**. The growing volume of second-hand clothing imports—driven by fashion trends and affordability—has led to increased waste, overstocking, and environmental stress. Our model aims to support **data-driven policy** and **sustainable waste management** through accurate time-series forecasting.

## 🎯 Objectives
- Identify trends and spikes in second-hand clothing imports and waste generation.
- Forecast demand and waste using LSTM models.
- Evaluate model performance using MAE, MAPE, and R² metrics.

## 🧠 Model Architecture
- Stacked **LSTM** with 4 hidden layers.
- Dropout layers to reduce overfitting.
- Sliding window input sequences (3-month rolling).
- Loss Function: **Mean Squared Error (MSE)**

## 🧪 Evaluation Metrics
| Metric | Imports Model | Waste Model |
|--------|----------------|-------------|
| MAE    | 631.07 tons    | 428.07 tons |
| MAPE   | 2.94%          | 3.07%       |
| R²     | 0.9512         | 0.9415      |

## 📈 Forecast (2024–2026)
| Year | Imports (tons) | Waste (tons) |
|------|----------------|--------------|
| 2024 | 24,116         | 7,887        |
| 2025 | 23,351         | 7,087        |
| 2026 | 23,521         | 7,954        |

## 🔧 Tools & Libraries
- **Python**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `sklearn`, `tensorflow`, `keras`

## 🧹 Data Preprocessing
- Normalization with `MinMaxScaler`
- Categorical encoding (e.g., policy changes)
- Sliding windows for sequential input generation

## 📚 Data Sources
- **Kenya National Bureau of Statistics (KNBS)**
- **Africa Data Hub**
- **World Bank Open Data**
- News reports, government policies, and NGO publications

## 📊 Results Summary
The LSTM model effectively captured temporal patterns in import and waste trends, offering a reliable tool for **forecasting**, **resource planning**, and **policy development**. The insights can support a **participatory circular economy** and better waste handling systems in Nairobi.

## 📎 Notebook Link
View the full code and model here:  
🔗 [LSTM_FinalBest.ipynb](https://github.com/Kenethoriga/DataOpsKit/blob/main/LSTM_FinalBest.ipynb)

## 👥 Authors
- Mutune Carole  
- Wahu Annabel  
- Gacheru David  
- Jeremiah Mbunu  
- **Keneth Origa**  
- Supervisor: Dr. Benjamin Muema

---
