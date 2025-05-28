# energy-forecasting-usa

Deep learning models (LSTM, RNN, RBM) for electricity demand and CO₂ forecasting in the U.S. energy sector.

---

## 📌 Project Objective

To compare and evaluate the effectiveness of deep learning models in forecasting electricity demand and estimating carbon emissions, using U.S. energy datasets. The goal is to inform sustainable energy planning and policy-making.

---

## 📊 Dataset

- Source: [U.S. Energy Information Administration (EIA)](https://www.eia.gov/)
- Time series data includes:
  - Hourly electricity demand
  - CO₂ emissions by region
  - Renewable energy penetration metrics

---

## 🧠 Models Implemented

1. **LSTM (Long Short-Term Memory)**
2. **RNN (Recurrent Neural Network)**
3. **RBM + NN (Restricted Boltzmann Machine + Neural Net)**

Each model was evaluated on:
- Forecast accuracy (MAE, RMSE)
- Ability to handle seasonality and trends
- Prediction stability across U.S. regions

---

## 🧪 Notebooks Breakdown

- `01.data_cleaning.ipynb` → Handling missing values, resampling
- `02.Feature_engg.ipynb` → Lag features, normalization, energy metrics
- `03.Visualisation.ipynb` → Trend/seasonal plots, correlation heatmaps
- `04.Modelling.ipynb` → Deep learning model training and comparison

---

## 📈 Key Results

- **LSTM outperformed RNN and RBM+NN** in most regional scenarios.
- California showed the highest variance reduction after model tuning.
- Insights indicate potential 10-12% improvement in grid efficiency when using forecast-backed planning.

---

## 📎 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Scikit-learn, Keras)
- Jupyter Notebooks
- Time-series forecasting methods
- Deep learning architectures (TensorFlow/Keras)

---

## 📚 What I Learned

- Advanced time-series forecasting techniques
- Hyperparameter tuning of deep learning models
- How to evaluate carbon emissions impact from renewables

---

## 📬 Contact

If you have any questions or suggestions, feel free to connect:

- 💼 [LinkedIn](https://www.linkedin.com/in/ann-mary-thomas-6272aa200)
- ✉️ annmarytttt@gmail.com

---

> ⭐ Star this repo if you found it useful. Thank you!
