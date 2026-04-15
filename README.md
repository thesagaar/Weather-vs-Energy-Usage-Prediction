Weather vs Energy Usage Prediction using Linear Regression
📌 Overview
This project analyzes how weather conditions affect energy consumption using Linear Regression. 
We used weather features such as outside temperature, humidity, and wind speed to predict appliance energy usage.

📂 Dataset
Dataset: Appliances Energy Prediction Dataset

Source: Kaggle

Records: ~19,735 rows

Features Used:

T_out

RH_out

Windspeed

Target:

Appliances (Energy Consumption)

🛠 Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn 
Scikit-learn
Google Colab

📊 Project Workflow
Load Dataset Data Analysis Statistical Measures (Mean, Median, Mode, Variance, Std) Visualization Linear Regression Model Equation Generation Prediction Evaluation

📐 Regression Formula
Energy = a0 + a1(Tout) + a2(RHout) + a3(Windspeed)

📈 Outputs:

Heatmap:
<img width="437" height="311" alt="histogram" src="https://github.com/user-attachments/assets/a622fe95-3dc2-4f47-ba83-b95d2711a344" />

Scatter Plot:
<img width="380" height="232" alt="scatterplot" src="https://github.com/user-attachments/assets/1b3edf2d-af7f-430e-91ce-01a029c02124" />

Time plot:
<img width="750" height="293" alt="time plot" src="https://github.com/user-attachments/assets/dae69cd6-b2d4-40fd-9d57-f39ed8f8831b" />


Prediction Output:
Prediction

📉 Evaluation Metrics
Mean Squared Error (MSE) R² Score
🚀 How to Run
Open notebook in Google Colab Upload dataset Run all cells
📁 Files Included
Notebook (.ipynb) Report (.docx) Output Images Dataset
