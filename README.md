# 🌾 Climate Change Impact on Crop Yields

This project analyzes and predicts the impact of climate change on crop yields using machine learning techniques.  
It explores how environmental and agricultural factors such as temperature, rainfall, CO₂ levels, soil health, fertilizers, and adaptation strategies influence agricultural productivity.

> **Project status:** Early stage — currently implemented as a single Jupyter Notebook with model training and a basic Gradio demo.

---

## 📊 Dataset

- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture/code  
- **Size:** ~10,000 records  
- **Type:** Structured tabular data (climate + agriculture features)

---

## 📁 Project Structure

| File | Description |
|------|------------|
| `climate.ipynb` | Main notebook containing data exploration, preprocessing, model comparison, training, evaluation, and a basic Gradio interface |
| `README.md` | Project documentation |

---

## 🔍 What This Project Does

The notebook performs the following steps:

- Loads and cleans agriculture and climate-related data
- Exploratory Data Analysis (EDA) on:
  - Temperature
  - Rainfall
  - CO₂ emissions
  - Extreme weather events
  - Irrigation, fertilizers, soil health
  - Climate adaptation strategies
- Feature preprocessing and scaling
- Trains and compares multiple regression models
- Selects the **best-performing model**
- Deploys a **basic Gradio UI** for interactive crop yield prediction

---

## 🤖 Models Used

Several regression algorithms were trained and evaluated, including:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- **Gradient Boosting Regressor (Final Model)**

The **Gradient Boosting Regressor** was selected based on superior performance across evaluation metrics.

---

## 📈 Model Performance

The final model was evaluated using regression metrics such as:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- R² Score: 0.62 
MAE: 0.42  
MSE: 0.61  


✅ **Gradient Boosting Regressor achieved the best overall performance**, showing strong predictive capability for crop yield under varying climate conditions.

---

## 🧪 Technologies Used

- **Python**
- **Pandas, NumPy** – data manipulation
- **Matplotlib, Seaborn** – data visualization
- **Scikit-learn** – machine learning models & evaluation
- **Gradient Boosting Regressor**
- **Gradio** – interactive model deployment
- **Jupyter Notebook**

---

## 🚀 Demo (Gradio)

A simple Gradio interface is included at the end of the notebook, allowing users to:
- Input climate and agricultural parameters
- Get predicted crop yield values interactively

---

## 🔮 Future Improvements

- Convert notebook into a modular Python pipeline
- Deploy the Gradio app on Hugging Face Spaces or Streamlit Cloud
- Perform hyperparameter tuning (GridSearch / Bayesian Optimization)
- Add feature importance & explainability (SHAP)
- Include time-series analysis for climate trends
- Improve UI/UX of the web interface

---


### How to use it (right now)

1. Download or clone this repo
2. Open the notebook
3. ## Project Screenshot

![Model Screenshot](https://raw.githubusercontent.com/SANA956792/Global-Crop-Yield-Prediction-in-a-Changing-Climate/main/path/to/image.png)


```bash
jupyter notebook climate.ipynb
# or
jupyter lab
