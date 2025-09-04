# Medical Insurance Charges Prediction

## Problem Statement
Predict medical insurance charges based on personal attributes such as age, BMI, smoking habits, number of children, sex, and region using regression algorithms. This helps insurance companies and individuals estimate expected medical costs.

---

## Dataset
- 200 rows, 7 columns:
  - `age` – Age of the individual
  - `sex` – Gender (male/female)
  - `bmi` – Body Mass Index
  - `children` – Number of children/dependents
  - `smoker` – Yes/No
  - `region` – Southwest, Southeast, Northwest, Northeast
  - `charges` – Medical insurance cost (target variable)

---

## Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Checked dataset shape, summary statistics, and missing values.
- Visualized distributions of features and target variable.

### 2. Data Preprocessing
- Label encoding for categorical variables: `sex`, `smoker`, `region`.
- Feature scaling using `StandardScaler`.

### 3. Feature Selection
- Features (`X`): `age`, `sex`, `bmi`, `children`, `smoker`, `region`.
- Target (`y`): `charges`.

### 4. Model Training
- Trained **RandomForestRegressor** (and optionally other regression models like Linear Regression, Decision Tree, Gradient Boosting).
- Split data into train/test sets (80/20).

### 5. Model Evaluation
- Metrics used:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
- Visualized **Actual vs Predicted charges**.

### 6. Insights
- Average charges differ by region.
- Smoking and BMI significantly impact charges.
- Age and number of children also affect cost but to a lesser extent.

---

## Sample Visualizations

### Actual vs Predicted Charges
![Actual vs Predicted](images/actual_vs_predicted.png)

### Average Charges by Region
![Average Charges](images/average_charges.png)

---

## How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib scikit-learn joblib

# Run the script
python medical_insurance_project.py





Author

Induri Avinash Reddy
B.Tech AIML Student | Data Science & ML Enthusiast
LinkedIn: https://www.linkedin.com/in/avinash-reddy-induri-4662b832a




---

If you want, I can **also give you the Python code snippet to automatically save your plots into the `images` folder** so that your GitHub README images work perfectly.  

Do you want me to do that?

