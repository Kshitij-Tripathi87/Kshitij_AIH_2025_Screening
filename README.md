# AI Innovators Hub Screening Task (2025-26)

## README

---
Build a Predictor 
_Task: Predict tomorrow’s PM2.5 value in Delhi based on previous data._

---

### What method/model you used
**Method/Model:**  
- **Random Forest Ensemble Method:**  
  Utilized a Random Forest Regressor (scikit-learn) to forecast the next day's PM2.5 value for Delhi. The model leverages an ensemble of decision trees to enhance predictive accuracy and control overfitting in time series forecasting.

- **Data Used:**  
  `city_day.csv` (Delhi subset) from "Air Quality Data in India (2015 - 2020)" Kaggle dataset

**Key Steps:**
- Loaded and filtered data for Delhi  
- Cleaned and interpolated missing values  
- Created lag features and rolling averages to capture temporal patterns  
- Trained a Random Forest model using past pollutant values and engineered features  
- Predicted PM2.5 for the day after the dataset's end  
- Reported model evaluation metrics

---

### What your result was
**Result:**  
- **Predicted PM2.5 for [NEXT DAY, e.g., 2020-07-02]:** `44.83` µg/m³   
- **Air Quality Category:** `Very Poor`  
- [Optional] **Model Confidence:** `Medium`  


---



