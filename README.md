# Classroom Temperature Prediction

## Project Description
This project uses a **Random Forest Regression model** to predict classroom temperatures based on multiple environmental and occupancy features. The goal is to estimate the temperature in a classroom at different times of the day, which can help with comfort and energy management.

## Why we used Random Forest?

Random Forest was chosen for this project because it performs well on small datasets with mixed feature types (numerical and categorical). It can capture non-linear relationships between classroom conditions and temperature, is robust to occasional outliers, and provides insights into feature importance. Compared to models like linear regression or neural networks, Random Forest offers a good balance of accuracy, reliability, and interpretability for predicting classroom temperature.

**Features used in the model:**
- AC usage
- Number of people in the classroom
- Window status (open/closed)
- Outdoor temperature
- Time of day

---

## How to Run
1. Clone or download this repository.  
2. Make sure the dataset `class_temp_log.csv` is in the same folder as the Jupyter Notebook.  
3. Open the Jupyter Notebook `classroom_temp_model.ipynb`.  
4. Run all cells to load the data, train the model, and generate predictions.  

---

## Model Performance
- Mean Absolute Error (MAE): 0.31 °C  
- Root Mean Squared Error (RMSE): 0.37 °C  

This shows the model is very reliable at predicting the **average classroom temperature** using the selected features.  

