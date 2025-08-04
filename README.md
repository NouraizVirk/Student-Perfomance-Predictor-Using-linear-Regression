# Student Score Prediction Using Linear Regression

This project demonstrates a machine learning model that predicts students’ exam scores based on their study hours. It uses the [Student Performance Factors Dataset](https://www.kaggle.com/datasets) from Kaggle. The model helps visualize and understand the relationship between study habits and academic performance.

---

## 📊 Project Overview
- **Goal:** Predict exam scores from study hours
- **Approach:** Linear Regression
- **Dataset:** Student Performance Factors (Kaggle)
- **Tools & Libraries:** Python, Pandas, Matplotlib, Scikit-learn, NumPy

---

## 🛠️ Steps Performed
1. **Data Loading & Cleaning**
   - Loaded the dataset with Pandas
   - Checked for missing values and data types
2. **Exploratory Data Analysis**
   - Summary statistics
   - Scatter plots of study hours vs exam scores
3. **Model Training**
   - Train/test split
   - Trained a Linear Regression model
4. **Evaluation**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
5. **Visualization**
   - Scatter plot of actual vs predicted values
   - Regression line overlay

---

## 📈 Results
- Average prediction error: ~2–3 exam points
- R² Score: ~0.23 (model explains ~23% of the variation in scores)
- Conclusion: Study hours positively impact exam performance, though other factors also play a role.

--- 

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/NouriazVirk/student-score-prediction.git
   cd student-score-prediction
