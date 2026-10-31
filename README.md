# 🚚 Food Delivery Data Analysis

## 📌 Project Overview
This project analyzes food delivery data using Python to understand delivery time, customer ratings, traffic conditions, weather conditions, and delivery distance.

## 🎯 Project Objectives
1. Detect 5 outliers using the IQR method.
2. Handle missing customer ratings.
3. Create an `is_late` column for deliveries over 45 minutes.
4. Analyze delivery time by traffic, weather, and time of day using box plots.
5. Visualize distance vs delivery time with a regression line.
6. Analyze delivery time vs customer rating.
7. Predict delivery time using NumPy `polyfit()`.

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Key Findings
- Identified delivery-time outliers using IQR.
- Analyzed customer ratings and delivery time.
- Observed a negative relationship between delivery time and rating.
- Used linear regression to estimate delivery time from distance.

## 🤖 Linear Regression Model
Used `np.polyfit()` to predict delivery time from distance.

- Slope: 3.2246
- Intercept: 22.6913
- Predicted time for 5 KM: 38.81 minutes.

## 📁 Project Files
- `Food_Delivery_Analysis.ipynb` – Python analysis and visualizations.
- `food_delivery.csv` – Dataset.
- `README.md` – Project documentation.

## 📝 Conclusion
This project demonstrates data cleaning, exploratory data analysis, data visualization, feature engineering, and basic linear regression using Python.

## 👨‍💻 Author
Hansraj More

B.Sc. Computer Science | Aspiring Data Analyst
