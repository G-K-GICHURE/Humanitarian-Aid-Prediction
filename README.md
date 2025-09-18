# Humanitarian Aid Prediction Project

## 📌 Project Overview
This project demonstrates how data science and machine learning can be applied to humanitarian aid planning.  
Using a dummy dataset that simulates disaster frequency, population, and healthcare access across different regions,  
we build predictive models to estimate the number of aid units required.  

The goal is to show how organizations like the **Red Cross** can use data-driven insights to allocate resources more effectively.

---

## 🎯 Objectives
1. Generate a simulated dataset for humanitarian aid needs.
2. Perform data cleaning and exploratory data analysis (EDA).
3. Train and compare predictive models:
   - Linear Regression  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
4. Evaluate models using MAE, RMSE, and R².
5. Recommend the best-performing model and provide insights.

---

## 🛠️ Tech Stack
- Python 3.x  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## 📊 Dataset (Simulated)
The dummy dataset contains the following columns:
- **Country**: Region name  
- **Population**: Population size (in millions)  
- **Disaster_Frequency**: Number of disasters in the past 5 years  
- **Healthcare_Access**: Index (0–1) representing healthcare accessibility  
- **GDP_per_Capita**: Economic strength indicator  
- **Aid_Units_Needed**: Target variable (number of aid units required)  

---

## 📈 Results
After testing models:
- **Linear Regression** performed weakest.  
- **Random Forest Regressor** achieved the lowest RMSE.  
- **Gradient Boosting** also performed well but slightly below Random Forest.  

📌 **Recommendation**: Use **Random Forest** for predictions, as it balances accuracy and interpretability.

---

## 🚀 How to Run
1. Clone this repo  
2. Open `humanitarian_aid_prediction.ipynb` in Jupyter Notebook or VS Code  
3. Run all cells  
4. View results and visualizations  

---

## 🧭 Impact
This project highlights how predictive analytics can guide humanitarian organizations like the Red Cross in:
- Anticipating aid demand  
- Allocating resources efficiently  
- Responding proactively to crises  

---

👤 **Author**: George Gichure  
📞 Phone: 0718089143  
📧 Email: georgegichure007@gmail.com  
