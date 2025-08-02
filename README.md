# 🌟 EV Charging Demand Prediction

**Python** | **Streamlit** | **scikit-learn** | **Heroku/Streamlit Cloud** | **MIT License**

An AI-powered application that predicts Electric Vehicle (EV) adoption trends across counties using historical data and visualizes 3-year forecasts in a Streamlit dashboard. Ideal for urban planners, green tech initiatives, and infrastructure optimization.

---

## 🚀 Quick Start • 📖 Features • 🧠 ML Pipeline • 📊 Deployment • 🤝 Contributing

---

## 📃 Table of Contents

* 🌟 Overview
* 🚀 Quick Start
* ✨ Features & Use Cases
* 📊 Dataset
* 🧠 ML Pipeline
* 🛠️ Technical Details
* 📅 Setup & Installation
* 🌚 Forecast Examples
* 📊 Charts & Outputs
* 🚀 Deployment Options
* 🤝 Contributing
* 📄 License
* 📧 Contact

---

## 🌟 Overview

This project provides county-level EV demand forecasting based on historical adoption trends from Washington State. It enables:

* ✅ ML-based 36-month demand forecasting
* 📈 Growth analysis for targeted infrastructure planning
* 📊 Easy-to-use interactive dashboard built with Streamlit

---

## 🚀 Quick Start

### Prerequisites

* Python 3.8+
* pip installed

### Installation

```bash
# Clone the repository
git clone https://github.com/tanishka234/EV_VEHICLE_DEMAND_PREDICTION.git
cd EV_VEHICLE_DEMAND_PREDICTION

# Install dependencies
pip install -r requirements.txt

# Launch the Streamlit app
streamlit run app.py
```

> 🌐 Visit [http://localhost:8501](http://localhost:8501) in your browser.

---

## ✨ Features & Use Cases

| Feature                 | Description                                 |
| ----------------------- | ------------------------------------------- |
| 📅 3-Year Forecast      | Predict EV growth for each county           |
| 🏢 Urban Planning Tool  | Optimize charging stations by future demand |
| 📊 Visual Dashboard     | Streamlit-based interactive charts          |
| 🔄 Compare Counties     | Analyze multiple counties side-by-side      |
| 📊 Time-Series Analysis | Random Forest applied to temporal features  |

---

## 📊 Dataset

**Source:** [Washington State EV Population](https://catalog.data.gov/dataset/electric-vehicle-population-data)
**File:** `Electric_Vehicle_Population_By_County.csv`

| Column                | Description                      |
| --------------------- | -------------------------------- |
| County                | County name                      |
| Electric Vehicle Type | Battery Electric, Plug-in Hybrid |
| Model Year            | Year of vehicle registration     |
| Forecast Target       | Total vehicle counts per county  |

Processed version: `preprocessed_ev_data.csv`

---

## 🧠 Machine Learning Pipeline

**Model:** RandomForestRegressor

* **Input Features:** County, Year, EV type
* **Output:** Predicted EV counts for next 36 months
* **Training:** Performed in `EV_Adoption_Forecasting.ipynb`
* **Model Saved As:** `forecasting_ev_model.pkl`

---

## 🛠️ Technical Details

| Component        | Tool/Lib Used              |
| ---------------- | -------------------------- |
| Model Training   | scikit-learn               |
| Visualization    | Streamlit                  |
| Deployment       | Streamlit Cloud, Heroku    |
| Environment Mgmt | requirements.txt, Procfile |

---

## 📅 Setup & Usage

### Step 1: Prepare Environment

```bash
git clone https://github.com/tanishka234/EV_VEHICLE_DEMAND_PREDICTION.git
cd EV_VEHICLE_DEMAND_PREDICTION
pip install -r requirements.txt
```

### Step 2: Run the App

```bash
streamlit run app.py
```

> Output at: [http://localhost:8501](http://localhost:8501)

---

## 🌚 Example Forecasts

1. **King County**:

   * 2025: \~42,000 EVs
   * 2026: \~51,000 EVs
   * 2027: \~61,000 EVs

2. **Spokane County**:

   * 2025: \~5,600 EVs
   * 2026: \~7,000 EVs
   * 2027: \~8,700 EVs

---

## 📊 Visualization Outputs

* Line chart: EV growth per county
* Bar chart: County comparison by year
* Pie chart: EV type distribution

---

## 🚀 Deployment Options

| Platform          | Instructions                      |
| ----------------- | --------------------------------- |
| Localhost         | `streamlit run app.py`            |
| Streamlit Cloud   | Connect repo + deploy via UI      |
| Heroku            | Add `Procfile` + GitHub deploy    |
| Docker (optional) | Build custom image (not included) |

---

## 🤝 Contributing

### How to Contribute

* Fork this repo
* Create a new branch: `feature/your-feature`
* Make changes and commit: `git commit -m "Add awesome feature"`
* Push: `git push origin feature/your-feature`
* Open a Pull Request

### Development Ideas

* Add EV pricing trend forecast
* Include population density as a feature
* Improve forecasting with XGBoost or Prophet

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

**Author:** Tanishka Jain
**GitHub:** [tanishka234](https://github.com/tanishka234)

Feel free to open an issue for bugs or suggestions!

---

> ✨ *Empowering green mobility through data & AI.*

