# 🌾 Climate Change Impact on Crop Yields

dataset link
https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture/code

**Current status: single Jupyter notebook (early stage)**

This repository contains my work on analyzing and predicting how climate change affects crop yields using machine learning.

### What's inside right now

| File            | Description                                          |
|-----------------|------------------------------------------------------|
| climate.ipynb   | Main notebook — data exploration, preprocessing, model comparison, Gradient Boosting training + basic Gradio demo |

That's it for now 😄

### What the notebook does (roughly)

- Loads agriculture + climate dataset (~10,000 rows)
- Explores temperature, rain, CO₂, extreme weather, irrigation, fertilizers, soil health, adaptation strategies...
- Compares several regression models
- Keeps the best one → Gradient Boosting Regressor
- Shows a simple Gradio interface at the end to test predictions

### How to use it (right now)

1. Download or clone this repo
2. Open the notebook

```bash
jupyter notebook climate.ipynb
# or
jupyter lab
