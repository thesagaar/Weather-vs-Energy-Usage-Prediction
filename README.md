🌦️ Weather vs Energy Usage Prediction using Linear Regression

📌 Project Overview
This project predicts household appliance energy consumption using weather-related variables through Multiple Linear Regression.
It was developed as an academic project for Numerical Methods / Statistical Analysis, demonstrating complete data analysis, regression modeling, prediction, visualization, and evaluation.

🎯 Objective
To predict Appliances Energy Consumption using the following input variables:

  i. Outside Temperature (T_out)
 ii. Outside Humidity (RH_out)
iii. Windspeed (Windspeed)

Output Variable:
 Appliances (Energy Consumption)

📂 Dataset Information
Dataset: Appliances Energy Prediction Dataset
Source: Kaggle / UCI Repository
Rows: 19,735
Format: CSV

🛠️ Technologies Used

* Python
* Google Colab
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

📊 Statistical Analysis Performed
The following measures were calculated:

* Mean
* Median
* Mode
* Standard Deviation
* Variance
* Correlation

📐 Regression Model
General Formula:
Y = c + m₁X₁ + m₂X₂ + m₃X₃

Applied Formula:
Appliances = c + m₁(Tout) + m₂(RHout) + m₃(Windspeed)

Where:

* c = Intercept
* m₁, m₂, m₃ = Regression Coefficients

🔄 Workflow

* Import Libraries
* Load Dataset
* Data Inspection
* Null Value Check
* Statistical Analysis
* Feature Selection
* Train-Test Split
* Train Linear Regression Model
* Generate Equation
* Predict Values
* Visualize Results
* Final Summary

📈 Dashboard Output
Dashboard

Included Visualizations:

* Scatter Plot + Regression Line
* Sorted X vs Predicted Y
* Residual Plot
* Histogram of Residuals

📉 Evaluation Metrics

* MAE → Mean Absolute Error
* MSE → Mean Squared Error
* RMSE → Root Mean Squared Error
* R² Score → Explained Variance of Model

▶️ How to Run

Google Colab:

* Upload notebook file
* Upload dataset CSV
* Click Runtime → Run all

Local Jupyter Notebook:
bash
pip install -r requirements.txt
jupyter notebook

📦 Files Included

* Weather_vs_Energy_Usage_Prediction.ipynb
* requirements.txt
* outputs/weather_energy_dashboard.png
* report/Weather_Energy_Report.docx

🎓 Academic Purpose
This repository was created for coursework submission in:

* Numerical Methods
* Statistical Analysis
* Linear Regression

👨‍💻 Project team: 
 Sagar Prajapati | Ashish Sagare | Aarati Sav
