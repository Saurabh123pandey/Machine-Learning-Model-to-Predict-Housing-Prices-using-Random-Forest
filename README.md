# 🏡 California Housing Price Prediction using Random Forest Regression  
### 📌 A complete Machine Learning pipeline for predicting house prices using the California Housing Dataset.

---

## 📖 **Project Overview**

This project builds a **Random Forest Regression model** to predict **California housing prices** based on multiple features like population, median income, house age, and geographical coordinates.

The project demonstrates:
- End-to-end ML workflow  
- Model evaluation  
- Feature importance  
- Residual analysis  
- Distribution comparison  

A fully visual explanation of model behavior is included.

---

## 📂 **Dataset Details**

The dataset is fetched directly from Scikit-Learn:

| Feature | Description |
|--------|-------------|
| MedInc | Median Income of the area |
| HouseAge | Median house age |
| AveRooms | Average rooms per household |
| AveBedrms | Average bedrooms per household |
| Population | Total population |
| AveOccup | Average household occupancy |
| Latitude | GPS coordinate |
| Longitude | GPS coordinate |

🎯 **Target Variable** → *Median House Value*

---

## 🏗️ **Project Architecture**

```text
Data Loading → Train-Test Split → Model Training (Random Forest)
            → Predictions → Evaluation (MSE, R²)
            → Visualization (4 advanced analysis plots)
