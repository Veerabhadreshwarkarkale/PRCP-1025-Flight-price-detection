# PRCP-1025-Flight-price-detection
Flight price prediction using ML models with EDA, feature engineering, and regression algorithms. Provides insights for customers and travel platforms to optimize pricing.
# ✈️ Flight Price Prediction

This project predicts flight ticket prices based on various features such as airline, source, destination, number of stops, and journey details.  
It applies **Machine Learning regression models** to provide accurate price forecasts, helping in decision-making for travelers and businesses.  

---

## 📌 Project Overview
- Implemented data preprocessing and feature engineering on flight dataset.  
- Built multiple regression models (Linear Regression, Random Forest, Gradient Boosting, etc.) to predict flight fares.  
- Evaluated performance using metrics like **R² score, MAE, and RMSE**.  
- Visualized key insights such as price trends by airline, stops, and duration.  

---

## 📊 Dataset Features
The dataset contains the following columns:  

- **Airline** – Name of the airline (IndiGo, Jet Airways, Air India, etc.)  
- **Date_of_Journey** – Travel date  
- **Source** – Starting location of the journey  
- **Destination** – Ending location of the journey  
- **Route** – Path taken from source to destination  
- **Arrival_Time** – Arrival time at the destination  
- **Duration** – Total travel time  
- **Total_Stops** – Number of stops during the journey  
- **Additional_Info** – Extra details like food, baggage, etc.  
- **Price** – 🎯 Target variable (flight fare in INR)  

---

## ⚙️ Technologies Used
- Python 🐍  
- Pandas & NumPy – Data preprocessing  
- Matplotlib & Seaborn – Data visualization  
- Scikit-learn – Machine Learning models  
- Jupyter Notebook  

---

## 📈 Results
- Achieved good prediction accuracy with ensemble models (Random Forest & Gradient Boosting).  
- Found that **Airline, Total Stops, and Duration** are the most significant factors in predicting flight prices.  

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/Veerabhadreshwarkarkale/PRCP-1025-Flight-price-detection.git
