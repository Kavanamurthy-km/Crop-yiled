# 🌾 Crop Yield Prediction Based on Indian Agriculture

This project aims to predict crop yields based on agricultural and environmental data from various regions in India. By using machine learning models, the system helps optimize farming practices and supports farmers in making data-driven decisions.

---

## 📁 Project Structure

- `data/` – Includes the crop production and environmental datasets
- `notebooks/` – EDA and model building Jupyter notebooks
- `models/` – Saved machine learning models
- `scripts/` – Utility functions for preprocessing and training
- `README.md` – Project documentation

---

## 🧪 Technologies Used

- **Python** (NumPy, Pandas)
- **Matplotlib, Seaborn** for data visualization
- **Scikit-learn** for ML models
- **Random Forest, Linear Regression**
- **MySQL** for structured data storage
- **HTML** (for basic frontend integration)

---

## 📈 Problem Statement

Crop yield prediction is essential for ensuring food security, improving planning for agricultural activities, and supporting economic stability. The objective is to use weather, soil, and crop-related features to accurately forecast yield per hectare.

---

## 📊 Model Performance

- ✅ **Model Used**: Random Forest Regressor  
- 🎯 **Accuracy**: **90%**  
- 📌 **Optimizations**: Feature selection, hyperparameter tuning

---

## 📉 Data Scope

The dataset includes:
- Rainfall, temperature, humidity
- Crop type, season, soil condition
- Region and district-specific agricultural inputs

---

## 🚀 How to Run This Project

```bash
# Clone the repository
git clone https://github.com/yourusername/crop-yield-prediction.git

# Install dependencies
pip install -r requirements.txt

# Open and run the main notebook
jupyter notebook notebooks/crop_yield_model.ipynb

