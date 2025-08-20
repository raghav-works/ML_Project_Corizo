# ML_Project_Corizo
# ✈️ Flight Price Prediction

This project predicts flight ticket prices using **Machine Learning models**. It involves data cleaning, exploratory data analysis (EDA), feature engineering, and model evaluation. The notebook compares **Linear Regression** and **Random Forest Regressor** for price prediction.

---

## 📂 Project Structure

* `ML_Corizo.ipynb` → Main Jupyter Notebook with code and analysis
* `README.md` → Project documentation
* `data/` → Dataset (not included here due to size/privacy)

---

## 🔍 Problem Statement

Airline ticket prices fluctuate due to multiple factors such as journey date, departure/arrival time, duration, stops, airline, and route. The goal is to build a machine learning model to predict flight fares more accurately.

---

## 🛠️ Workflow

1. **Data Preprocessing & Cleaning**

   * Handling missing values
   * Parsing dates, times, and durations

2. **Exploratory Data Analysis (EDA)**

   * Distribution of flight fares
   * Impact of stops, airlines, and routes
   * Correlation analysis

3. **Feature Engineering**

   * Duration
   * Departure & Arrival Time
   * Date of Journey
   * Total Stops
   * Airline & Additional Info
   * Source & Destination
   * Route encoding

4. **Model Building & Evaluation**

   * Linear Regression
   * Random Forest Regressor
   * Metrics: Accuracy, RMSE, R² Score

---

## 📊 Results

* **Linear Regression**

  * R² Score: \~65.1%
  * Higher prediction error

* **Random Forest Regressor**

  * R² Score: \~82.7%
  * 23.8% improvement in accuracy over Linear Regression
  * Lower RMSE → More reliable predictions

✅ **Conclusion**: Random Forest significantly outperforms Linear Regression due to its ability to model non-linear feature interactions.

---

## 🚀 Technologies Used

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* Jupyter Notebook

---

## 📌 Future Improvements

* Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
* Feature selection & dimensionality reduction
* Trying Gradient Boosting, XGBoost, or LightGBM
* Deploying as a web app using Flask or Streamlit

---

## 👨‍💻 Author

Developed as part of a Machine Learning project with Corizo.

---

## 📜 License

This project is open-source and available under the MIT License.
