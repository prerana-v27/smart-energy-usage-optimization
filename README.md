# smart-energy-usage-optimization


This repository contains code, data, and results for predicting household electricity usage and recommending optimal lighting schedules using AI/ML and the UCI Individual Household Electric Power Consumption dataset.

---

## 📊 Project Overview

The goal is to minimize lighting energy wastage while maintaining comfort in a household, through:
- Short-term electricity usage forecasting
- (Optional) Occupancy inference or prediction
- Rule-based or ML-driven optimal lighting schedule recommendations
- Visualization of results and estimated energy savings

---

## 🗂️ Repository Structure

```
├── data/                  # Raw dataset (.txt from UCI)
├── notebooks/             # Jupyter notebooks for analysis, modeling, and reporting
├── src/                   # Source code scripts (preprocessing, modeling, optimization)
├── Outputs/               # Figures, tables, and generated results
├── README.md              # Project description and instructions
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/prerana-v27/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Install dependencies
Create and activate a Python environment:
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

### 3. Download the dataset
Place the `household_power_consumption.txt` file from [UCI Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption) into the `data/` folder.

### 4. Run analysis
- Open the Jupyter notebook(s) in `notebooks/` for step-by-step code, visualizations, and results.
- Outputs (plots, tables) are saved in the `Outputs/` folder.

---

## 📈 Results

- **MAPE for 15-min electricity usage forecast:** < 10%
- **Estimated lighting energy savings:** 10–25% (simulated, by optimal schedule)
- **Visualization examples:**  
  ![Hourly Usage](Outputs/power_usage_time_series.png)  
  ![Recommended Lighting Schedule](Outputs/lighting_schedule_day0.png)  

For more details, see the Results/Discussion section in the notebook and markdown files.

---

## ⚡ Limitations

- Dataset is aggregate (whole-house), not device-level; occupancy and lighting usage may require proxies or additional sensors.
- Results are for a single household; generalization to other homes may need cross-validation or transfer learning.

---

## 📚 References

- UCI Machine Learning Repository: [Individual household electric power consumption Data Set](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)
- [Scikit-learn documentation](https://scikit-learn.org/stable/documentation.html)
- [Keras LSTM Tutorial](https://keras.io/examples/timeseries/timeseries_forecasting_lstm/)

---

## 🙏 Acknowledgements

Thanks to the UCI ML Repository, open-source library authors, and [Instructor Name] for guidance.

---

## 🔗 Project Link

You are welcome to explore, reproduce, or extend this project by visiting the repository:

[https://github.com/prerana-v27/<your-repo-name>](https://github.com/prerana-v27/<your-repo-name>)

---
